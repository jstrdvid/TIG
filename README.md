## Start by installing docker and docker-compose
https://dev.to/elalemanyo/how-to-install-docker-and-docker-compose-on-raspberry-pi-1mo


## Pull InfluxdB/Grafana/telegraf

Pull influx:1.8
Pull 
```bash
pull influx:1.8
pull telegraf
pull grafana/grafana
```


## install git clone
https://linuxize.com/post/how-to-install-git-on-raspberry-pi/


## Download this repo
```bash
sudo git clone https://github.com/jstrdvid/TIG.git
```

##Start docker-compose
```bash
sudo docker-compose up -d
```




## Services and Ports
### Grafana
- URL: http://localhost:3000 
- User: admin 
- Password: admin 

### Telegraf
- Port: 8125

### InfluxDB
- Port: 8086
- User: admin 
- Password: admin 
- Database: influx
