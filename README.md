# User service

> This microservice handles requests for publishing, updating and deleting users as either patient or dentist clients


## Getting started


To run this service you need to follow the steps described below:


### Add .env file

The .env file contains information about the *MQTT broker* and *MongoDB*. This informatin is best contained locally on your computer, to keep your connections private. You will have to insert a *MONGO_URI* for your database and a *BROKER_URL*.

For our instances of the service, we used [HiveMQ](https://www.hivemq.com/mqtt/) being a private broker.

```
MONGO_URI = "YOUR_URI"
BROKER_URL = "YOUR_BROKER:PORT_NR"
```

### Run User Service

In order to build and run the User service you need to type these commands in to your terminal:

```
go build
go run main.go
```
 

### Contributions

**Developers:**
- Mohamad Khalil
- Lucas Holter
- Cornelia Olofsson Larsson 

**Code Reviewers:**
- James Klouda 
- Jonatan Boman 
- Joel Mattson
