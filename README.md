# Openstack-and-Chef
CDM Group Project
Cloud Deployment Model Project
The project is related to a use case we could create for image detection/recognition using OpenStack and Chef. We used following of the services while creating this project: -
1. Keystone: - Keystone maintains a central user list that is mapped to all of the OpenStack services that they can utilise. It connects with current backend services like LDAP while serving as a centralised authentication mechanism for cloud computing.
2. Glance: - Discovering, registering, and restoring virtual machine images are all possible with the OpenStack image service. Glance is built on a client-server architecture and provides a user REST API that allows users to query virtual machine image metadata as well as retrieve the actual picture. Glance uses the cached pictures as templates when deploying new virtual machine instances.
3. Cinder: - OpenStack Cinder provides application-specific block-level storage devices for OpenStack compute instances. By combining block storage volumes with Dashboard and Nova, a cloud user can control their storage demands.
4. Heat: - Heat is a service that uses the AWS CloudFormation template format to coordinate many composite cloud applications using the CloudFormation-compatible Query API and the OpenStack-native REST API.
5. Qinling: - Qinling is an OpenStack Function as a Service. The goal of this project is to create a platform for serverless functions (like AWS Lambda). Qinling's plugin structure allows it to handle a variety of container orchestration platforms (Kubernetes/Swarm, for example) and function package storage backends (local/Swift/S3).
6. Chef
