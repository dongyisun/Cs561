# Cs561

First, I lanuch the amazon linux 2 ami(hvm) - kkernel 5.10. Then, I added the port 8080 to the security inbound rules.

Second, I connect ec2 by using the ec2 instance connect on the aws console.

Third, I installed the npm and apimocker in to the ec2 backend.

I create these two files in the repo by vim command.

I lanunch the server by using commend apimocker -c /home/ec2-user/config.json

Fianlly, enter the http://18.209.62.136:8080/data/2.5/weather to see the response.json file's content.
