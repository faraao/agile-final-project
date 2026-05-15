# Agile Final Project: Accounts Service

![Build Status](https://github.com/faraao/agile-final-project/actions/workflows/ci-build.yaml/badge.svg)

## Project Description
This project is a microservice for managing user accounts. It provides a RESTful API to Create, Read, Update, and Delete (CRUD) account information. It is built using Python, Flask, and deployed using a CI/CD pipeline with GitHub Actions and Tekton on Kubernetes/OpenShift.

## Architecture
- **Language:** Python
- **Framework:** Flask
- **Database:** PostgreSQL (or in-memory for testing)
- **CI/CD:** GitHub Actions & Tekton
- **Deployment:** Docker & Kubernetes (OpenShift)

## Features
- Create a new account
- List all accounts
- Read an account's details
- Update an existing account
- Delete an account

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the application: `flask run`
