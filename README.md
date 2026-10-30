# Mandiant

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Mandiant, now part of Google Cloud, is a threat intelligence and cyber defense company whose Mandiant Advantage platform exposes several authenticated REST APIs documented at docs.mandiant.com. The Threat Intelligence (MATI) API v3 serves indicators, finished intelligence reports, threat actors, malware families, vulnerabilities and campaigns; the Digital Threat Monitoring API surfaces exposed credentials and brand/deep-and-dark-web threats; the Attack Surface Management API inventories an organization's external assets; and the Security Validation (MSV) API drives automated testing of security controls. These APIs authenticate with an API key and secret that is exchanged for a short-lived bearer access token. Mandiant's frontline threat data now also powers Google Threat Intelligence alongside VirusTotal.

**Areas:** Company · Security · Threat Intelligence · Cybersecurity · Incident Response · Attack Surface Management · Vulnerability Intelligence · Malware · Google Cloud

## Mandiant on APIs.io

Everything profiled for Mandiant is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/mandiant/](https://apis.io/providers/mandiant/)** — or go straight to one of the APIs or properties below.

### APIs (61)

- [Mandiant Threat Intelligence API v3](https://apis.io/apis/mandiant/mandiant-threat-intelligence-api-v3/) — The Mandiant Advantage Threat Intelligence (MATI) API v3 provides programmatic access to Mandiant's threat intelligence, including indicators of compromise,…
- [Mandiant Action user profiles API](https://apis.io/apis/mandiant/mandiant-action-user-profiles-api/) — Action User Profiles allow running certain types of actions as other users. For example, to run a Host CLI action as a non-System or non-root user, you…
- [Mandiant Actions API](https://apis.io/apis/mandiant/mandiant-actions-api/) — Actions are the smallest units MSV uses and simulate suspicious or malicious network traffic. They can be combined to form Sequences and Evaluations.
- [Mandiant Actors API](https://apis.io/apis/mandiant/mandiant-actors-api/) — The Actors API from Mandiant — 5 operation(s) for actors.
- [Mandiant Alert Analysis API](https://apis.io/apis/mandiant/mandiant-alert-analysis-api/) — The Alert Analysis API from Mandiant — 4 operation(s) for alert analysis.
- [Mandiant Alert Audit API](https://apis.io/apis/mandiant/mandiant-alert-audit-api/) — The Alert Audit API from Mandiant — 2 operation(s) for alert audit.
- [Mandiant Alerts API](https://apis.io/apis/mandiant/mandiant-alerts-api/) — The Alerts API from Mandiant — 5 operation(s) for alerts.
- [Mandiant Analyze API](https://apis.io/apis/mandiant/mandiant-analyze-api/) — The Analyze API from Mandiant — 1 operation(s) for analyze.
- [Mandiant Audit Logs API](https://apis.io/apis/mandiant/mandiant-audit-logs-api/) — The Validation Platform Director has a consolidated audit log that tracks Validation Platform activity. As a general overview, the type of data in the Audit…
- [Mandiant Bulk Jobs API](https://apis.io/apis/mandiant/mandiant-bulk-jobs-api/) — Bulk jobs can be created from a single Action with a list of source and destination tags.
- [Mandiant Cloud Profiles API](https://apis.io/apis/mandiant/mandiant-cloud-profiles-api/) — Cloud profiles provide a secure way to use credentials when running cloud actions. They are made available in your scripts as environment variables. Once…
- [Mandiant Collection Runs API](https://apis.io/apis/mandiant/mandiant-collection-runs-api/) — The Collection Runs API from Mandiant — 1 operation(s) for collection runs.
- [Mandiant Collections API](https://apis.io/apis/mandiant/mandiant-collections-api/) — Collections live under a project and are another foundational unit of organization in the ASM platform. They define the process of collecting entities,…
- [Mandiant DNS Servers API](https://apis.io/apis/mandiant/mandiant-dns-servers-api/) — DNS Servers provide addresses for actors to use as DNS servers in DNS query actions. Individual DNS query actions can specify one of the available DNS servers.
- [Mandiant Docs API](https://apis.io/apis/mandiant/mandiant-docs-api/) — The Docs API from Mandiant — 4 operation(s) for docs.
- [Mandiant Email Profiles API](https://apis.io/apis/mandiant/mandiant-email-profiles-api/) — Email Profiles provide the valid email addresses and email servers that are used to send files for email file transfer actions.
- [Mandiant Email rules API](https://apis.io/apis/mandiant/mandiant-email-rules-api/) — Rules to use when determining the results of Email Actions
- [Mandiant Email Settings API](https://apis.io/apis/mandiant/mandiant-email-settings-api/) — The Email Settings API from Mandiant — 3 operation(s) for email settings.
- [Mandiant Entities API](https://apis.io/apis/mandiant/mandiant-entities-api/) — The Entities API from Mandiant — 3 operation(s) for entities.
- [Mandiant Event Filter Rules API](https://apis.io/apis/mandiant/mandiant-event-filter-rules-api/) — The suppressed event filter rule API endpoints interact with the rules governing an event matching a Job Action. An suppressing or dropping EventFilterRule…
- [Mandiant Event Suppression API](https://apis.io/apis/mandiant/mandiant-event-suppression-api/) — The suppressed event API endpoints provide accessors to suppress and drop events.
- [Mandiant File Library API](https://apis.io/apis/mandiant/mandiant-file-library-api/) — File Library objects that can be attached to Actions.
- [Mandiant Integration API Tokens API](https://apis.io/apis/mandiant/mandiant-integration-api-tokens-api/) — Tokens to use when authenticating with the Integrations API. When being used, the token must be in the Authorization header as a bearer token like…
- [Mandiant Integration Collections API](https://apis.io/apis/mandiant/mandiant-integration-collections-api/) — Configure Collections with integrations for Cloud credential associations.
- [Mandiant Integration Events API](https://apis.io/apis/mandiant/mandiant-integration-events-api/) — Events that came from an integration configured on the Director. This does not include events that come from local logs for Host CLI Actions.
- [Mandiant Integrations API](https://apis.io/apis/mandiant/mandiant-integrations-api/) — Add your integration(s) here. Once added you can associate them to a collection within the Integrations Collections section.
- [Mandiant Issues API](https://apis.io/apis/mandiant/mandiant-issues-api/) — The Issues API from Mandiant — 3 operation(s) for issues.
- [Mandiant Job Actions API](https://apis.io/apis/mandiant/mandiant-job-actions-api/) — The result of running an action as part of a simulation. Belongs to a Job
- [Mandiant Job API](https://apis.io/apis/mandiant/mandiant-job-api/) — The Job API from Mandiant — 1 operation(s) for job.
- [Mandiant Jobs API](https://apis.io/apis/mandiant/mandiant-jobs-api/) — Jobs are the results of Actions, Evaluations, or Sequences that have been run. They contain JobSteps and JobActions
- [Mandiant Library API](https://apis.io/apis/mandiant/mandiant-library-api/) — The Library API from Mandiant — 12 operation(s) for library.
- [Mandiant Mitre ATT&CK Dashboard API](https://apis.io/apis/mandiant/mandiant-mitre-att-ck-dashboard-api/) — ActionProfiles are statistical actions based on a metatag.
- [Mandiant Monitor Definitions API](https://apis.io/apis/mandiant/mandiant-monitor-definitions-api/) — Sequences or Evaluations that run periodically and generate notifications depending on result
- [Mandiant Monitor groups API](https://apis.io/apis/mandiant/mandiant-monitor-groups-api/) — Groups to contain multiple Monitor Definitions
- [Mandiant Monitors API](https://apis.io/apis/mandiant/mandiant-monitors-api/) — The Monitors API from Mandiant — 7 operation(s) for monitors.
- [Mandiant MSI API](https://apis.io/apis/mandiant/mandiant-msi-api/) — The MSI API from Mandiant — 7 operation(s) for msi.
- [Mandiant Notes API](https://apis.io/apis/mandiant/mandiant-notes-api/) — The Notes API from Mandiant — 2 operation(s) for notes.
- [Mandiant Notification formats API](https://apis.io/apis/mandiant/mandiant-notification-formats-api/) — Monitors generate notifications of two different formats: email and syslog. Notification formats let you customize the messages sent when a monitor creates…
- [Mandiant Notification profiles API](https://apis.io/apis/mandiant/mandiant-notification-profiles-api/) — Notification profiles allow you to configure which monitors produce notifications and under what conditions the notification is sent.
- [Mandiant NTP Servers API](https://apis.io/apis/mandiant/mandiant-ntp-servers-api/) — NTP Servers allow you to provide server addresses for actors to use to synchronize their time
- [Mandiant Organizations API](https://apis.io/apis/mandiant/mandiant-organizations-api/) — Organizations are the top-level resource that all other resources reside in
- [Mandiant Projects API](https://apis.io/apis/mandiant/mandiant-projects-api/) — Projects are the most foundational unit of organization in the ASM platform. Collections exist within one and only one project.
- [Mandiant Proxy Rules API](https://apis.io/apis/mandiant/mandiant-proxy-rules-api/) — Proxy Rules specify proxies to use for MSV traffic.
- [Mandiant Report Builder API](https://apis.io/apis/mandiant/mandiant-report-builder-api/) — A collection of API endpoints to help automate report creation
- [Mandiant Reports API](https://apis.io/apis/mandiant/mandiant-reports-api/) — Reports are the finished product of system interactions. Behaviors are the possibly-nested umbrella for job actions. Zones are the pseudological…
- [Mandiant Search API](https://apis.io/apis/mandiant/mandiant-search-api/) — The Search API from Mandiant — 1 operation(s) for search.
- [Mandiant Security technologies API](https://apis.io/apis/mandiant/mandiant-security-technologies-api/) — The Security technologies API from Mandiant — 4 operation(s) for security technologies.
- [Mandiant Security zone attributes API](https://apis.io/apis/mandiant/mandiant-security-zone-attributes-api/) — Security Zone attributes are descriptors added to Security Zones. Attributes determine whether a zone's location is internal or external and influence…
- [Mandiant Security zones API](https://apis.io/apis/mandiant/mandiant-security-zones-api/) — Security Zones are regions within the network that contain actors and can be considered as being Internal or External. Each actor must belong to exactly one…
- [Mandiant Seeds API](https://apis.io/apis/mandiant/mandiant-seeds-api/) — deletes a user entity / seed
- [Mandiant Sequences and Evaluations API](https://apis.io/apis/mandiant/mandiant-sequences-and-evaluations-api/) — Sequences and evaluations can have one or more steps, each containing one or more actions. Each step of a sequence or evaluation can be run between…
- [Mandiant Settings API](https://apis.io/apis/mandiant/mandiant-settings-api/) — The Settings are used for Director-specific alterations to your organizations installation. <h2>Handling Content Backups</h2> Creating and using a data…
- [Mandiant Tags API](https://apis.io/apis/mandiant/mandiant-tags-api/) — The Tags API from Mandiant — 2 operation(s) for tags.
- [Mandiant Technologies API](https://apis.io/apis/mandiant/mandiant-technologies-api/) — The Technologies API from Mandiant — 1 operation(s) for technologies.
- [Mandiant Templates API](https://apis.io/apis/mandiant/mandiant-templates-api/) — The Templates API from Mandiant — 1 operation(s) for templates.
- [Mandiant Time Series API](https://apis.io/apis/mandiant/mandiant-time-series-api/) — The Time Series API from Mandiant — 4 operation(s) for time series.
- [Mandiant Topology API](https://apis.io/apis/mandiant/mandiant-topology-api/) — The topology API endpoints provide information about Actors, Security Zones, and the connections between them.
- [Mandiant User Groups API](https://apis.io/apis/mandiant/mandiant-user-groups-api/) — User Groups are collections of Users with similar privileges and that all belong to the same Organization.
- [Mandiant Users API](https://apis.io/apis/mandiant/mandiant-users-api/) — Users are individuals belonging to an Organization. Each user belongs to a UserGroup which determines their privileges.
- [Mandiant Verified Domains API](https://apis.io/apis/mandiant/mandiant-verified-domains-api/) — The Verified Domains API from Mandiant — 5 operation(s) for verified domains.
- [Mandiant Vocab API](https://apis.io/apis/mandiant/mandiant-vocab-api/) — The Vocab API from Mandiant — 1 operation(s) for vocab.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Mandiant Agentic Access](https://apis.io/agentic-access/mandiant/mandiant-agentic-access/)

#### JSON Schema (12)

The data models the API reads and writes.

- [Alert](https://apis.io/schemas/mandiant/mandiant-alert/)
- [create_bulk_job](https://apis.io/schemas/mandiant/mandiant-create-bulk-job/)
- [Raw Source Document](https://apis.io/schemas/mandiant/mandiant-doc/)
- [Document Search Response](https://apis.io/schemas/mandiant/mandiant-doc-search-response/)
- [Email Setting](https://apis.io/schemas/mandiant/mandiant-email-setting/)
- [file_library_object](https://apis.io/schemas/mandiant/mandiant-file-library-object/)
- [integration_type](https://apis.io/schemas/mandiant/mandiant-integration-type/)
- [Monitor](https://apis.io/schemas/mandiant/mandiant-monitor/)
- [msi_integration](https://apis.io/schemas/mandiant/mandiant-msi-integration/)
- [run_job](https://apis.io/schemas/mandiant/mandiant-run-job/)
- [security_zone](https://apis.io/schemas/mandiant/mandiant-security-zone/)
- [Verifeid Domain](https://apis.io/schemas/mandiant/mandiant-verified-domain/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Mandiant Context](https://apis.io/jsonld/mandiant/mandiant-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Mandiant API Rules](https://apis.io/rules/mandiant/mandiant-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Mandiant Authentication](https://apis.io/security/mandiant/mandiant-authentication/)
- [Mandiant Domain Security](https://apis.io/security/mandiant/mandiant-domain-security/)

#### Rate limits (1)

Published request limits.

- [Mandiant Rate Limits](https://apis.io/rate-limits/mandiant/mandiant-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://mandiant.com)
- [Documentation](https://docs.mandiant.com)
- [Getting started](https://docs.mandiant.com/home/eod-getting-started)
- [API reference](https://docs.mandiant.com/home/mati-threat-intelligence-api-v3)
- [Blog](https://cloud.google.com/blog/topics/threat-intelligence)
- [GitHub](https://github.com/mandiant)

## API Evangelist rating

**Kin Score 46.6** — developing · rubric 0.24.0 · scored 2026-10-20

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 52.5 |
| Contract governance | 79.1 |
| Operational transparency | 31.1 |
| Developer ergonomics | 52.4 |
| Access clarity | 6.6 |

**Agent readiness 38.4** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/mandiant/](https://apis.io/providers/mandiant/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Mandiant: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/mandiant/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
