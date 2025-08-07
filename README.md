# automation_testing_remove_404_peviitor_ro

we need to automatically remove all documents from PRODUCTION Apache SOLR with job_link returning 404 as response code

jmeter -n -t get_all_urls.jmx -Duser=your_username -Dpasswd=your_password

jmeter -n -t gremove_404s.jmx

rm jmeter.log

remove input.csv
