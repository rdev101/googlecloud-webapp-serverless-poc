# Serverless Web App

## Goals

- Evaluate viability of cloud deployment strategy [mentioned below](#stack-deployment-in-the-cloud) using google cloud solutions
- Simple performance tests
- Low cost deployment for developemnt process and startup environments with low inital usage of the app
- Evaluate ability to scale up on increased usage demand

## Application stack

- Nodejs/express backend api (stateless)
- React frontend (static content)
- MongoDB datastore (store app data and states)

## Stack deployment in the cloud

- Backend API deployed as stateless serverless function solution
- React frontend served from static storage solutions
- MongoDB PAS (Platform as a service) solution
