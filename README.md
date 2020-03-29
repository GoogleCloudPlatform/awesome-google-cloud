# Awesome List for Google Cloud Platform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/GoogleCloudPlatform/awesome-google-cloud.svg?branch=master)](https://travis-ci.org/GoogleCloudPlatform/awesome-google-cloud)

A curated list of awesome applications, tools, and resources for [Google
Cloud Platform](https://cloud.google.com). Inspired by [other awesome
projects](https://github.com/sindresorhus/awesome).

If you are new to Google Cloud Platform, there is a [free
trial](https://cloud.google.com/free-trial/) to try it out.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Table of Contents**

- [General](#general)
- [Compute](#compute)
  - [App Engine](#app-engine)
  - [Cloud Run](https://github.com/steren/awesome-cloudrun)
  - [Kubernetes Engine](#kubernetes-engine)
  - [Cross-product](#cross-product)
    - [Python](#python)
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

- ["The Google Cloud Developer Cheat Sheet" by Greg Wilson](https://github.com/gregsramblings/google-cloud-4-words) - A list of every product in the Google Cloud family described in 4 words or less
- ["Google Cloud - Jumpstart, Tutorials & Community!" by David das Neves](https://www.linkedin.com/pulse/google-cloud-jumpstart-tutorials-community-david-das-neves/) - Additional links about GCP including tutorials, solutions and community.

## Compute

[Google Compute Engine](https://cloud.google.com/products/compute/) From app platform to containers to VMs, cloud compute tailored to your needs

### App Engine

- [Running Parse server on Google App
  Engine](https://cloud.google.com/nodejs/resources/frameworks/parse-server) -
  deploy and run Parse server on Google App Engine with a sample Node.js
  app
- [SlackEngine](https://github.com/thesandlord/SlackEngine) - a Slack inviter
  running on Google App Engine.

### Kubernetes Engine

- [Real-time Simon Says](https://github.com/grpc-ecosystem/grpc-simon-says) If
  you have played the 70s handheld game "Simon" as a child, you know exactly what this is.
  There are example clients for the Web, IoT (arduino), Android, and command line.
  Built with [gRPC](https://grpc.io) for bidirectional streaming and [Kubernetes](https://kubernetes.io) for scalability.

### Cross-product

#### Python

- [Talisman](https://github.com/GoogleCloudPlatform/flask-talisman) provides
  easy security headers (HTTPS, HSTS, and CSP) for
  [Flask](http://flask.pocoo.org/) applications.

## Cloud AI

[Google Cloud AI](https://cloud.google.com/products/ai/) Fast, large scale, and easy-to-use AI products and services.

### Cloud Vision API

- [Bot for Facebook Messenger](https://github.com/jshin49/fb-vision-bot) This
  bot uses the Google Cloud Vision API to detect faces, labels, landmarks, logos,
  text, explicit content, and attributes in images that are sent to it.

## Storage & Databases

[Google Cloud Storage](https://cloud.google.com/products/storage/) Storage for all your data needs

- [Cloud Datastore adapter for the JSData
  ORM](https://github.com/GoogleCloudPlatform/js-data-cloud-datastore)
  `js-data-cloud-datastore` is an adapter for [JSData](http://www.js-data.io), an
  ORM for Node.js and the browser.

## Monorepo

### Bazel, gRPC, Protocol Buffers

- [StartupOS](https://github.com/google/startup-os) A monorepo with examples for using
  Google's Open Source tools and deploying to the cloud.

## Big Data

[Google Cloud Big Data](https://cloud.google.com/products/big-data/) Efficiently capture, process, and analyze data with Google Cloud data analytics products.

### Apache Beam & Dataflow

- [Scio](https://github.com/spotify/scio) - a Scala API for Google Cloud
  Dataflow and Apache Beam.

### Bigtable

- [Heroic](https://github.com/spotify/heroic) - time series database, works with
  Google Cloud Bigtable as its storage backend.
- [OpenTSDB](http://opentsdb.net/) - time series database, works with Google
  Cloud Bigtable as its storage backend; [deploy it on
  GKE](https://cloud.google.com/solutions/opentsdb-cloud-platform).
- [JanusGraph](http://janusgraph.org/) - distributed graph database, works with
  Google Cloud Bigtable as its storage backend; [deploy it on
  GKE](https://cloud.google.com/solutions/running-janusgraph-with-bigtable).
- [TensorFlow](https://www.tensorflow.org/) - machine learning framework,
  integrates well with Google Cloud Bigtable as both a source and sink for
  high-performance ML model training; use it with CPU, GPU, and TPU. [Train
  ResNet-50 model with TensorFlow + Cloud
  Bigtable](https://cloud.google.com/tpu/docs/tutorials/bigtable-resnet).

### BigQuery

- [Spark-BigQuery](https://github.com/spotify/spark-bigquery) - support for
  Google BigQuery in Apache Spark, SQL and DataFrames.
- [Apache Zeppelin](http://zeppelin.apache.org/) - web-based notebook for
  interactive analytics, works with Google BigQuery

### Pub/Sub

- [PSQ](https://github.com/GoogleCloudPlatform/psq) is a distributed task queue for Python inspired by [rq](http://python-rq.org/) using Google Cloud Pub/Sub.

## Interactive Learning Resources

- [Google Cloud Training Docs](https://cloud.google.com/compute/docs/tutorials) - Google's cloud own practical guide
- [Google Cloud Community Documentation](https://cloud.google.com/community/tutorials/) - Learn how to use Google Cloud Platform services by following these step-by-step walkthroughs and tutorials submitted from the Google Cloud Platform community.
- [Qwiklabs](https://google.qwiklabs.com) - Hands-on Lab for learning Cloud Computing and get Badges.
- [Google Cloud Codelabs](https://codelabs.developers.google.com/cloud) - GCP Codelabs covers topics such as Google Cloud Basics, Compute, Data, Mobile, Monitoring, Machine Learning and Networking.
- [Play with Kubernetes](https://labs.play-with-k8s.com) - A simple, interactive and fun playground to learn Kubernetes
- [Google Cloud Coursera Courses](https://www.coursera.org/googlecloud) - A list of available Google Cloud Courses on Coursera

## Other Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The awesome for awesomes.
- [Awesome Firebase](https://github.com/jthegedus/awesome-firebase).
- [Awesome Go](https://github.com/avelino/awesome-go).
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes).
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow).
- [Awesome GCP Certifications](https://github.com/ddneves/awesome-gcp-certifications).
- [Awesome Cloud Build](https://github.com/Timtech4u/awesome-cloudbuild).

## About This Document

### License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

### Disclaimer

This list is not an official Google product. Links on this list also are not
necessarily to official Google products.

### Contributing

If you have found or built something awesome that uses Google Cloud
Platform, please follow the instructions in [CONTRIBUTING.md](CONTRIBUTING.md)
to get it included here.
