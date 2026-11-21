# StudentPortal Backend API

This repository contains the API contract inventory for StudentPortal. The running API implementation lives in the [backend repository](https://github.com/beyondloop/StudentPortal_Backend).

## Contract

`openapi.yaml` lists the HTTP paths and methods exposed by the Spring Boot controllers, using the `/api/v1` prefix. It is an endpoint inventory generated from controller annotations. It does not yet define request or response schemas, status codes, or per-operation authorization requirements; use the backend implementation as the source of truth for those details.

## Local service

- Base URL: `http://localhost:8080`
- API prefix: `/api/v1`
- The service uses bearer JWT authentication for protected operations. Login and registration are under `/auth`.
- Configure the service and database using the instructions in the backend repository.

## Repositories

- [Frontend](https://github.com/beyondloop/StudentPortal_Frontend)
- [Backend](https://github.com/beyondloop/StudentPortal_Backend)
- API contract: this repository
