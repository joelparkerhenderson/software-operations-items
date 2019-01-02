# Software operations outline

This page is based on the excellent work [here](https://github.com/kamranahmedse/developer-roadmap). Work in progress. Feedback welcome.

Contents:

* [](#)


## Infrastructure as Code

Provision:

* Terraform
* Cloud Formation

Configure:

* Ansible
* Chef
* Puppet
* Salt

Orchestrate:

* Kubernetes
* Mesos
* Swarm
* Nomad

Continuous integration:

* Jenkins
* Travis
* Circle
* Teamcity
* Drone

Containers:

* Docker
* rkt
* LXC

Cloud providers:

* Amazon Web Services (AWS)
* Google Cloud Platform (GCP)
* Micrsoft Azure
* Rackspace Cloud
* Digital Ocean
* Heroku


## Server software

Server software types:

* Web server
* Credential server
* Database server for SQL
* Database server for NoSQL
* Database server for graphs
* Database as a service
* Email server
* Email as a service
* Messaging server
* Search server
* Reverse proxy server
* Object cache server
* Load balancer
* Firewall

Web server:

* Apache
* Nginx
* Tomcat
* Caddy
* IIS

Credential server:

* Hashicorp Vault
* AWS Key Management Service

Database server for relational data and SQL:

* PostgreSQL
* MySQL
* Aurora
* Oracle
* MariaDB
* MSSQL

Database server for freeform data and NoSQL:

* Spanner
* Cassandra
* MongoDB
* RethinkDB
* Couchbase

Database server for graph data and GraphQL:

* Neo4j
* Amazon Nepture
* ArangoDB
* Orient DB
* Titan Database
* RedisGraph

Database as a service:
	
* AWS Relational Database Service (RDS)
* Google BigQuery
* Microsoft Azure SQL Database
* IBM Db2 on Cloud
* SAP Cloud Platform, SAP HANA Service

Email server:

* Postfix
* Sendmail

Email as a service:

* AWS Simple Email Service (SMS)
* Mailchimp Mandrill
* SendGrid
* SendInBlue
* MailGun
* Mailjet
* Postmark
* Elastic Email

Chat server or services:

* IRC
* Mattermost
* Slack

Message server:

* RabbitMQ
* ZeroMQ
* Kafka

Search server:

* ElasticSearch
* Solr
* Sphinx

Reverse proxy:

* Varnish
* nginx
* Squid

Object cache server:

* Memcache
* Apache Ignite
* Redis

Load balancer:

* AWS Elastic Load Balancing (ELB) 
* AWS Elastic Beanstalk (EB)
* AWS Fargate
* TODO

Firewall:

* IPFW
* AWS Web Application Firewall (WAF)
* TODO


## Server operation

Admnistration areas:

* Process management
* Threads and concurrency
* Sockets
* Memory/storage
* I/O Management
* Virtualization
* File systems

Infrastructure monitoring:

* Datadog
* Nagios
* Icinga
* Zabbix

Application monitoring:

* Monit
* AppDynamics
* New Relic

Log monitoring:

* Splunk
* Sumo Logic
* ELK Stack
* Graylog
* Papertrail

Networking:

* HTTP/HTTP
* SSSL/TLS
* FTP/SFTP
* DNS
* VPN
* NAT


## API

Architecture:

* REST/RESTful
* GraphQL
* RPC

Communication:

* Google Protobuf
* Google FlatBuffers
* Apache Thrift
* Formats e.g JSON, XML, CSV, TSV

Authentication and authorization areas:

* OAuth
* Basic authentication
* Token authentication
* Multi-factor authentication (MFA)
* JavaScript Web Token (JWT)
* OpenID Connect
* Lightweight Directory Access Protocol (LDAP)
* Microsfot Active Directory (AD)
* Security Assertion Markup Language (SAML)
* Single Sign On (SS)
* Federated identity

Authentication as a service:

* Okta
* Auth0
* Google
* Facebook
