
# Secure Multi-AZ Deployment ☁️


This project showcases a robust production environment within a Virtual Private Cloud (VPC) designed with a strong emphasis on security. The architecture leverages two availability zones (AZs), employing Auto Scaling Groups (ASG) and an Application Load Balancer (ALB) to enhance resilience and ensure high availability.
## Screenshots

![Screenshot 2023-04-14 at 7 06 46 PM](https://docs.aws.amazon.com/images/vpc/latest/userguide/images/vpc-example-private-subnets.png)


## 💻 Key Features 💻

**Multi-AZ Deployment:** The application is deployed across two availability zones, promoting fault tolerance and minimizing downtime.   

**Auto Scaling Groups (ASG):** ASGs are employed to automatically adjust the number of instances based on demand, optimizing resource utilization and providing scalability.

**Application Load Balancer (ALB):** An ALB is utilized to evenly distribute incoming traffic across multiple instances, improving availability and fault tolerance.

**Private Subnet Security:** The deployment is configured within private subnets to enhance security, ensuring that servers receive requests exclusively through the load balancer.

**NAT Gateway for Internet Access:** To enable internet access for servers while maintaining a secure environment, a Network Address Translation (NAT) gateway is deployed. Importantly, the NAT gateway is set up in both availability zones for redundancy.


## Documentation

º https://docs.aws.amazon.com/vpc/  
º https://docs.aws.amazon.com/autoscaling/  
º https://docs.aws.amazon.com/elasticloadbalancing/    
ºhttps://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html  
º https://docs.aws.amazon.com/iam/
