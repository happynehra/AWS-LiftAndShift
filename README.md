# Flow Of Execution
1. Login to AWS Account.  
2. Created Key Pairs. 
3. Created Security groups. 
4. Launched Instances with user data (Bash Script). 
5. Updated IP to name mapping in route 53. 
6. Build Application from source code. 
7. Uploaded to S3 bucket. 
8. Downloaded artifact to Tomcat Ec2 Instance. 
9. Setup ELB with HTTPS (Certificate from Amazon Certificate Manager). 
10. Maped ELB Endpoint to the website name in Godaddy DNS. 
11. Verify. 

# Problems fixed in this project
1. Complex Management. 
2. Scale Up/Down complexity. 
3. UpFront CapEx and Regular OpEx. 
4. Manual Process. 
5. Difficult to automate. 
6. Time Consuming. 

# Benefits
1. PayAsUgo. 
2. IAAS. 
3. Flexiblity. 
4. Automation. 
5. Ease of Infra Management.  

# Serives Used 
1. Ec2 Instances for Tomcat, RabbitMq, Memcache, Mysql. 
2. ELB (Load Balancer).
3. Autoscaling. 
4. S3/EFS Storage. 
5. Route 53. 

![image](Images/image.png)















