# AWS-Cloud-Scalability-and-Web-Hosting-Solution
AWS Cloud Scalability and Web Hosting Solution


I'm thrilled to share a recent project that allowed me to delve into the world of cloud infrastructure, automation, and web hosting. Here's a brief overview of what I accomplished:

🔹 **Amazon S3 Bucket for Static Website**: I created an Amazon S3 bucket and uploaded an `index.html` file, serving as the foundation for my web application.

🔹 **Real-Time Notifications with AWS Lambda and SNS**: Leveraging AWS Lambda functions and SNS (Simple Notification Service), I set up a system that notified users via email whenever new objects were uploaded to the S3 bucket, enhancing user engagement.

🔹 **Scalable Infrastructure with VPC and Auto Scaling**: To ensure robustness and scalability, I designed a Virtual Private Cloud (VPC) with three public subnets. Within this environment, I configured an Auto Scaling Group (ASG) to automatically adjust the number of EC2 instances based on traffic demands.

🔹 **Automated Deployment with EC2 User Data Scripts**: For the application layer, I employed User Data scripts to streamline the installation of an Apache HTTP server on EC2 instances. These instances retrieved the website content from the S3 bucket.

🔹 **High Availability and Load Balancing**: To ensure high availability, I integrated an Application Load Balancer (ALB) with the ASG, distributing incoming traffic across multiple EC2 instances.

🔹 **Domain Management with Route 53**: Using Amazon Route 53, I associated a custom domain with my web application. This involved creating a hosted zone and updating DNS records. The domain was originally sourced from GoDaddy.

🔹 **Seamless Traffic Routing**: To route traffic to my domain hosted on AWS, I changed the DNS name servers on GoDaddy to point to my AWS name servers, ensuring a smooth transition.

🔹 **Robust Testing and Monitoring**: I rigorously tested the system, including scenarios like verifying the domain URL serving content from multiple IP addresses, terminating instances to assess ASG's capabilities, and triggering auto-scaling based on CPU utilization using CloudWatch alarms.

This project was an incredible learning experience, showcasing my expertise in AWS services, web hosting, automation, and infrastructure management. I'm excited to apply these skills to more complex challenges in the future. Stay tuned for more exciting projects on my journey into the world of cloud computing! 💡🌐 #AWS #CloudComputing #Infrastructure #Automation #WebHosting #Scalability
