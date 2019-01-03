# Software operations outline

This page is based on the excellent work [here](https://github.com/kamranahmedse/developer-roadmap). Work in progress. Feedback welcome.

Contents:

* [Infrastructure as Code](#infrastructure-as-code)
* [Server software](#server-software)
* [Server operation](#server-operation)
* [API](#api)
* [Testing](#testing)


## Infrastructure as Code

Provision:

* [Terraform by Hashicorp](https://www.terraform.io/)
* [AWS CloudFormation](https://aws.amazon.com/cloudformation/)

Configure:

* [RedHat Ansible](https://www.ansible.com/)
* [Chef](https://www.chef.io/)
* [Puppet](https://puppet.com/)
* [SaltStack](https://www.saltstack.com/)

Orchestrate:

* [Kubernetes](https://kubernetes.io/)
* [Apache Mesos](https://mesos.apache.org/)
* [Docker Swarm](https://docker.com)
* [Nomad by Hashicorp](https://www.nomadproject.io/)

Containers:

* [Docker](https://docker.com)
* [rkt](https://github.com/rkt/rkt) - pronounced "rocket"
* [LXC](https://linuxcontainers.org/) - Linux containers

Cloud providers:

* [Amazon Web Services (AWS)](https://aws.amazon.com)
* [Google Cloud Platform (GCP)](https://cloud.google.com/)
* [Microsoft Azure](https://azure.microsoft.com)
* [Rackspace Cloud](https://www.rackspace.com/en-us/cloud)
* [Digital Ocean](https://digitalocean.com)

Platform as a service:

* [Heroku](https://www.heroku.com/)
* [Pivotal Cloud Foundry (PCF)](https://pivotal.io/platform)
* [SAP Cloud Platform](https://cloudplatform.sap.com/)

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

* [NGINX](https://www.nginx.com/)
* [Apache HTTP Server](https://httpd.apache.org/)
* [Apache Tomcat](http://tomcat.apache.org/)
* [Caddy](https://caddyserver.com/)
* [Microsoft IIS](https://www.iis.net/)

Credential server:

* [Vault by Hashicorp](https://www.vaultproject.io/)
* [AWS Key Management Service](https://aws.amazon.com/kms/)

Database server for relational data and SQL:

* [PostgreSQL](https://www.postgresql.org/)
* [MySQL](https://www.mysql.com/)
* [Amazon Aurora](https://aws.amazon.com/rds/aurora/)
* [Oracle](https://www.oracle.com/database/)
* [MariaDB](https://mariadb.org/)
* [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/s)

Database server for freeform data and NoSQL:

* [Cloud Spanner by Google](https://cloud.google.com/spanner/)
* [CockroachDB](https://www.cockroachlabs.com/)
* [Apache Cassandra](https://cassandra.apache.org/)
* [MongoDB](https://www.mongodb.com/)
* [RethinkDB](https://www.rethinkdb.com/)
* [Couchbase](https://www.couchbase.com/)
* [ArangoDB](https://www.arangodb.com/)

Database server for graph data and GraphQL:

* [Neo4j](https://neo4j.com/)
* [Amazon Nepture](https://aws.amazon.com/neptune/)
* [OrientDB](https://orientdb.com/)
* [Titan Database](https://titan.thinkaurelius.com/)
* [RedisGraph](http://redisgraph.io/)

Database as a service:
	
* [AWS Relational Database Service (RDS)](https://aws.amazon.com/rds/)
* [Google BigQuery](https://cloud.google.com/bigquery/)
* [Microsoft Azure Cloud SQL Database](https://azure.microsoft.com/en-us/services/sql-database/)
* [IBM Db2 on Cloud](https://www.ibm.com/cloud/db2-on-cloud)
* [SAP Cloud Platform, SAP HANA Service](https://cloudplatform.sap.com/capabilities/product-info.SAP-Cloud-Platform-SAP-HANA-service.cca998f4-97ca-4b81-8c45-9b5bc8588776.html)

Email server:

* [Postfix](https://www.postfix.org/)
* [Sendmail](https://www.sendmail.org/)

Email as a service:

* [AWS Simple Email Service (SMS)](https://aws.amazon.com/ses/)
* [Mandrill by Mailchimp](https://mandrill.com/)
* [SendGrid](https://sendgrid.com/)
* [SendInBlue](https://www.sendinblue.com/)
* [MailGun](https://www.mailgun.com/)
* [Mailjet](https://www.mailjet.com/)
* [Postmark](https://postmarkapp.com/)
* [Elastic Email](https://elasticemail.com/)

Chat server or services:

* [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat)
* [Mattermost](https://mattermost.com/)
* [Slack](https://slack.com)

Message server:

* [RabbitMQ](https://www.rabbitmq.com/)
* [ZeroMQ](https://zeromq.org/)
* [Apache Kafka](https://kafka.apache.org/)

Search server:

* [Elasticsearch](https://www.elastic.co/)
* [Apache Lucene](http://lucene.apache.org/)
* [Apache Solr](http://lucene.apache.org/solr/)
* [Sphinx](https://sphinxsearch.com/)

Reverse proxy:

* [Varnish Cache](https://varnish-cache.org/)
* [NGINX reverse proxy](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/)
* [Squid caching proxy](http://www.squid-cache.org/)

Object cache server:

* [Memcached](https://memcached.org/)
* [Apache Ignite](https://ignite.apache.org/)
* [Redis](https://redis.io/)

Load balancer:

* [AWS Elastic Load Balancing (ELB)](https://aws.amazon.com/elasticloadbalancing/)
* [AWS Elastic Beanstalk (EB)](https://aws.amazon.com/elasticbeanstalk/)
* [AWS Fargate](https://aws.amazon.com/fargate/)
* TODO

Firewall:

* [IPFW](https://en.wikipedia.org/wiki/Ipfirewall)
* [AWS Web Application Firewall (WAF)](https://aws.amazon.com/waf/)
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

* [Datadog](https://www.datadoghq.com/)
* [Nagios](https://www.nagios.org/)
* [Icinga](https://icinga.com/)
* [Zabbix](https://www.zabbix.com/)

Application monitoring:

* [Monit](https://mmonit.com/monit/)
* [AppDynamics](https://www.appdynamics.com/)
* [New Relic](https://newrelic.com/)

Log monitoring:

* [Splunk](https://www.splunk.com)
* [Sumo Logic](https://www.sumologic.com/)
* [ELK Stack](https://www.elastic.co/elk-stack)
* [Graylog](https://www.graylog.org/)
* [Papertrail](https://papertrailapp.com/)

Networking:

* [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)
* [SSL](https://en.wikipedia.org/wiki/Secure_Sockets_Layer)
* [TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security)
* [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol)
* [DNS](https://en.wikipedia.org/wiki/Domain_Name_System)
* [VPN](https://en.wikipedia.org/wiki/Virtual_private_network)
* [NAT](https://en.wikipedia.org/wiki/Network_address_translation)


## API

Architecture:

* [REST](https://en.wikipedia.org/wiki/Representational_state_transfer)
* [GraphQL](https://en.wikipedia.org/wiki/GraphQL)
* [Remote procedure call (RPC)](https://en.wikipedia.org/wiki/Remote_procedure_call)
* [WebSocket](https://en.wikipedia.org/wiki/WebSocket)

Communication:

* [Protocol Buffers by Google](https://en.wikipedia.org/wiki/Protocol_Buffers)
* [FlatBuffers by Google](https://en.wikipedia.org/wiki/FlatBuffers)
* [Apache Thrift](https://en.wikipedia.org/wiki/Apache_Thrift)
* [Apache Avro](https://en.wikipedia.org/wiki/Apache_Avro)

Formats:

* [JSON](https://en.wikipedia.org/wiki/JSON)
* [XML](https://en.wikipedia.org/wiki/XML)
* [Comma-separated values (CSV)](https://en.wikipedia.org/wiki/Comma-separated_values)
* [Tab-separated values (TSV)](https://en.wikipedia.org/wiki/Tab-separated_values)

Authentication and authorization areas:

* [OAuth](https://en.wikipedia.org/wiki/OAuth)
* [Basic access authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)
* Token authentication
* [Multi-factor authentication (MFA)](https://en.wikipedia.org/wiki/Multi-factor_authentication)
* [JSON Web Token (JWT)](https://en.wikipedia.org/wiki/JSON_Web_Token)
* [OpenID Connect](https://en.wikipedia.org/wiki/OpenID_Connect)
* [Lightweight Directory Access Protocol (LDAP)](https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol)
* [Active Directory (AD)](https://en.wikipedia.org/wiki/Active_Directory)
* [Security Assertion Markup Language (SAML)](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language)
* [Single sign on (SSO)](https://en.wikipedia.org/wiki/Single_sign-on)
* [Federated identity](https://en.wikipedia.org/wiki/Federated_identity)

Authentication as a service:

* [Okta](https://www.okta.com/)
* [Auth0](https://auth0.com/)
* [Google Sign-In](https://developers.google.com/identity/sign-in/web/sign-in)
* [Facebook Login](https://developers.facebook.com/docs/facebook-login/)


## Testing

Test types:

* [Unit testing](https://en.wikipedia.org/wiki/Unit_testing)
* [Functional testing](https://en.wikipedia.org/wiki/Functional_testing)
* [Integration testing](https://en.wikipedia.org/wiki/Integration_testing)
* [System testing](https://en.wikipedia.org/wiki/System_testing)
* [Load testing](https://en.wikipedia.org/wiki/Load_testing)
* [Fuzz testing](https://en.wikipedia.org/wiki/Fuzz_testing)
* [Penetration testing](https://en.wikipedia.org/wiki/Penetration_test)
* [Regression testing](https://en.wikipedia.org/wiki/Regression_testing)
* [Operational acceptance testing](https://en.wikipedia.org/wiki/Operational_acceptance_testing)
* [Destructive testing](https://en.wikipedia.org/wiki/Destructive_testing)
* [Security testing](https://en.wikipedia.org/wiki/Security_testing)

Test frameworks:

* [Selenium](https://www.seleniumhq.org/)
* [Cypress](https://www.cypress.io/)
* [TestCafe](https://testcafe.devexpress.com/)
* [Mocha](https://mochajs.org/)
* [Chai](https://www.chaijs.com/)
* [Ava](https://github.com/avajs/ava)
* [Karma](https://karma-runner.github.io/)
* [Jasmine](https://jasmine.github.io/)
* [Protractor](https://www.protractortest.org/)
* [Jest](https://jestjs.io/)
* [Enzyme](https://github.com/airbnb/enzyme)

Continuous integration and continuous delivery:

* [Jenkins](https://jenkins.io/)
* [Travis CI](https://travis-ci.org/)
* [CircleCI](https://circleci.com/)
* [Teamcity](https://www.jetbrains.com/teamcity/)
* [Drone](https://github.com/drone/drone)
