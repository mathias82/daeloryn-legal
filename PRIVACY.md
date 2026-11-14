# Daeloryn AI — Privacy Policy

**Draft for review — not yet effective**  
**Last updated:** 14 November 2026

> **Publication checklist:** Before publishing this policy, replace the contact and retention placeholders, verify the actual deployment architecture and all data recipients, and obtain appropriate legal review. The current Daeloryn GitHub App integration is documented as a *local developer preview*, not a hosted customer service.

## 1. Who is responsible for your data?

Daeloryn AI is developed and operated by **[LEGAL NAME / REGISTERED BUSINESS NAME]** (the “Provider”). For privacy questions and data-protection requests, contact **[WORKING PRIVACY CONTACT EMAIL]**. Business address (where legally required): **[BUSINESS ADDRESS]**.

The Provider's role as controller or processor depends on the service configuration and the applicable agreement. Any hosted business offering must define those roles and any required data-processing agreement before onboarding customers.

## 2. Scope and current service status

This policy is intended for the Daeloryn AI website, GitHub App and related engineering workflows **when they are made available to external users**. At the date above, the documented GitHub App integration is a local developer preview: a locally operated backend can discover authorized repositories, read selected files and pull-request metadata, and—only after explicit approval—send selected source text to a configured GitHub Copilot provider. Hosted multi-customer operation, public webhooks, subscriptions and Marketplace billing are not documented as operational.

Before making a hosted service available, the Provider will update this policy to reflect the actual system and practices.

## 3. Information that may be processed

Depending on the functionality enabled and permissions granted:

- **GitHub account and installation metadata:** identifiers for accounts, organizations, installations and selected repositories, and information needed to verify access.
- **Repository and pull request data:** names, selected file paths, selected commit-pinned source code, pull-request titles and descriptions, where the user has authorized access.
- **Review requests and results:** user-submitted questions, explicitly approved prompts/source excerpts, agent or model selections, generated review findings and test/evaluation evidence.
- **Operational and security data:** minimal error, usage and security records needed to operate and protect a deployed service, if logging is enabled.
- **Support communications:** information voluntarily submitted when contacting support.

Please do not submit secrets, personal information, confidential client data, or source code that you are not authorized to process.

## 4. How data is used

Data may be processed to authenticate and authorize access, present permitted repository information, prepare previews, execute actions expressly approved by the user, display results, respond to support requests, prevent abuse and meet legal obligations.

The local GitHub App review flow requires users to preview and explicitly approve the exact selected source/prompt before Copilot submission. It does not automatically scan entire repositories or automatically publish changes through this adapter.

## 5. AI providers and third parties

When a user explicitly enables an AI-backed workflow, selected inputs may be transmitted to the **configured provider**. The documented GitHub App review workflow uses GitHub Copilot. Separate optional workflows can use OpenAI or other configured model/CLI providers. The specific provider, its processing location, logging and retention rules depend on the actual configuration and its terms.

GitHub processes account, installation, repository and platform data under its own terms and privacy notices. A hosted deployment may also involve an infrastructure provider **[IDENTIFY IF APPLICABLE]**.

**Do not interpret the local provider configuration as a guarantee of zero retention, EU-only processing, or that customer code is never transmitted.** The full list of processors, their roles and relevant international transfer safeguards must be confirmed before commercial launch.

## 6. Storage and retention

For the documented local GitHub App preview, pending approved-review selections are stored in backend memory, expire after 15 minutes, and are lost on server restart. The documented selected-source preview/approval flow does not persist preview source or credentials. Other local workflow features may retain code, prompts and evidence in operator-controlled files or databases.

For any hosted offering, the Provider must publish and follow verified retention rules for logs, account records, repository metadata, review results, backups and deletion requests: **[INSERT VERIFIED RETENTION PERIODS AND DELETION PROCEDURE BEFORE LAUNCH]**.

## 7. Security

Daeloryn documentation describes least-privilege GitHub permissions, installation-scoped access, explicit approval before selected source is submitted to Copilot, and short-lived access tokens held in memory for the local adapter. These controls do not establish that a future hosted service has completed independent security testing. No service can guarantee absolute security.

## 8. Legal bases and rights

Where the GDPR applies, the legal basis for processing will depend on the actual use: performance of a service agreement, legitimate interests in securing and operating the service, compliance with law, or consent where required. Users may have rights of access, correction, deletion, restriction, objection and portability, as well as the right to complain to a supervisory authority. To exercise rights contact **[WORKING PRIVACY CONTACT EMAIL]**.

## 9. International transfers

Data sent to GitHub, AI providers or hosting providers may be processed outside your country or the European Economic Area. Before hosting customers, the Provider will document applicable transfer mechanisms and safeguards for each actual recipient.

## 10. Changes

This policy may be updated when the service changes. The latest effective version will be published at this URL with its effective date. Material changes will be communicated where required by law.

## 11. Contact

Privacy: **[WORKING PRIVACY CONTACT EMAIL]**  
Security: **[WORKING SECURITY CONTACT EMAIL]**