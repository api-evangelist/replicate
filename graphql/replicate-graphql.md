# Replicate GraphQL

## Description

Replicate does not currently expose a public GraphQL endpoint. The platform's primary API is a REST HTTP API available at `https://api.replicate.com/v1`. This GraphQL schema is a conceptual representation derived from the types, relationships, and operations described in Replicate's official REST API and HTTP reference documentation.

## Endpoint

No public GraphQL endpoint is available. Introspection against `https://api.replicate.com/graphql` returns no response.

## Documentation

- REST API Reference: https://replicate.com/docs/reference/http
- API Documentation: https://replicate.com/docs
- Client Libraries: https://replicate.com/docs/reference/client-libraries

## Note

This schema is **conceptual**. It models the domain entities, enumerations, and query/mutation patterns that would be natural in a GraphQL layer over Replicate's REST API. Types are derived from:

- The Replicate OpenAPI specification (`openapi/replicate-openapi.yml`)
- Replicate's public HTTP API reference at https://replicate.com/docs/reference/http
- The Cog model framework documentation
- Replicate's deployment, training, prediction, and webhook APIs

The schema covers 60+ types including: Model, ModelVersion, Prediction, PredictionInput, PredictionOutput, PredictionStatus, PredictionLog, PredictionMetrics, Training, TrainingVersion, Deployment, DeploymentScaling, Hardware, Collection, FileObject, Webhook, WebhookEvent, Account, Token, SchemaProperty, CogModel, CogPredictor, CogTrainer, OpenAPISpec, Input, Output, BenchmarkRun, BenchmarkResult, and supporting types.
