---
name: ofx-create-beneficiary
description: Create a new beneficiary for the connected company after validating the details.
api: openapi/_ae-authored/ofx-openapi-generated.yml
operations:
- post_v1_business_beneficiaries_validate
- post_v1_business_beneficiaries
- get_v1_business_beneficiaries_beneficiaryId
generated: '2026-09-22'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/_ae-authored/ofx-openapi-generated.yml ; every operationId checked against the contract
---

# ofx-create-beneficiary

Create a new beneficiary for the connected company after validating the details.

## Steps

1. 1. `post_v1_business_beneficiaries_validate` – provide beneficiary fields as defined in the schema.
2. 2. `post_v1_business_beneficiaries` – send the validated beneficiary data to create the record.
3. 3. `get_v1_business_beneficiaries_beneficiaryId` – retrieve the newly created beneficiary using its identifier.

## Rules

- (none stated)
