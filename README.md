# FreeBSD-Nodejs 

I modified this script for Node JS xen orchestra startup service. FreeBSD doesn't have the forever-service. if anyone wish to create startup for any nodejs use this script. It would be useful and saves your time.


required package:

forever package.  ( npm install forever -g) 


Create directory following :

For home :  /var/run/forever

Just modifiy according your script location and service name. Rest everything would be good. don't forget this script as executable.

After changing executable add on  /etc/rc.conf  =  servicename_enable="YES"

Options :

start
status
stop
restart
