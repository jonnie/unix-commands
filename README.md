# unix-commands
Useful UNIX commands and scripts

**Login as another user**

    sudo -S -u jenkins /bin/bash -l
    
**Mount EC2 EBS**

https://rbgeek.wordpress.com/2012/10/08/how-to-mount-ec2-ebs-storage-to-ec2-linux-instance/

**Dump and compress MySQL database**

    mysqldump < mysqldump options> | gzip > outputfile.sql.gz
    
**Uncompress and import MySQL database**

    gunzip < outputfile.sql.gz | mysql < mysql options>
