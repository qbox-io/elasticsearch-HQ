ElasticHQ
=========

Simplified Monitoring and Management for ElasticSearch clusters.

[![GitHub Stars](https://img.shields.io/github/stars/ElasticHQ/elasticsearch-HQ.svg)](https://github.com/ElasticHQ/elasticsearch-HQ)
[![GitHub Issues](https://img.shields.io/github/issues/ElasticHQ/elasticsearch-HQ.svg)](https://github.com/ElasticHQ/elasticsearch-HQ)
[![Current Version](https://img.shields.io/badge/version-3.0.0-green.svg)](https://github.com/ElasticHQ/elasticsearch-HQ)
![Python](https://img.shields.io/badge/python-v3.4%20%2F%20v3.6-blue.svg)
[![License](https://img.shields.io/badge/license-ASL-blue.svg)](https://opensource.org/licenses/ASL)


![alt text](https://raw.githubusercontent.com/ElasticHQ/elasticsearch-HQ/master/main_dashboard.png)


Key Features
------------
* Works with 2.x, 5.x, 6.x and current versions of Elasticsearch.
* Monitor **many** clusters at once.
* Monitor Nodes, Indices, Shards, and general cluster metrics.
* Create and perform maintenance on Elasticsearch Indices.
* One-Click access to common ES API endpoints.
* Well-documented REST API for extensibility.
* Real-time monitoring charts of important metrics.
* Active project used by Fortune 100 companies around the world.
* Free. ;-)

Requirements
------------

* Python 3.4+


Installation
------------

For **full** installation and configuration instructions, see [Getting Started](http://docs.elastichq.org/installation.html)

1. Download or clone the repository.
2. Open terminal and point to root of repository. Type: ``pip install -r requirements.txt``
3. Run server with: `` python application.py ``. Alternatively: ``./manage.py runserver``
4. Access HQ with: `` http://localhost:5000 ``
5. All API endpoints are available through `` http://localhost:5000/api ``.  

For further installation and configuration help, please read the docs: [ElasticHQ Documentation](http://docs.elastichq.org)

For those of you wanting to use Docker: [ElasticHQ on Dockerhub](https://hub.docker.com/r/elastichq/elasticsearch-hq/)

Useful Links
------------
* [Documentation](http://docs.elastichq.org)
* [Official Website](http://www.elastichq.org)
* [Docker Images](https://hub.docker.com/r/elastichq/elasticsearch-hq/)
* [Google Group](https://groups.google.com/d/forum/elastichq)

Qbox Particular
----------------
We use port 9100 and it has been set to be exposed in the Dockerfile and also in the deployment/supervisord.conf file. If you are running locally, you will want to use http://localhost:9100
