# HAproxy_withDocker
Create haproxy folder with 3 file
# Run: docker-compose up
# Add 2 domain testhaproxy2.com and testhaproxy1.com in /etc/hosts:
        -127.0.0.1	testhaproxy2.com
        -127.0.0.1	testhaproxy1.com
Go to http://testhaproxy1.com:8080, this come to yahoo.com
Refresh http://testhaproxy2.com:8080, this come to 3 site 
