nginx-iplookup-module
========================

nginx iplookup module

##nginx
	
	location /iplookup/extra {
	        iplookup "/usr/local/share/iplookup/ip.db";
	        iplookup_extra on;
	}
	

