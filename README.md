# drone-on-kubernetes
Kubernetes files to deploy Drone CI (WORK IN PROGRESS)

## Features
- Work in progress. This configuration should work, but for some reason, the containers deployed by the Drone Agent can't reach Internet. As fas as I know, Drone was successfully deployed in Kubernetes for other users.
- Uses an AWS EBS volume as persistent volume for a SQLite database. If you want to keep it, you will need to create a EBS volume in AWS and update the yaml file, before to deploy Drone. If you want to rid of it, you will need to configure an external relational database.

If you had the same problem trying to deploy Drone on Kubernetes on AWS, and fixed it, please let me know to mario.sotil [at] gmail.com


