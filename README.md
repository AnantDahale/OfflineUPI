# Offline UPI Payment System

**Author:** Anant Dahale

A Spring Boot backend that demonstrates an offline UPI payment system using a decentralized Bluetooth-style mesh network.

## Features

* Offline payment transaction processing
* Decentralized transaction routing
* AES-256-GCM encryption
* RSA-2048 key encryption
* SHA-256 based transaction identification
* Optimistic locking using JPA `@Version`
* H2 in-memory database
* REST APIs
* Concurrent transaction handling

## Technologies

* Java 17
* Spring Boot
* Spring Data JPA
* H2 Database
* Maven
* REST API
* AES-256-GCM
* RSA-2048
* SHA-256

## Run

```bash
./mvnw spring-boot:run
```

Windows PowerShell:

```powershell
.\mvnw.cmd spring-boot:run
```

Application:

```text
http://localhost:8080
```
