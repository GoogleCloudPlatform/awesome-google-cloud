# Awesome List for Google Cloud Platform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/GoogleCloudPlatform/awesome-google-cloud.svg?branch=master)](https://travis-ci.org/GoogleCloudPlatform/awesome-google-cloud)

A curated list of awesome applications, tools, and resources for [Google
Cloud Platform](https://cloud.google.com).  Inspired by [other awesome
projects](https://github.com/sindresorhus/awesome).

If you are new to Google Cloud Platform, there is a [free
trial](https://cloud.google.com/free-trial/) to try it out.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Compute](#compute)
  - [App Engine](#app-engine)
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
- [Other Awesome Lists](#other-awesome-lists)
- [About This Document](#about-this-document)
  - [License](#license)
  - [Disclaimer](#disclaimer)
  - [Contributing](#contributing)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Compute

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
  Built with [gRPC](grpc.io) for bidirectional streaming and [Kubernetes](k8s.io) for scalability.

### Cross-product

#### Python

- [Talisman](https://github.com/GoogleCloudPlatform/flask-talisman) provides
  easy security headers (HTTPS, HSTS, and CSP) for
  [Flask](http://flask.pocoo.org/) applications.

## Cloud AI

### Cloud Vision API

- [Bot for Facebook Messenger](https://github.com/jshin49/fb-vision-bot) This
  bot uses the Google Cloud Vision API to detect faces, labels, landmarks, logos,
  text, explicit content, and attributes in images that are sent to it.

## Storage & Databases

- [Cloud Datastore adapter for the JSData
  ORM](https://github.com/GoogleCloudPlatform/js-data-cloud-datastore)
  `js-data-cloud-datastore` is an adapter for [JSData](http://www.js-data.io), an
  ORM for Node.js and the browser.

## Monorepo

### Bazel, gRPC, Protocol Buffers

- [StartupOS](https://github.com/google/startup-os) A monorepo with examples for using
  Google's Open Source tools and deploying to the cloud.

## Big Data

### Apache Beam & Dataflow

- [Scio](https://github.com/spotify/scio) - a Scala API for Google Cloud
  Dataflow and Apache Beam.

### Bigtable

- [Heroic](https://github.com/spotify/heroic) - time series database, works with
  Google Cloud Bigtable as its storage backend.
- [OpenTSDB](http://opentsdb.net/) - time series database, works with Google
  Cloud Bigtable as its storage backend.

### BigQuery

- [Spark-BigQuery](https://github.com/spotify/spark-bigquery) - support for
  Google BigQuery in Apache Spark, SQL and DataFrames.
- [Apache Zeppelin](http://zeppelin.apache.org/) - web-based notebook for
  interactive analytics, works with Google BigQuery

### Pub/Sub

- [PSQ](https://github.com/GoogleCloudPlatform/psq) is a distributed task queue for Python inspired by [rq](http://python-rq.org/) using Google Cloud Pub/Sub.


## Other Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The awesome for awesomes.
- [Awesome Firebase](https://github.com/afonsopacifer/awesome-firebase).
- [Awesome Go](https://github.com/avelino/awesome-go).
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes).
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow).


## About This Document

### License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


### Disclaimer

This list is not an official Google product.  Links on this list also are not
necessarily to official Google products.


### Contributing

If you have found or built something awesome that uses Google Cloud
Platform, please follow the instructions in [CONTRIBUTING.md](CONTRIBUTING.md)
to get it included here.
