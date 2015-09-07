# linux-and-network-information

* AWS Failover simple architecture

In my case we have 2 web server and 1 Database server, I used Amazon Router 53 DNS for the Failover Architecture with the DNS primary and secondry servers

  * we have web servers on diffrent grographical location
  * primary is stop working then after specific time DNS is point to secondry server  and this is decide by the Route health check
  * when primary will be in working condition DNS point back to the primary server 
  
* Commercial SSL Purchasing and configuration
1). Geneate the csr file 
  * openssl req -new -newkey rsa:2048 -nodes -keyout server.key -out server.csr
  * when we purchase ssl , company ask some question
  * city, country
  * for what purpose for a company or personal
  * then they authorized

* Paths
  * relative, A relativfe path is a way to specify the location of a directory relative to another directory
  * absolute,  the absolute path contains the root directory and all other subdirectories that contain a file or folder
  
* Usage of teamviewer software
* Main panel of AWS
  * where diffrent application run and we select according to our need
  * first OS then choose an instance type then configure instance detail then add storage  then instance tay and security
* Mail relog
  * AWS give services of ses (simple email service) you can just send email no inbox in this
* # root user 
* $ ordinary user
* sudo su,  switching user with bash which is non-log-in shell
* sudo su- , This time it is a login shell, so /etc/profile, .profile and .bashrc are executed and
            * you will find yourself in root's home directory with root's environment
            
* Data have issues, if issues then logs, when logs then we clustor to handle logs
  * ELK Elasticsearch log, it function is "indexing of logs"
  * Logstash, this clustor gathered logs and deliver to Elastic search
  * kibana , kibana is just for visualizing
* SSL , SSL Certificates are small data files that digitally bind a cryptographic key to an organization's details. When installed on a web server, it activates the padlock and the https protocol (over port 443) and allows secure connections from a web server to a browser.

 

