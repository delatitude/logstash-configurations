# Logstash configurations
- basic samples
- csv to postgres with geoip
- csv to mssqlserver
- csv to elastic
- csv to command line
- insert statement to mssqlserver

## How to run logstash piplines from command line
```
./logstash -e 'input { stdin { } } output { stdout {} }'

E:\logstash-7.0.0\bin\logstash.bat -f E:\logstash-7.0.0\bin\logstash-simple.conf --debug

./logstash -f ".\logstash-txt.conf" --debug

./logstash -f "E:\logstash-7.0.0\config\myconfigs\logstash-generator.conf"

```




