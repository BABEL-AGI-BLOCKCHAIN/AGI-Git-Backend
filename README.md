# AGI-Git-Backend

## Project Overview

This project consists of three main components: User, Contract, and Relay. Users initiate requests through smart contracts, the relay processes these requests, and interacts with users. This package contains the relay module.

## Interaction Architecture Diagram

https://babel-agi-blockchain.notion.site/Nostr-AGI-Git-NAG-Protocol-176c09fee3b78111af95eb829443b5b6

## Installation Requirements

-   Go
-   PostgreSQL

## Startup Guide

```bash
go mod tidy
cd relay-service/
go build -o relayer-basic
POSTGRESQL_DATABASE=postgres://name:pass@localhost:5432/dbname ./relayer-basic
```
