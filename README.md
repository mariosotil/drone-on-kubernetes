# drone-on-kubernetes
Kubernetes files to deploy Drone CI (WORKING IN PROGRESS)

## Features
- Working in progress. This configuration should work, but for some reason in my case, the containers deployed by the Drone Agent can't reach Internet. As fas as I know, Drone was successfully deployed in Kubernetes for other persons.
- Uses an AWS EBS volume as persistent volume for a SQLite database. If you want to keep it, you will need to create a EBS volume in AWS and update the yaml file, before to deploy Drone. If you want to rid of it, you will need to configure an external relational database.

If you have the same problem like me, deploying Drone on Kubernetes on AWS, and fixed it, please let me know to mario.sotil [at] gmail.com


