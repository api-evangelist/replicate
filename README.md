# Replicate (replicate)

Replicate lets you run machine learning models in the cloud with a simple API. Thousands of open-source models are available for image generation, language modeling, audio synthesis, video generation, and more. You can run your own custom models at scale or fine-tune existing models. Replicate makes AI accessible to every software engineer — import a model like an npm package, customize it like a GitHub fork.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/replicate/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

- Artificial Intelligence
- Machine Learning
- Image Generation
- Language Models
- Model Deployment

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-05-02

## APIs

### Replicate

Replicate lets you run machine learning models in the cloud with a simple REST API. Access thousands of open-source models for image generation, language modeling, audio synthesis, video generation, upscaling, and more. Create predictions, manage deployments, fine-tune models, and run training jobs via a clean API with webhooks and streaming support.

**Human URL:** [https://replicate.com/](https://replicate.com/)

#### Tags:

- Accounts
- Artificial Intelligence
- Collections
- Deployments
- Hardware
- Machine Learning
- Models
- Predictions
- Training
- Webhooks

#### Properties

- [Documentation](https://replicate.com/docs)
- [OpenAPI Documentation](https://replicate.com/docs/reference/http)
- [OpenAPI](openapi/replicate-openapi.yml)
- [Spectral Ruleset](rules/replicate-rules.yml)
- [Capability: Model Inference](capabilities/model-inference.yaml)
- [Capability: Model Management](capabilities/model-management.yaml)
- [Vocabulary](vocabulary/replicate-vocabulary.yml)

## Common Properties

- [Website](https://replicate.com)
- [Documentation](https://replicate.com/docs)
- [Pricing](https://replicate.com/pricing)
- [Blog](https://replicate.com/blog)
- [ChangeLog](https://replicate.com/changelog)
- [TermsOfService](https://replicate.com/terms)
- [PrivacyPolicy](https://replicate.com/privacy)
- [SignUp](https://replicate.com/signin?next=/docs)
- [Login](https://replicate.com/signin)
- [Playground](https://replicate.com/explore)
- [GitHub Organization](https://github.com/replicate)
- [SDKs](https://replicate.com/docs/reference/client-libraries)
- [Python SDK](https://github.com/replicate/replicate-python)
- [Node.js SDK](https://github.com/replicate/replicate-javascript)
- [Go SDK](https://github.com/replicate/replicate-go)
- [Swift SDK](https://github.com/replicate/replicate-swift)
- [Cog (Model Packaging)](https://github.com/replicate/cog)
- [Status](https://status.replicate.com)

## Artifacts

### OpenAPI Specifications

- [replicate-openapi.yml](openapi/replicate-openapi.yml) — Replicate REST API covering accounts, models, predictions, deployments, trainings, and webhooks (28 operations)

### Spectral Rulesets

- [replicate-rules.yml](rules/replicate-rules.yml) — Spectral rules enforcing Replicate API conventions (dot-notation operationIds, Bearer auth, paginated responses)

### Naftiko Capabilities

#### Shared Definitions

- [shared/replicate.yaml](capabilities/shared/replicate.yaml) — Complete Replicate API consumed definition

#### Workflow Capabilities

- [model-inference.yaml](capabilities/model-inference.yaml) — Create and manage AI predictions, browse collections, check hardware options
- [model-management.yaml](capabilities/model-management.yaml) — Manage models, versions, fine-tuning jobs, and production deployments

### JSON Schemas

- [replicate-prediction-schema.json](json-schema/replicate-prediction-schema.json) — Schema for Replicate Prediction objects
- [replicate-model-schema.json](json-schema/replicate-model-schema.json) — Schema for Replicate Model objects

### JSON Structures

- [replicate-prediction-structure.json](json-structure/replicate-prediction-structure.json) — Field-level documentation for prediction objects

### JSON-LD Contexts

- [replicate-context.jsonld](json-ld/replicate-context.jsonld) — Linked data context mapping Replicate terms to schema.org vocabulary

### Examples

- [replicate-create-prediction-example.json](examples/replicate-create-prediction-example.json) — Create an image generation prediction
- [replicate-list-models-example.json](examples/replicate-list-models-example.json) — List public models with pagination

### Vocabulary

- [replicate-vocabulary.yml](vocabulary/replicate-vocabulary.yml) — Domain vocabulary covering predictions, models, deployments, training, and integration patterns

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
