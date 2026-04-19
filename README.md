# Abortion Policy API (abortion-policy-api)
The Abortion Policy API provides up-to-date information on US state abortion policies that can be integrated into online abortion resources. The API consolidates abortion laws into one database across four data tables covering gestational limits, insurance coverage, minors restrictions, and waiting periods. Data is accessible by US state name or zip code.

**URL:** [https://www.abortionpolicyapi.com/](https://www.abortionpolicyapi.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Abortion, Policies, Healthcare, Government

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-04-19

## APIs

### Abortion Policy API
The Abortion Policy API consolidates US state abortion laws into one database for third-party developers to use. Data tables include gestational limits, insurance coverage, minors restrictions, and waiting periods. Access requires requesting an API key. Rate limit is 100 calls per 60 seconds.

**Human URL:** [https://www.abortionpolicyapi.com/](https://www.abortionpolicyapi.com/)

#### Tags:

 - Abortion, Policies, Healthcare

#### Properties

- [Documentation](https://www.abortionpolicyapi.com/)
- [Authentication](https://www.abortionpolicyapi.com/request-access)
- [APIReference](https://www.abortionpolicyapi.com/field-references)
- [OpenAPI](openapi/abortion-policy-api-openapi.yml)
- [CodeExamples](https://github.com/alexanian/abortion-policy-api-examples)
- [JSONSchema - Gestational Limits](json-schema/gestational-limits-schema.json)
- [JSONSchema - Insurance Coverage](json-schema/insurance-coverage-schema.json)
- [JSONSchema - Minors Restrictions](json-schema/minors-restrictions-schema.json)
- [JSONSchema - Waiting Periods](json-schema/waiting-periods-schema.json)

## Common Properties

- [GettingStarted](https://www.abortionpolicyapi.com/)
- [Authentication](https://www.abortionpolicyapi.com/request-access)
- [APIReference](https://www.abortionpolicyapi.com/field-references)
- [CaseStudies](https://www.abortionpolicyapi.com/case-studies)
- [Support](https://www.abortionpolicyapi.com/contact)
- [TermsOfService](https://www.abortionpolicyapi.com/terms)
- [PrivacyPolicy](https://www.abortionpolicyapi.com/privacy)

## Features

| Name | Description |
|------|-------------|
| Gestational Limits Data | State-by-state gestational limit policies including exceptions for life, health, fetal anomaly, and rape/incest. |
| Insurance Coverage Data | Comprehensive insurance coverage restrictions covering Medicaid, private insurance, and ACA exchange plans by state. |
| Minors Restrictions Data | Parental consent, notification, and judicial bypass requirements for minors seeking abortion by state. |
| Waiting Periods Data | State mandatory waiting period hours and counseling visit requirements between counseling and abortion care. |
| State and Zip Code Lookup | All policy data accessible by US state name or 5-digit zip code for integration flexibility. |
| Expert-Curated Data | Data collaboratively analyzed by reproductive rights experts from Guttmacher, Planned Parenthood, Power to Decide, CRR, and others. |
| Free Public Good | API provided free without gatekeeping as a public good resource for reproductive health organizations. |

## Use Cases

| Name | Description |
|------|-------------|
| Abortion Finder Applications | Integrate state abortion policy data into patient-facing tools that help people find abortion services. |
| Healthcare Provider Tools | Embed policy data into clinical tools to help providers advise patients on state-specific access restrictions. |
| Journalism and Research | Access structured policy data for data journalism, academic research, and policy analysis. |
| Advocacy and Education | Power public education tools and advocacy platforms with accurate, up-to-date abortion policy information. |
| Chatbot Integration | Provide abortion policy answers in conversational tools like Charley the Chatbot. |
| Legal Aid Resources | Support legal aid organizations with accurate state law data for advising clients on abortion access. |

## Integrations

| Name | Description |
|------|-------------|
| Planned Parenthood | Used by Planned Parenthood for patient-facing abortion policy information. |
| Abortion Finder | Powers policy data in the Abortion Finder patient resource tool. |
| Charley the Chatbot | Integrated into Charley the Chatbot for conversational abortion policy guidance. |
| Ineedana.com | Powers policy data for ineedana.com abortion access resource. |
| Microsoft Power Platform | Available as an independent publisher connector for Power Apps, Power Automate, Logic Apps, and Copilot Studio. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Abortion Policy API](openapi/abortion-policy-api-openapi.yml)

### JSON Schema

- [Gestational Limits](json-schema/gestational-limits-schema.json)
- [Insurance Coverage](json-schema/insurance-coverage-schema.json)
- [Minors Restrictions](json-schema/minors-restrictions-schema.json)
- [Waiting Periods](json-schema/waiting-periods-schema.json)

### JSON Structure

- [Gestational Limits](json-structure/gestational-limits-structure.json)
- [Insurance Coverage](json-structure/insurance-coverage-structure.json)
- [Minors Restrictions](json-structure/minors-restrictions-structure.json)
- [Waiting Periods](json-structure/waiting-periods-structure.json)

### JSON-LD

- [Abortion Policy API Context](json-ld/abortion-policy-api-context.jsonld)

### Examples

- [Gestational Limits Example](examples/gestational-limits-example.json)
- [Insurance Coverage Example](examples/insurance-coverage-example.json)
- [Minors Restrictions Example](examples/minors-restrictions-example.json)
- [Waiting Periods Example](examples/waiting-periods-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Abortion Policy API](capabilities/shared/abortion-policy-api.yaml) — 12 operations for gestational limits, insurance coverage, minors restrictions, and waiting periods

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Abortion Policy Lookup](capabilities/abortion-policy-lookup.yaml) | Abortion Policy API | 12 | Healthcare Provider, Patient Advocate, Legal Aid, Chatbot Developer |

## Vocabulary

- [Abortion Policy API Vocabulary](vocabulary/abortion-policy-api-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 3 actions, 1 workflow, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Abortion Policy API Spectral Rules](rules/abortion-policy-api-spectral-rules.yml) — 30 rules across 12 categories enforcing Abortion Policy API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
