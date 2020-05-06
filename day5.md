# AWS LAMBDA - serverless computing service

**Features
		
		- You don't own a server.
		- zero maintenance.
		- Scalability and parallelization. 

**how it is differnt than ec2

-  Ec2 is a server and if it is running then you have to pay for the resources like RAM, core, harsdisk
even if you are not utilizing the resources 100%.

-	In case of serverless,there is a lambda function and no server.
You can store code 
 *no chareges will be applicable for storage of code.

-	aws will be charged for the time * ram used *cpu utilization . 


**Scalability

-	Suppose 1st time your code is using 1 Gb space and 1 core.
And next time your code is updated and now it is your code require 2gb space then automatically get updated. 
- automatic scale up and down.

**Parallelization

-	Lambda creates instances of your function as they are requested.
-	At a time millions of requests are served by same Lambda function

**Difference between mysql installed on ec2 and RDS

1.ec2 is managed by aws but the application managed by thedeveloper.suppose ec2 contain mysql server it will be managed by the developer.but in case of RDS it will be
managed by the aws.
2.backup ,scalability,maintenance is managed by aws in case of RDS.but not in ec2.


**About S3

	-	Everything in s3 bucket is an object.
	-  	Objects are immutable(once they created u cannot updated)

**Example:

	Bucket 		: ram
	Directory	: Test
	File 		: ro.txt
	Content 	: "Welcome to vidyanidhi"
when i created ro.txt.suppose i want to update the ro.txt ,i cant update it.solution on this create another file ro.txt with same name and upate it .then new ro.txt
overright old ro.txt.		



