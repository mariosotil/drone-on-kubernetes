# drone-on-kubernetes
Kubernetes files to deploy Drone CI (WORKING IN PROGRESS)

## Features
- Working in progress. This configuration should work, but for some reason in my case, the containers deployed by the Drone Agent can't reach Internet. As fas as I know, Drone was successfully deployed in Kubernetes for other persons.
- Uses a persistent volume for SQLite. If you want to keep it, you will need to create a EBS volume in AWS and update the yaml file. If you want to rid of it, you will need to configure an external relational database.

