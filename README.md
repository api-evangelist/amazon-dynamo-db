# Amazon DynamoDB (amazon-dynamo-db)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon DynamoDB is a fully managed NoSQL key-value and document database service from Amazon Web Services that delivers single-digit millisecond performance at any scale with built-in security, continuous backups, automated multi-region replication, in-memory caching, and data export capabilities. DynamoDB exposes a low-level HTTPS JSON API used by the AWS SDKs and CLI to perform table management, item CRUD, query, scan, transaction, and streams operations, all authenticated with AWS Signature Version 4 (SigV4).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amazon-dynamo-db/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-dynamo-db/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- NoSQL
- Database
- Key-Value Store
- Document Database
- Serverless
- AWS
- Managed Database

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Amazon DynamoDB API

Low-level HTTPS JSON API for Amazon DynamoDB that supports table management, item-level CRUD, queries, scans, transactions, global tables, streams, and backup and restore operations. Requests are POSTed with the X-Amz-Target header naming the operation and are authenticated using AWS Signature Version 4 (SigV4).

- **Human URL:** [https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/Welcome.html)
- **Base URL:** `https://dynamodb.us-east-1.amazonaws.com`

#### Tags

- NoSQL
- Database
- Key-Value Store
- Document Database
- AWS

#### Properties

- [Documentation](https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/Welcome.html)
- [Developer  Guide](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/)
- [Authentication](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_sigv.html)
- [Endpoints](https://docs.aws.amazon.com/general/latest/gr/ddb.html)
- [Postman Collection](collections/amazon-dynamo-db.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-dynamo-db.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://aws.amazon.com/dynamodb/)
- [Documentation](https://docs.aws.amazon.com/dynamodb/)
- [Pricing](https://aws.amazon.com/dynamodb/pricing/)
- [Sign Up](https://portal.aws.amazon.com/billing/signup)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
