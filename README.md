# BAF 0.1.0

[![Join the chat at https://gitter.im/BAFcommunity/Lobby](https://badges.gitter.im/BAFcommunity/Lobby.svg)](https://gitter.im/BAFcommunity/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Blind Attacking Framework

* version [0.1.0] --> [(public releases).(beta versions).(bugfixes patches)]

* this framework is under  AGPLv3 license 

______________________________________________________________________________________________________________________________
what is BAF ? 
* it's a framework written in python [2.7] that is being made specially for blind attacking , ie : attacking random targets with common security issues , targets are generated by the hackers search engine <a href="https://www.shodan.io/explore">"shodan"</a> and vulnerable hosts are hacked in an automated way .

* this framework is completely "neutral" ie: it's not based on shodan API and it has total dependence on web scraping , ie: the only limit on what you can do with it is your immagination as a tester & our programming skills as contributers/owners .   

how to use BAF ? 
* fire up a terminal and sudo apt-get update && apt-get upgrade && apt-get dist-upgrade
* install [ requests , httplib , urllib , time , bs4 "BeautifulSoup" , colored , selenium , sys ] python modules 
* python BAF_0.1.0.py
* enter your shodan's account username and pass
* choose 1 , let it do it's job , press y , close the previous tab , press y ,close the previous tabs ...etc till u have the vulnerable        cams only 
* choose 2 , enter what do u want to search for (ie: NSA) , when it's done , refer to the targets text file , it will contain the targets ip:port
* that's all , till now :)
* DON'T close a loading webpage 
* beta versions will make automated browser open for better understanding ,but you can close the webcam tabs freely 

pictures from the framework
![alt tag](http://www12.0zz0.com/2017/03/22/01/185064220.png)
![alt tag](http://www12.0zz0.com/2017/03/22/01/220329359.png)
![alt tag](http://store6.up-00.com/2017-03/149037301080081.png)


how to contribute? 

the framework is under development so both testers and contributers are more than welcome to help ... so , 
* active testers and bug reporters can help us developing the TODO list of the framework & enjoy watching their TODO wishes - next to    their names - come true :) 
* contributers who provide merged <a href="https://guides.github.com/activities/contributing-to-open-source/">pull requests</a> will be listed below and in the framework contributers section .
* contributers who provide (continuous - dramatic) <a href="https://guides.github.com/activities/contributing-to-open-source/">merged pull requests</a> will be owners and they will have a share in the pro version profit 

how can a pull request be definitely merged?
* adds new from the TODO 
* patces bugs from the TODO 

TODO list(features) in the free version 
- [x] custom search that exports the targets ips / open ports to text file for custom attacks  
- [x] serially open admin/admin webcams login pages 
- [ ] loging into hosts through common services telnet,ssh,ftp,.. etc of the hosts with default credentials
- [ ] bruteforcing webcams login pages
- [ ] automatic search / exploitation of common vulnerabilities on different patforms 
- [ ] handling exceptions and abstracing the project for being efficiently embedded into hacking enviroments/ pentesting labs 
- [ ] rest in peace / pull new features from community :)

TODO list(features) in the pro/paid version 
- [ ] contact shodan creators 
- [ ] GUI
- [ ] automated custom fuzzing 
- [ ] 0-day vulnerabilities mass exploitation 
- [ ] whatever framework capabilitiy that requires tremendous work and totally engineered & programmed by the owners/paid contributers

TODO list(reported bugs) in free version
- [x] <a href="https://github.com/engMaher/BAF/blob/master/README.md">NONE yet</a> 

TODO list(reported bugs) in paid version
- [x] <a href="https://github.com/engMaher/BAF/blob/master/README.md">NONE yet</a> 

list of owners 
- [x] <a href="https://github.com/engMaher">Ahmed Maher</a>

list of contributers
- [x] <a href="https://github.com/engMaher/BAF/blob/master/README.md">NONE yet</a>
