<!--lint ignore no-dead-urls awesome-license-->
# Awesome Google Cloud [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint ignore double-link-->
[<img src="https://www.gstatic.com/images/branding/productlogos/google_cloud/v8/web-96dp/logo_google_cloud_color_1x_web_96dp.png" align="right">](https://cloud.google.com)

<!--lint ignore double-link-->
A curated list of awesome applications, tools, and resources for [Google Cloud](https://cloud.google.com).

Google Cloud is a suite of modular cloud services including computing, data storage, data analytics, and machine learning, alongside a set of management tools.

If you are new to Google Cloud, there is a [free trial](https://cloud.google.com/free-trial/) to try it out.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [General](#general)
- [Compute](#compute)
  - [App Engine](#app-engine)
  - [Cloud Functions](#cloud-functions)
  - [Cloud Run](#cloud-run)
  - [Kubernetes Engine](#kubernetes-engine)
- [Cross-product](#cross-product)
  - [Python](#python)
  - [Security](#security)
- [Cloud AI](#cloud-ai)
  - [Cloud Vision API](#cloud-vision-api)
- [Storage & Databases](#storage--databases)
- [Monorepo](#monorepo)
  - [Bazel, gRPC, Protocol Buffers](#bazel-grpc-protocol-buffers)
- [Big Data](#big-data)
  - [Apache Beam & Dataflow](#apache-beam--dataflow)
  - [Bigtable](#bigtable)
  - [BigQuery](#bigquery)
  - [Pub/Sub](#pubsub)
- [Interactive Learning Resources](#interactive-learning-resources)
- [Other Awesome Lists](#other-awesome-lists)
- [About This Document](#about-this-document)
  - [License](#license)
  - [Disclaimer](#disclaimer)
  - [Contributing](#contributing)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## General

- ["The Google Cloud Developer Cheat Sheet" by Greg Wilson](https://github.com/gregsramblings/google-cloud-4-words) - A list of every product in the Google Cloud family described in 4 words or less.
- ["Google Cloud - Jumpstart, Tutorials & Community!" by David das Neves](https://www.linkedin.com/pulse/google-cloud-jumpstart-tutorials-community-david-das-neves/) - Additional links about GCP including tutorials, solutions and community.

## Compute

- [Google Compute Engine](https://cloud.google.com/products/compute/) - From app platform to containers to VMs, cloud compute tailored to your needs.

### App Engine

- [Running Parse server on Google App Engine](https://cloud.google.com/nodejs/resources/frameworks/parse-server) - Deploy and run Parse server on Google App Engine with a sample Node.js app.
- [SlackEngine](https://github.com/thesandlord/SlackEngine) - Slack inviter running on Google App Engine.

### Cloud Functions

- [Functions Framework](https://github.com/GoogleCloudPlatform/functions-framework) - An open source set of libraries for writing portable Google Cloud functions.

- [Goblet](https://github.com/anovis/goblet) - An open source library for serverless Python application development using Google Cloud functions.

### Cloud Run

- [Awesome Cloud Run](https://github.com/steren/awesome-cloudrun) - Extensive list of awesome Cloud Run applications.

### Kubernetes Engine

- [GKE Policy Automation](https://github.com/google/gke-policy-automation) - Tool and policy library for validating GKE clusters against configuration best practices.

- [Real-time Simon Says](https://github.com/grpc-ecosystem/grpc-simon-says) - If you have played the 70s handheld game "Simon" as a child, you know exactly what this is. There are example clients for the Web, IoT (arduino), Android, and command line. Built with [gRPC](https://grpc.io) for bidirectional streaming and [Kubernetes](https://kubernetes.io) for scalability.

<!--lint ignore double-link-->
- [Click to Deploy Charts Repo](https://github.com/GoogleCloudPlatform/click-to-deploy/tree/master/k8s) - Source for Google Click to Deploy solutions listed on [Google Cloud Marketplace](https://cloud.google.com/marketplace). Provide several examples with detailed READMEs on how-to install in a [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine) cluster.

<!--lint ignore double-link-->
- [Bank of Anthos](https://github.com/GoogleCloudPlatform/bank-of-anthos/) - Sample HTTP-based web application that simulates a bank's payment processing network. It runs on [Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine) and showcases many other Google Cloud products such as [Anthos Service Mesh (ASM)](https://cloud.google.com/anthos/service-mesh), [Anthos Config Management (ACM)](https://cloud.google.com/anthos/config-management), [Cloud Operations](https://cloud.google.com/products/operations), [Cloud SQL](https://cloud.google.com/sql/docs), [Cloud Build](https://cloud.google.com/build), and [Cloud Deploy](https://cloud.google.com/deploy).

<!--lint ignore double-link-->
- [Online Boutique](https://github.com/GoogleCloudPlatform/microservices-demo/) - Sample gRPC-based web application that simulates an ecommerce store. It runs on [Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine), is built of 11 microservices in 5 different languages, and showcases many other Google Cloud products.

## Cross-product

### Python

- [Talisman](https://github.com/GoogleCloudPlatform/flask-talisman) - Provides easy security headers (HTTPS, HSTS, and CSP) for [Flask](http://flask.pocoo.org/) applications.

### Security

- [Forseti](https://forsetisecurity.org/) - Scan your GCP resources to ensure that access controls are set as you intended and protected against unsafe changes.

## Cloud AI

- [Google Cloud AI](https://cloud.google.com/products/ai/) - Fast, large scale, and easy-to-use AI products and services.

### Cloud Vision API

- [Bot for Facebook Messenger](https://github.com/jshin49/fb-vision-bot) - This bot uses the Google Cloud Vision API to detect faces, labels, landmarks, logos, text, explicit content, and attributes in images that are sent to it.

## Storage & Databases

- [Google Cloud Storage](https://cloud.google.com/products/storage/) - Storage for all your data needs.
- [Cloud Datastore adapter for the JSData ORM](https://github.com/GoogleCloudPlatform/js-data-cloud-datastore) - `js-data-cloud-datastore` is an adapter for [JSData](http://www.js-data.io), an ORM for Node.js and the browser.

## Monorepo

### Bazel, gRPC, Protocol Buffers

- [StartupOS](https://github.com/google/startup-os) - A monorepo with examples for using Google's Open Source tools and deploying to the cloud.

## Big Data

- [Google Cloud Big Data](https://cloud.google.com/products/big-data/) - Efficiently capture, process, and analyze data with Google Cloud data analytics products.

### Apache Beam & Dataflow

- [Dataflow Templates](https://github.com/GoogleCloudPlatform/DataflowTemplates) - Google-provided Cloud Dataflow template pipelines for solving simple in-Cloud data tasks.
- [Scio](https://github.com/spotify/scio) - A Scala API for Google Cloud Dataflow and Apache Beam.

### Bigtable

- [Heroic](https://github.com/spotify/heroic) - Time series database, works with Google Cloud Bigtable as its storage backend.
- [OpenTSDB](http://opentsdb.net/) - Time series database, works with Google Cloud Bigtable as its storage backend; [deploy it on GKE](https://cloud.google.com/solutions/opentsdb-cloud-platform).
- [JanusGraph](http://janusgraph.org/) - Distributed graph database, works with Google Cloud Bigtable as its storage backend; [deploy it on GKE](https://cloud.google.com/solutions/running-janusgraph-with-bigtable).
- [TensorFlow](https://www.tensorflow.org/) - Machine learning framework, integrates well with Google Cloud Bigtable as both a source and sink for high-performance ML model training; use it with CPU, GPU, and TPU. [Train ResNet-50 model with TensorFlow + Cloud Bigtable](https://cloud.google.com/tpu/docs/tutorials/bigtable-resnet).

### BigQuery

- [Apache Zeppelin](http://zeppelin.apache.org/) - Web-based notebook for interactive analytics, works with Google BigQuery.
- [Dekart](https://dekart.xyz/) - Geospatial analysis tool for Google BigQuery based on Kepler.gl.
- [SQLtools for BigQuery](https://github.com/evidence-dev/sqltools-bigquery-driver) - VSCode Extension to run queries and explore databases.
- [BigQuery Utils](https://github.com/GoogleCloudPlatform/bigquery-utils) - Useful scripts, udfs, views, and other utilities for migration and data warehouse operations in BigQuery.
- [Spark-BigQuery](https://github.com/spotify/spark-bigquery) - Support for Google BigQuery in Apache Spark, SQL and DataFrames.

### Pub/Sub

- [PSQ](https://github.com/GoogleCloudPlatform/psq) - Distributed task queue for Python inspired by [rq](http://python-rq.org/) using Google Cloud Pub/Sub.

## Interactive Learning Resources

- [Google Cloud Training Docs](https://cloud.google.com/compute/docs/tutorials) - Google's cloud own practical guide.
- [Google Cloud Community Documentation](https://cloud.google.com/community/tutorials/) - Learn how to use Google Cloud services by following these step-by-step walkthroughs and tutorials submitted from the Google Cloud community.
- [Qwiklabs](https://google.qwiklabs.com) - Hands-on Lab for learning Cloud Computing and get Badges.
- [Google Cloud Codelabs](https://codelabs.developers.google.com/cloud) - GCP Codelabs covers topics such as Google Cloud Basics, Compute, Data, Mobile, Monitoring, Machine Learning and Networking.
- [Play with Kubernetes](https://labs.play-with-k8s.com) - A simple, interactive and fun playground to learn Kubernetes.
- [Google Cloud Coursera Courses](https://www.coursera.org/googlecloud) - A list of available Google Cloud Courses on Coursera.

## Other Awesome Lists
<!--lint ignore double-link-->
- [Awesome](https://github.com/sindresorhus/awesome) - The awesome for awesomes.
- [Awesome Firebase](https://github.com/jthegedus/awesome-firebase) - App development platform built on Google Cloud.
- [Awesome Go](https://github.com/avelino/awesome-go) - A statically typed, compiled high-level programming language designed at Google.
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) - An open-source container orchestration system for automating software deployment, scaling, and management.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) - A free and open-source software library for machine learning and artificial intelligence.
- [Awesome GCP Certifications](https://github.com/ddneves/awesome-gcp-certifications) - Demonstrate your knowledge and skills with an industry-recognized Google Cloud certification.
- [Awesome Cloud Build](https://github.com/Timtech4u/awesome-cloudbuild) - Serverless CI/CD platform from Google Cloud.
- [Awesome Bigtable](https://github.com/zrosenbauer/awesome-bigtable) - Low-latency NoSQL database service for machine learning, operational analytics, and user-facing applications at scale.
- [Awesome Spanner](https://github.com/rakyll/awesome-spanner) - A highly scalable database that combines unlimited scalability with relational semantics.


## About This Document

### License
<!--lint ignore double-link-->
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)
<!--lint ignore double-link-->
This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

### Disclaimer

This list is not an official Google product. Links on this list also are not necessarily to official Google products.

### Contributing

If you have found or built something awesome that uses Google Cloud, please follow the instructions in [CONTRIBUTING.md](CONTRIBUTING.md) to get it included here.
