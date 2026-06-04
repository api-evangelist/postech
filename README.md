# Pohang University of Science and Technology (postech)

Pohang University of Science and Technology (POSTECH) is a private research university in Pohang, South Korea, founded in 1986 by POSCO and ranked #87 in the QS World University Rankings 2025. This repository catalogs POSTECH's public developer/API footprint as an [APIs.json](https://apisjson.org) profile. The primary confirmed public, machine-readable API is the POSTECH Library OASIS institutional repository's OAI-PMH 2.0 metadata-harvesting endpoint.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/postech/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=postech-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Institutional Repository, OAI-PMH, DSpace, Library, South Korea, Korea

## APIs

- **OASIS Repository OAI-PMH** — Live OAI-PMH 2.0 metadata-harvesting endpoint for the POSTECH Library OASIS institutional repository (DSpace). Base URL: `https://oasis.postech.ac.kr/oai/request`. Verified responding to Identify, ListMetadataFormats (12 formats), and ListSets (163 sets). Protocol docs: https://www.openarchives.org/OAI/openarchivesprotocol.html

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/postech-plans-pricing.yml](plans/postech-plans-pricing.yml)
- Rate Limits: [rate-limits/postech-rate-limits.yml](rate-limits/postech-rate-limits.yml)
- FinOps: [finops/postech-finops.yml](finops/postech-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.postech.ac.kr/eng/
- LinkedIn: https://kr.linkedin.com/school/pohang-university-of-science-and-technology/
- Portal (PODIUM): https://podium.postech.ac.kr
- Repository (OASIS): https://oasis.postech.ac.kr/
- Review: [review.yml](review.yml)

## Notes

- No general-purpose developer portal or open-data API program was found for POSTECH. Most institutional systems (PODIUM portal, PLMS LMS, admissions, certificate center) are login-gated with no documented public API.
- Only the OASIS OAI-PMH endpoint was verified as a live, public, machine-readable API. The DSpace REST endpoint (`/rest/communities`) returned a JavaScript loading shell rather than a JSON payload, so it is not cataloged as confirmed.
- The `github.com/postech` org is unrelated (a stale 2013 TaskRepo). POSTECH research labs run separate GitHub orgs (e.g. POSTECH-CVLab, postech-imlab), which are lab projects, not institutional APIs.
- No endpoints were fabricated; see [review.yml](review.yml) for probed URLs and their HTTP statuses.

## Maintainers

- Kin Lane — kin@apievangelist.com
