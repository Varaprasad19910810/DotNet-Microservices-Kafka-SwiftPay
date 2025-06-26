# DotNet Microservices – SwiftPay Transaction Monitoring System

A real-time financial transaction monitoring platform built with .NET 8, Kafka, PostgreSQL, Azure Functions, and Blazor. Designed to simulate secure, scalable SWIFT-based payment processing and alerting.

## Features

- RESTful APIs built in .NET 8
- Real-time message streaming with Kafka
- PostgreSQL integration
- Transaction dashboards (Blazor)
- Azure Functions for background processing
- Docker-ready, cloud deployable

## Microservices Architecture

- **TransactionService**: Create & store payment data
- **NotificationService** *(coming soon)*: Trigger fraud alerts
- **AuditService** *(planned)*: Stores transaction logs
- **UI Dashboard** *(in progress)*: Blazor SPA for insights

## Folder Structure


## Project Status

Base API Complete  
Kafka & PostgreSQL integration planned  
UI dashboard under development

