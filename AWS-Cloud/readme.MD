<h2>AWS SERVICES</h2>

- EC2 Instances --> VM for Tomcat, RabbitMQ, Memcache, MySQL <p>
- ELB (Load Balancer) --> Nginx load balancer replacement <p>
- Autoscaling --> Automation for VM scaling<p>
- S3/EFS Storage --> Shared storage<p>
- Route 53 --> Private DNS service<p>

<h2>Instances (VMs)</h2>

| Name           | OS             | Service   | Version | Private IP    |
|:--------------:|:--------------:|:---------:|:-------:|:-------------:|
| vprofile-db01  | CentOS 7       | MariaDB   | 5.5.68  | 172.31.85.138 |
| vprofile-rm01  | CentOS 7       | RabbitMQ  | 3.10.0  | 172.31.82.96  |
| vprofile-mc01  | CentOS 7       | Memcached | 1.4.15  | 172.31.89.73  |
| vprofile-app01 | Ubuntu 18.04   | Tomcat    | 8.5.39  | 172.31.87.1   |  
