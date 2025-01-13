# AaravLabs

Aarav Labs is an innovative learning platform designed to help middle schoolers with AI steps and answer analysis. It combines tough but interesting questions with AI analysis to help kids know what they got right or where they went wrong.

This repository contains the deployment configuration for both the frontend and backend of the application. 

## Deploying

Since all the code is containerized, you can deploy 

1. Clone the repository with `git clone https://github.com/AaravLabsOfficial/AaravLabs`
2. `cd AaravLabs`
3. Write your own env variables based on `.example.env`
4. Deploy with `sudo docker compose up -d`

## Building

The recommended way to deploy AaravLabs is using the `docker-compose.yaml` file provided in this repository. This file will build and deploy both the frontend and backend applications.

## Using a Different Deployment Method

While using `docker-compose.yaml` is recommended, you can also build and deploy the frontend and backend applications separately.  

Instructions for building and deploying the frontend and backend applications can be found in the respective repository's README files:

* [Frontend](https://github.com/AaravLabsOfficial/Frontend)
* [Backend](https://github.com/AaravLabsOfficial/Backend)
