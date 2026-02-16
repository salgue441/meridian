# Meridian

**Meridian** is a distributed log aggregation and real-time observability engine built from first principles. It ingests logs, metrics, and traces from distributed services, streams them through a custom partitioned commit log, processes them with configurable rules, and surface insights via a real-time dashboard and alerting system.

## System Overview

Meridian is composed of xis primary subsystems that form an end-to-end observability pipeline. Data flows from instrumented services through collection agents, into a distributed streaming backbone, through a process engine, into persistent storage, and finally out to consumers via a real-time dashboard and alert system.
