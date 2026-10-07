# AWS / Serverless Engineering

## Focus
Build small, understandable cloud services before adding unnecessary infrastructure.

## Reference architecture
~~~text
Client
  ↓
HTTP / API
  ↓
AWS Lambda
  ↓
Business logic
  ├── S3
  ├── external APIs
  └── structured storage
  ↓
Logs / telemetry
~~~

## Security
- never commit credentials
- use environment/configuration mechanisms
- minimize permissions
- separate development and production
- treat external input as untrusted

## Reliability
- validate input
- handle timeouts
- handle retries carefully
- make operations observable
- record useful error context

## Cost awareness
Consider invocation volume, execution time, storage, network transfer and external API costs.

## Portfolio evidence
Each cloud project should eventually provide an architecture diagram, deployment instructions, API example, sample response, logging example, failure case, security notes and cost assumptions.
