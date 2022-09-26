# **0x0F. Load balancer**
---
## HAProxy
HAProxy, which stands for High Availability Proxy, is a popular open source software TCP/HTTP Load Balancer and proxying solution which can be run on Linux, macOS, and FreeBSD.
Its most common use is to improve the performance and reliability of a server environment by distributing the workload across multiple servers (e.g. web, application, database).
It is used in many high-profile environments, including: GitHub, Imgur, Instagram, and Twitter.

## Background Context
You have been given 2 additional servers:

* gc-[STUDENT_ID]-web-02-XXXXXXXXXX
* gc-[STUDENT_ID]-lb-01-XXXXXXXXXX
Let’s improve our web stack so that there is redundancy for our web servers.
This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. 
If one web server fails, we will still have a second one to handle requests.

For this project, you will need to write Bash scripts to automate your work.
All scripts must be designed to configure a brand new Ubuntu server to match the task requirements.
