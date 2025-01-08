# docker-configs

## Intro

I tinker a lot with different applications and ideas. Whenever possible I use docker containers for these excursions so I can quickly spin up an environment and tear it down when no longer needed.

Some of these might be interesting or even helpful to others when trying to run said service in a test environment or just as inspiration for docker files in general.

## Requirements

As of creation of this repository I have been working with docker version **27.3.1**.
Keep this in mind when trying to run one of the compose files.

## Applications

All the following apps use a docker compose config for running locally in a non production-ready manner.
This not to say they could not be used as inspiration for production, but as this was not my main goal I can give no guarantees.

All files are provided as-is, adapt to your own requirements.

| App                                          | Description                                                                                                                                                                                                |
| -------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **8n8**                                      | A versatile, open-source communication platform designed for secure and scalable team collaboration. It supports messaging, video conferencing, and integrations with other tools to enhance productivity. |
| **Gitea**                                    | A lightweight, self-hosted Git service for managing version control repositories. Perfect for developers, it offers features like pull requests, issue tracking, and CI/CD pipelines.                      |
| **llm-playground**                           | A combination of ollama service and web-ui to have a local llm instance to experiment with. (no ChatGPT API or similar here. Pure local!) </br>**TODO: needs further documentation**                       |
| **MongoDB**                                  | A NoSQL database that stores data in flexible, JSON-like documents. It is ideal for handling large-scale applications requiring scalability and dynamic schemas.                                           |
| **MySQL**                                    | A popular relational database management system known for its reliability and ease of use. It supports structured data storage and is widely used in web and enterprise applications.                      |
| **Node-RED**                                 | A powerful, flow-based development tool for wiring together hardware devices, APIs, and online services. Its visual interface simplifies the creation of automation workflows.                             |
| **openHAB**                                  | A smart home integration platform that unifies and automates various devices and technologies. It enables users to create personalized and energy-efficient home automation systems.                       |
| [**OpenOlat**](openolat/README.md)           | An open-source learning management system (LMS) designed for creating and managing e-learning courses. It supports collaborative learning, assessments, and course tracking.                               |
| [**Paperless-ngx**](paperless-ngx/README.md) | A digital document management system that helps you organize and archive scanned documents and PDFs efficiently. With robust tagging and search features, it simplifies going paperless.                   |
| **Pi-hole**                                  | A network-wide ad blocker that acts as a DNS sinkhole, protecting your devices from unwanted ads and trackers. It enhances browsing speed and privacy on all connected devices.                            |
