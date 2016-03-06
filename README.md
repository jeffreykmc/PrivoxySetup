# PrivoxySetup



### Edit Privoxy Config 

vi /etc/config/privoxy

Add following line 

[...]

	list	filterfile	'adfilter.filter'
	list 	actionsfile	'adfilter.action'

[...]

Download adfilter.filter & adfilter.action from GITHub

Restart privoxy 

/etc/init.d/privoxy restart



### Acknowledge
1. https://github.com/chenxsan/Privoxy
2. 
