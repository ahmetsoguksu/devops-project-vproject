<h2>AWS SERVICES</h2>

- EC2 Instances --> VM for Tomcat, RabbitMQ, Memcache, MySQL <p>
- ELB (Load Balancer) --> Nginx load balancer replacement <p>
- Autoscaling --> Automation for VM scaling<p>
- S3/EFS Storage --> Shared storage<p>
- Route 53 --> Private DNS service<p>

<h2>Instances (VMs)</h2>

| Name  | OS             | Service   | Version | Private IP |
|:-----:|:--------------:|:---------:|:-------:|:----------:|
| db01  | CentOS 7       | MariaDB   |         |            |
| rm01  | CentOS 7       | RabbitMQ  |         |            |
| mc01  | CentOS 7       | Memcached |         |            |
| app01 | Ubuntu 18.04   | Tomcat    |         |            |  
