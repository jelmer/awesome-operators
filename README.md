# Awesome Operators in the Wild

This is a fork from https://github.com/operator-framework/awesome-operators
which has been archived.

Operators are Kubernetes native applications. We define native as being both
managed using the Kubernetes APIs via kubectl and ran on Kubernetes as
containers. Operators take advantage of Kubernetes’s extensibility to deliver
the automation advantages of cloud services like provisioning, scaling, and
backup/restore while being able to run anywhere that Kubernetes can run.

This list is built by the community. Have you built or are you using an Operator
that is not listed? Please send a pull request against [repos.txt](repos.txt)
and we will add that Operator to the list. 

| Github | Description | License | Stargazers | Last Update |
|--------|-------------|---------|------------|-------------|
| [rook/rook](https://github.com/rook/rook) | Storage Orchestration for Kubernetes | Apache-2.0 | 9312 | 2021-12-08 |
| [jetstack/cert-manager](https://github.com/jetstack/cert-manager) | Automatically provision and manage TLS certificates in Kubernetes | Apache-2.0 | 8113 | 2021-12-08 |
| [argoproj/argo-cd](https://github.com/argoproj/argo-cd) | Declarative continuous deployment for Kubernetes. | Apache-2.0 | 7787 | 2021-12-08 |
| [fluxcd/flux](https://github.com/fluxcd/flux) | Successor: https://github.com/fluxcd/flux2 — The GitOps Kubernetes operator | Apache-2.0 | 6676 | 2021-12-08 |
| [prometheus-operator/prometheus-operator](https://github.com/prometheus-operator/prometheus-operator) | Prometheus Operator creates/configures/manages Prometheus clusters atop Kubernetes | Apache-2.0 | 6410 | 2021-12-08 |
| [vmware-tanzu/velero](https://github.com/vmware-tanzu/velero) | Backup and migrate Kubernetes applications and their persistent volumes | Apache-2.0 | 5831 | 2021-12-08 |
| [kubevirt/kubevirt](https://github.com/kubevirt/kubevirt) | Kubernetes Virtualization API and runtime in order to define and manage virtual machines. | Apache-2.0 | 2902 | 2021-12-08 |
| [strimzi/strimzi-kafka-operator](https://github.com/strimzi/strimzi-kafka-operator) | Apache Kafka running on Kubernetes | Apache-2.0 | 2815 | 2021-12-08 |
| [zalando/postgres-operator](https://github.com/zalando/postgres-operator) | Postgres operator creates and manages PostgreSQL clusters running in Kubernetes | MIT | 2179 | 2021-12-08 |
| [CrunchyData/postgres-operator](https://github.com/CrunchyData/postgres-operator) | Production PostgreSQL for Kubernetes, from high availability Postgres clusters to full-scale database-as-a-service. | Apache-2.0 | 2148 | 2021-12-07 |
| [openfaas/faas-netes](https://github.com/openfaas/faas-netes) | Serverless on Kubernetes with OpenFaaS | MIT | 1871 | 2021-12-08 |
| [GoogleCloudPlatform/spark-on-k8s-operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator) | Kubernetes operator for managing the lifecycle of Apache Spark applications on Kubernetes.  | Apache-2.0 | 1757 | 2021-12-07 |
| [elastic/cloud-on-k8s](https://github.com/elastic/cloud-on-k8s) | Elastic Cloud on Kubernetes | NOASSERTION | 1687 | 2021-12-08 |
| [banzaicloud/bank-vaults](https://github.com/banzaicloud/bank-vaults) | A Vault swiss-army knife: a K8s operator, Go client with automatic token renewal, automatic configuration, multiple unseal options and more. A CLI tool to init, unseal and configure Vault (auth methods, secret engines). Direct secret injection into Pods. | Apache-2.0 | 1522 | 2021-12-07 |
| [flant/shell-operator](https://github.com/flant/shell-operator) | Shell-operator is a tool for running event-driven scripts in a Kubernetes cluster | Apache-2.0 | 1486 | 2021-12-08 |
| [kubeflow/training-operator](https://github.com/kubeflow/training-operator) | Training operators on Kubernetes. | Apache-2.0 | 981 | 2021-12-07 |
| [kudobuilder/kudo](https://github.com/kudobuilder/kudo) | Kubernetes Universal Declarative Operator (KUDO) | Apache-2.0 | 972 | 2021-12-07 |
| [FairwindsOps/rbac-manager](https://github.com/FairwindsOps/rbac-manager) | A Kubernetes operator that simplifies the management of Role Bindings and Service Accounts. | Apache-2.0 | 971 | 2021-12-07 |
| [pingcap/tidb-operator](https://github.com/pingcap/tidb-operator) | TiDB operator creates and manages TiDB clusters running in Kubernetes. | Apache-2.0 | 902 | 2021-12-07 |
| [banzaicloud/logging-operator](https://github.com/banzaicloud/logging-operator) | Logging operator for Kubernetes based on Fluentd and Fluentbit | Apache-2.0 | 870 | 2021-12-06 |
| [reactive-tech/kubegres](https://github.com/reactive-tech/kubegres) | Kubegres is a Kubernetes operator allowing to deploy one or many clusters of PostgreSql instances and manage databases replication, failover and backup. | Apache-2.0 | 852 | 2021-12-07 |
| [spotahome/redis-operator](https://github.com/spotahome/redis-operator) | Redis Operator creates/configures/manages high availability redis with sentinel automatic failover atop Kubernetes. | Apache-2.0 | 789 | 2021-12-08 |
| [jaegertracing/jaeger-operator](https://github.com/jaegertracing/jaeger-operator) | Jaeger Operator for Kubernetes simplifies deploying and running Jaeger on Kubernetes. | Apache-2.0 | 752 | 2021-12-06 |
| [coreos/vault-operator](https://github.com/coreos/vault-operator) | Run and manage Vault on Kubernetes simply and securely | Apache-2.0 | 752 | 2021-12-06 |
| [Altinity/clickhouse-operator](https://github.com/Altinity/clickhouse-operator) | The ClickHouse Operator creates, configures and manages ClickHouse clusters running on Kubernetes | Apache-2.0 | 737 | 2021-12-07 |
| [bitpoke/mysql-operator](https://github.com/bitpoke/mysql-operator) | Asynchronous MySQL Replication on Kubernetes using Percona Server and Openark's Orchestrator. | Apache-2.0 | 679 | 2021-12-07 |
| [upmc-enterprises/elasticsearch-operator](https://github.com/upmc-enterprises/elasticsearch-operator) | manages elasticsearch clusters | BSD-3-Clause | 663 | 2021-12-06 |
| [apache/camel-k](https://github.com/apache/camel-k) | Apache Camel K is a lightweight integration platform, born on Kubernetes, with serverless superpowers | Apache-2.0 | 639 | 2021-12-08 |
| [fluxcd/helm-operator](https://github.com/fluxcd/helm-operator) | Successor: https://github.com/fluxcd/helm-controller — The Flux Helm Operator, once upon a time a solution for declarative Helming. | Apache-2.0 | 630 | 2021-12-01 |
| [minio/operator](https://github.com/minio/operator) | MinIO Operator creates/configures/manages MinIO clusters on Kubernetes | AGPL-3.0 | 594 | 2021-12-08 |
| [banzaicloud/koperator](https://github.com/banzaicloud/koperator) | Oh no! Yet another Apache Kafka operator for Kubernetes | Apache-2.0 | 576 | 2021-12-07 |
| [nats-io/nats-operator](https://github.com/nats-io/nats-operator) | NATS Operator | Apache-2.0 | 520 | 2021-12-05 |
| [banzaicloud/istio-operator](https://github.com/banzaicloud/istio-operator) | An operator that manages Istio deployments on Kubernetes | Apache-2.0 | 512 | 2021-11-17 |
| [mongodb/mongodb-kubernetes-operator](https://github.com/mongodb/mongodb-kubernetes-operator) | MongoDB Community Kubernetes Operator | NOASSERTION | 471 | 2021-12-08 |
| [kubedb/operator](https://github.com/kubedb/operator) | KubeDB Operator | NOASSERTION | 459 | 2021-12-07 |
| [jenkinsci/kubernetes-operator](https://github.com/jenkinsci/kubernetes-operator) | Kubernetes native Jenkins Operator | NOASSERTION | 441 | 2021-12-07 |
| [lyft/flinkk8soperator](https://github.com/lyft/flinkk8soperator) | Kubernetes operator that provides control plane for managing Apache Flink applications | Apache-2.0 | 438 | 2021-12-06 |
| [kanisterio/kanister](https://github.com/kanisterio/kanister) | An extensible framework for  application-level data management on Kubernetes | Apache-2.0 | 402 | 2021-12-07 |
| [k8gb-io/k8gb](https://github.com/k8gb-io/k8gb) | A cloud native Kubernetes Global Balancer | Apache-2.0 | 361 | 2021-12-06 |
| [grafana-operator/grafana-operator](https://github.com/grafana-operator/grafana-operator) | An operator for Grafana that installs and manages Grafana instances, Dashboards and Datasources through Kubernetes/OpenShift CRs | Apache-2.0 | 350 | 2021-12-05 |
| [rabbitmq/cluster-operator](https://github.com/rabbitmq/cluster-operator) | RabbitMQ Cluster Kubernetes Operator | MPL-2.0 | 343 | 2021-12-07 |
| [ongres/stackgres](https://github.com/ongres/stackgres) | StackGres Operator, Full Stack PostgreSQL on Kubernetes // !! Mirror repository of https://gitlab.com/ongresinc/stackgres, only accept Merge Requests there. | AGPL-3.0 | 309 | 2021-12-08 |
| [percona/percona-xtradb-cluster-operator](https://github.com/percona/percona-xtradb-cluster-operator) | Percona Distribution for MySQL Operator | Apache-2.0 | 298 | 2021-12-08 |
| [GoogleCloudPlatform/airflow-operator](https://github.com/GoogleCloudPlatform/airflow-operator) | Kubernetes custom controller and CRDs to managing Airflow | Apache-2.0 | 289 | 2021-10-28 |
| [searchlight/searchlight](https://github.com/searchlight/searchlight) | 🔦 Alerts for Kubernetes | Apache-2.0 | 289 | 2021-12-05 |
| [libopenstorage/stork](https://github.com/libopenstorage/stork) | Stork - Storage Orchestration Runtime for Kubernetes | Apache-2.0 | 284 | 2021-12-08 |
| [hashicorp/terraform-k8s](https://github.com/hashicorp/terraform-k8s) | Terraform Cloud Operator for Kubernetes | MPL-2.0 | 276 | 2021-11-25 |
| [jetstack/navigator](https://github.com/jetstack/navigator) | Managed Database-as-a-Service (DBaaS) on Kubernetes | Apache-2.0 | 269 | 2021-11-29 |
| [jetstack/navigator](https://github.com/jetstack/navigator) | Managed Database-as-a-Service (DBaaS) on Kubernetes | Apache-2.0 | 269 | 2021-11-29 |
| [mongodb/mongodb-enterprise-kubernetes](https://github.com/mongodb/mongodb-enterprise-kubernetes) | MongoDB Enterprise Kubernetes Operator | NOASSERTION | 263 | 2021-11-29 |
| [pravega/zookeeper-operator](https://github.com/pravega/zookeeper-operator) | Kubernetes Operator for Zookeeper | Apache-2.0 | 241 | 2021-12-07 |
| [datastax/cass-operator](https://github.com/datastax/cass-operator) | The DataStax Kubernetes Operator for Apache Cassandra | Apache-2.0 | 240 | 2021-12-04 |
| [tektoncd/operator](https://github.com/tektoncd/operator) | Kubernetes operator to manage installation, updation and uninstallation of tektoncd projects (pipeline, …) | Apache-2.0 | 234 | 2021-12-08 |
| [banzaicloud/hpa-operator](https://github.com/banzaicloud/hpa-operator) | Horizontal Pod Autoscaler operator for Kubernetes. Annotate and let the HPA operator do the rest. | Apache-2.0 | 232 | 2021-11-25 |
| [ucloud/redis-cluster-operator](https://github.com/ucloud/redis-cluster-operator) | Redis Cluster Operator creates and manages Redis Clusters atop Kubernetes. | Apache-2.0 | 222 | 2021-11-30 |
| [oracle/weblogic-kubernetes-operator](https://github.com/oracle/weblogic-kubernetes-operator) | Oracle Weblogic Server Kubernetes Operator | NOASSERTION | 206 | 2021-12-07 |
| [scylladb/scylla-operator](https://github.com/scylladb/scylla-operator) | The Kubernetes Operator for ScyllaDB | Apache-2.0 | 181 | 2021-12-07 |
| [GoogleCloudPlatform/elcarro-oracle-operator](https://github.com/GoogleCloudPlatform/elcarro-oracle-operator) | El Carro is a new project that offers a way to run Oracle databases in Kubernetes as a portable, open source, community driven, no vendor lock-in container orchestration system. El Carro provides a powerful declarative API for comprehensive and consistent configuration and deployment as well as for real-time operations and monitoring. | Apache-2.0 | 179 | 2021-12-01 |
| [arangodb/kube-arangodb](https://github.com/arangodb/kube-arangodb) | ArangoDB Kubernetes Operator - Start ArangoDB on Kubernetes in 5min | Apache-2.0 | 177 | 2021-12-07 |
| [apache/rocketmq-operator](https://github.com/apache/rocketmq-operator) | Apache RocketMQ Operator | Apache-2.0 | 175 | 2021-12-06 |
| [openshift/hive](https://github.com/openshift/hive) | API driven OpenShift cluster provisioning and management | Apache-2.0 | 169 | 2021-12-07 |
| [VictoriaMetrics/operator](https://github.com/VictoriaMetrics/operator) | Kubernetes operator for Victoria Metrics | Apache-2.0 | 163 | 2021-12-05 |
| [ucloud/redis-operator](https://github.com/ucloud/redis-operator) | Redis operator build a Highly Available Redis cluster with Sentinel atop Kubernetes | Apache-2.0 | 161 | 2021-11-25 |
| [AmadeusITGroup/Redis-Operator](https://github.com/AmadeusITGroup/Redis-Operator) | Redis Operator creates/configures/manages Redis clusters atop Kubernetes | MIT | 151 | 2021-11-19 |
| [solo-io/envoy-operator](https://github.com/solo-io/envoy-operator) | Envoy Operator creates/configures/manages Envoy clusters atop Kubernetes | Apache-2.0 | 149 | 2021-11-13 |
| [bitpoke/wordpress-operator](https://github.com/bitpoke/wordpress-operator) | Bitpoke Kubernetes operator for WordPress | Apache-2.0 | 148 | 2021-12-01 |
| [isaaguilar/terraform-operator](https://github.com/isaaguilar/terraform-operator) | A Kubernetes CRD to handle terraform operations | Apache-2.0 | 146 | 2021-12-02 |
| [isindir/sops-secrets-operator](https://github.com/isindir/sops-secrets-operator) | Kubernetes SOPS secrets operator | MPL-2.0 | 143 | 2021-11-24 |
| [ianlewis/memcached-operator](https://github.com/ianlewis/memcached-operator) | A Kubernetes operator for memcached | Apache-2.0 | 140 | 2021-10-12 |
| [aws/amazon-sagemaker-operator-for-k8s](https://github.com/aws/amazon-sagemaker-operator-for-k8s) | Amazon SageMaker operator for Kubernetes | Apache-2.0 | 134 | 2021-12-06 |
| [giantswarm/aws-operator](https://github.com/giantswarm/aws-operator) | Manages Kubernetes clusters running on AWS | Apache-2.0 | 121 | 2021-12-03 |
| [practo/k8s-worker-pod-autoscaler](https://github.com/practo/k8s-worker-pod-autoscaler) | Kubernetes autoscaler for the workers. Resource is called WPA. Queues Supported: SQS, Beanstalkd. | Apache-2.0 | 117 | 2021-11-24 |
| [radanalyticsio/spark-operator](https://github.com/radanalyticsio/spark-operator) | Operator for managing the Spark clusters on Kubernetes and OpenShift. | Apache-2.0 | 116 | 2021-11-22 |
| [sapcc/kubernetes-operators](https://github.com/sapcc/kubernetes-operators) | Operators that automate common tasks for managing Openstack on Kubernetes. | Apache-2.0 | 115 | 2021-08-30 |
| [amaizfinance/redis-operator](https://github.com/amaizfinance/redis-operator) | Redis Operator for Kubernetes | Apache-2.0 | 98 | 2021-11-04 |
| [linki/cloudformation-operator](https://github.com/linki/cloudformation-operator) | A Kubernetes operator for managing CloudFormation stacks via a CustomResource | MIT | 95 | 2021-10-18 |
| [Azure/azure-databricks-operator](https://github.com/Azure/azure-databricks-operator) | Kubernetes Operator for Databricks | MIT | 94 | 2021-11-03 |
| [upmc-enterprises/kong-operator](https://github.com/upmc-enterprises/kong-operator) | manages kong clusters | BSD-3-Clause | 87 | 2021-06-04 |
| [Dynatrace/dynatrace-oneagent-operator](https://github.com/Dynatrace/dynatrace-oneagent-operator) | Kubernetes/Openshift Operator for managing Dynatrace OneAgent deployments | Apache-2.0 | 86 | 2021-12-07 |
| [maistra/istio-operator](https://github.com/maistra/istio-operator) | null | Apache-2.0 | 72 | 2021-12-03 |
| [amaizfinance/secreter](https://github.com/amaizfinance/secreter) | Kubernetes operator and CLI tool for encrypting and managing Kubernetes secrets | Apache-2.0 | 69 | 2021-11-08 |
| [streamnative/function-mesh](https://github.com/streamnative/function-mesh) | The serverless framework purpose-built for event streaming applications. | undefined | 68 | 2021-12-01 |
| [TykTechnologies/tyk-operator](https://github.com/TykTechnologies/tyk-operator) | Tyk Operator for Kubernetes | MPL-2.0 | 68 | 2021-11-30 |
| [sky-big/pulsar-operator](https://github.com/sky-big/pulsar-operator) | Pulsar Operator creates/configures/manages pulsar clusters atop Kubernetes | MIT | 64 | 2021-12-01 |
| [kloeckner-i/db-operator](https://github.com/kloeckner-i/db-operator) | The DB Operator creates databases and make them available in the cluster via Custom Resource. | Apache-2.0 | 63 | 2021-12-07 |
| [habitat-sh/habitat-operator](https://github.com/habitat-sh/habitat-operator) | A Kubernetes operator for Habitat services | Apache-2.0 | 61 | 2021-08-24 |
| [stakater/Konfigurator](https://github.com/stakater/Konfigurator) | A kubernetes operator that dynamically generates and manages app configuration based on kubernetes resources  – [✩Star] if you're using it! | undefined | 59 | 2021-10-26 |
| [huanwei/rocketmq-operator](https://github.com/huanwei/rocketmq-operator) | Create, operate and scale self-healing RocketMQ clusters on Kubernetes. | Apache-2.0 | 58 | 2021-11-04 |
| [storageos/cluster-operator](https://github.com/storageos/cluster-operator) | cluster-operator creates, configures and helps manage StorageOS cluster on Kubernetes | MIT | 58 | 2021-10-22 |
| [banzaicloud/pvc-operator](https://github.com/banzaicloud/pvc-operator) | null | Apache-2.0 | 48 | 2021-04-28 |
| [grtl/mysql-operator](https://github.com/grtl/mysql-operator) | Kubernetes Custom Resource for MySQL | Apache-2.0 | 47 | 2021-11-13 |
| [patoarvizu/kms-vault-operator](https://github.com/patoarvizu/kms-vault-operator) | Kubernetes operator to manage KMS-encrypted Vault secrets | Apache-2.0 | 46 | 2021-11-18 |
| [banzaicloud/prometheus-jmx-exporter-operator](https://github.com/banzaicloud/prometheus-jmx-exporter-operator) | null | Apache-2.0 | 45 | 2021-09-16 |
| [jw-s/redis-operator](https://github.com/jw-s/redis-operator) | Redis operator for Kubernetes | MIT | 45 | 2021-05-25 |
| [eclipse-che/che-operator](https://github.com/eclipse-che/che-operator) | null | EPL-2.0 | 42 | 2021-12-08 |
| [teseraio/ensemble](https://github.com/teseraio/ensemble) | Modular Kubernetes operator to manage the lifecycle of databases | MPL-2.0 | 41 | 2021-11-18 |
| [deepinsight/mxnet-operator](https://github.com/deepinsight/mxnet-operator) | Tools for ML/MXNet on Kubernetes. | Apache-2.0 | 41 | 2021-03-08 |
| [mongodb/mongodb-atlas-kubernetes](https://github.com/mongodb/mongodb-atlas-kubernetes) | MongoDB Atlas Kubernetes Operator - Manage your MongoDB Atlas clusters from Kubernetes | Apache-2.0 | 40 | 2021-12-06 |
| [aliyx/tidb-operator](https://github.com/aliyx/tidb-operator) | Tidb-operator creates/configures/manages tidb clusters atop Kubernetes | undefined | 40 | 2020-08-07 |
| [halkyonio/operator](https://github.com/halkyonio/operator) | Kubernetes Operator simplifying the development of microservices on k8s ! | Apache-2.0 | 39 | 2021-07-20 |
| [application-stacks/runtime-component-operator](https://github.com/application-stacks/runtime-component-operator) | A generic Operator capable of deploying any runtime component image with enterprise QoS and bind it to other services | Apache-2.0 | 38 | 2021-12-07 |
| [movetokube/postgres-operator](https://github.com/movetokube/postgres-operator) | PostgreSQL operator for Kubernetes | MIT | 38 | 2021-11-24 |
| [movetokube/postgres-operator](https://github.com/movetokube/postgres-operator) | PostgreSQL operator for Kubernetes | MIT | 38 | 2021-11-24 |
| [piontec/netperf-operator](https://github.com/piontec/netperf-operator) | Kubernetes operator to measure TCP transmission speed between 2 pods | Apache-2.0 | 37 | 2021-05-27 |
| [falarica/steerd-presto-operator](https://github.com/falarica/steerd-presto-operator) | Kubernetes (K8s) Operator for PrestoDB | Apache-2.0 | 36 | 2021-09-18 |
| [pravega/pravega-operator](https://github.com/pravega/pravega-operator) | Pravega Kubernetes Operator | Apache-2.0 | 33 | 2021-12-07 |
| [eshepelyuk/cmak-operator](https://github.com/eshepelyuk/cmak-operator) | CMAK (prev. Kafka Manager) for Kubernetes | MIT | 32 | 2021-12-03 |
| [verfio/fortio-operator](https://github.com/verfio/fortio-operator) | Load Testing Operator within the Kubernetes cluster and outside of it. | Apache-2.0 | 32 | 2021-12-01 |
| [Orange-OpenSource/galera-operator](https://github.com/Orange-OpenSource/galera-operator) | Galera Operator automates tasks for managing a Galera cluster in Kubernetes | Apache-2.0 | 32 | 2021-12-03 |
| [paulczar/gcp-cloud-compute-operator](https://github.com/paulczar/gcp-cloud-compute-operator) | gcp operator for kubernetes | Apache-2.0 | 28 | 2021-11-12 |
| [aquasecurity/aqua-operator](https://github.com/aquasecurity/aqua-operator) | The aqua-operator is a group of controllers that runs within a Kubernetes or Openshift cluster that provides a means to deploy and manage Aqua Security cluster and Components. | undefined | 27 | 2021-11-28 |
| [influxdata/influxdb-operator](https://github.com/influxdata/influxdb-operator) | The Kubernetes operator for InfluxDB and the TICK stack. | Apache-2.0 | 25 | 2021-08-08 |
| [travelaudience/aerospike-operator](https://github.com/travelaudience/aerospike-operator) | Manages Aerospike clusters atop Kubernetes, automating their creation and administration. | Apache-2.0 | 24 | 2021-09-07 |
| [integr8ly/gitea-operator](https://github.com/integr8ly/gitea-operator) | An Operator that installs Gitea | Apache-2.0 | 22 | 2021-11-17 |
| [personio/newrelic-alert-manager](https://github.com/personio/newrelic-alert-manager) | Kubernetes operator for managing New Relic alerts and dashboards | MIT | 22 | 2021-11-05 |
| [OpenLiberty/open-liberty-operator](https://github.com/OpenLiberty/open-liberty-operator) | null | EPL-1.0 | 21 | 2021-12-08 |
| [kube-incubator/redis-operator](https://github.com/kube-incubator/redis-operator) | A redis-operator based on operator-sdk. | Apache-2.0 | 21 | 2021-09-23 |
| [jomkz/rethinkdb-operator](https://github.com/jomkz/rethinkdb-operator) | A Kubernetes operator to manage RethinkDB clusters. | Apache-2.0 | 21 | 2020-09-14 |
| [dastergon/vegeta-operator](https://github.com/dastergon/vegeta-operator) | Kubernetes Operator for running HTTP load testing scenarios with Vegeta | Apache-2.0 | 21 | 2021-09-20 |
| [slok/service-level-operator](https://github.com/slok/service-level-operator) | Manage application's SLI and SLO's easily with the application lifecycle inside a Kubernetes cluster | Apache-2.0 | 20 | 2021-07-06 |
| [Nuance-XINFRA/zookeeper-operator](https://github.com/Nuance-XINFRA/zookeeper-operator) | Kubernetes Operator for Apache Zookeeper | Apache-2.0 | 20 | 2021-06-15 |
| [appsody/appsody-operator](https://github.com/appsody/appsody-operator) | An Operator for deploying Appsody based applications to Kubernetes | Apache-2.0 | 18 | 2021-12-03 |
| [Juniper/contrail-operator](https://github.com/Juniper/contrail-operator) | Juniper K8s contrail operator | Apache-2.0 | 17 | 2021-09-01 |
| [craftypath/sops-operator](https://github.com/craftypath/sops-operator) | A Kubernetes operator for Mozilla SOPS | Apache-2.0 | 17 | 2021-11-08 |
| [lukasz-antoniak/neo4j-operator](https://github.com/lukasz-antoniak/neo4j-operator) | Kubernetes Neo4J Operator | Apache-2.0 | 16 | 2021-11-10 |
| [patoarvizu/vault-dynamic-configuration-operator](https://github.com/patoarvizu/vault-dynamic-configuration-operator) | Operator to handle dynamic configuration of https://github.com/banzaicloud/bank-vaults | Apache-2.0 | 16 | 2021-05-21 |
| [app-sre/deployment-validation-operator](https://github.com/app-sre/deployment-validation-operator) | The Deployment Validator Operator (DVO) checks deployments and other resources against a curated collection of best practices. | undefined | 15 | 2021-12-06 |
| [blackducksoftware/opssight-connector](https://github.com/blackducksoftware/opssight-connector) | OpsSight Connector documentation | Apache-2.0 | 14 | 2020-09-14 |
| [skylt/rabbitmq-operator](https://github.com/skylt/rabbitmq-operator) | Rabbitmq operator for kubernetes | MIT | 13 | 2021-02-25 |
| [geritol/secret-backup-operator](https://github.com/geritol/secret-backup-operator) | Kubernetes operator for backing up secrets | MIT | 13 | 2021-10-12 |
| [IBM/ibm-block-csi-operator](https://github.com/IBM/ibm-block-csi-operator) | Operator for IBM block storage CSI driver | Apache-2.0 | 11 | 2021-12-06 |
| [malagoli/oracle-db-operator](https://github.com/malagoli/oracle-db-operator) | A kubernetes operator to manage the lifecycle of an Oracle Container Database | MIT | 11 | 2021-05-21 |
| [lightbend/console-charts](https://github.com/lightbend/console-charts) | Lightbend Console Helm Charts | Apache-2.0 | 11 | 2021-11-25 |
| [disposab1e/sealed-secrets-operator-helm](https://github.com/disposab1e/sealed-secrets-operator-helm) | [DEPRECATED] Sealed Secrets Operator (Helm) installs Sealed Secrets in OpenShift and Kubernetes. | Apache-2.0 | 10 | 2021-06-28 |
| [didil/autobucket-operator](https://github.com/didil/autobucket-operator) | Cloud Storage Kubernetes Operator with Go and Operator SDK | MIT | 9 | 2021-12-01 |
| [vgkowski/cassandra-operator](https://github.com/vgkowski/cassandra-operator) | kubernetes operator for cassandra clusters automation | Apache-2.0 | 9 | 2021-09-10 |
| [hazelcast/hazelcast-operator](https://github.com/hazelcast/hazelcast-operator) | null | Apache-2.0 | 9 | 2021-11-17 |
| [interconnectedcloud/qdr-operator](https://github.com/interconnectedcloud/qdr-operator) | null | Apache-2.0 | 8 | 2021-08-26 |
| [kube-incubator/tomcat-operator](https://github.com/kube-incubator/tomcat-operator) | Tomcat operator for Kubernetes | undefined | 8 | 2020-05-01 |
| [krestomatio/m4e-operator](https://github.com/krestomatio/m4e-operator) | Moodle Operator for Kubernetes or OKD (Openshift), based on Ansible Operator SDK. | Apache-2.0 | 6 | 2021-12-03 |
| [whyseco/mailgun-operator](https://github.com/whyseco/mailgun-operator) | Mailgun Operator for kubernetes | MIT | 5 | 2021-03-10 |
| [thatInfrastructureGuy/vaultsync-operator](https://github.com/thatInfrastructureGuy/vaultsync-operator) | Periodically syncs secrets from various Vaults to Kubernetes Secrets.  | Apache-2.0 | 5 | 2021-05-11 |
| [openshift/node-problem-detector-operator](https://github.com/openshift/node-problem-detector-operator) | An operator to run Node Problem Detector on OpenShift | Apache-2.0 | 5 | 2021-11-09 |
| [aerogear-attic/android-sdk-operator](https://github.com/aerogear-attic/android-sdk-operator) | Android SDK kubernetes operator | Apache-2.0 | 4 | 2020-02-14 |
| [deepfabric/elasticell-operator](https://github.com/deepfabric/elasticell-operator) | k8s operator for elasticell | undefined | 4 | 2019-07-08 |
| [mesosphere/kudo-spark-operator](https://github.com/mesosphere/kudo-spark-operator) | KUDO Spark Operator | Apache-2.0 | 4 | 2021-12-01 |
| [openshift/aws-efs-operator](https://github.com/openshift/aws-efs-operator) | Operator to manage AWS EFS on OpenShift | Apache-2.0 | 4 | 2021-08-26 |
| [aceeric/nuxeo-operator](https://github.com/aceeric/nuxeo-operator) | A Go language Nuxeo Operator supporting OpenShift and Kubernetes | Apache-2.0 | 4 | 2021-02-22 |
| [hijak/ghost-operator](https://github.com/hijak/ghost-operator) | Kubernetes Operator for ghost blog | undefined | 2 | 2021-06-02 |
| [aerogear/ups-config-operator](https://github.com/aerogear/ups-config-operator) | null | Apache-2.0 | 2 | 2019-05-24 |
| [janepelladinesh/postgresql-operator](https://github.com/janepelladinesh/postgresql-operator) | null | undefined | 0 | 2019-12-27 |
| [Hyperfoil/horreum-operator](https://github.com/Hyperfoil/horreum-operator) | Operator managing Horreum instance in Openshift | Apache-2.0 | 0 | 2021-08-05 |
| [Hyperfoil/hyperfoil-operator](https://github.com/Hyperfoil/hyperfoil-operator) | Operator for installation in Openshift | undefined | 0 | 2021-09-13 |