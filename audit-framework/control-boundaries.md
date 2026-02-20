# Scope of Editing Authority

This audit was conducted using page-level editing access within the CMS. Changes were limited to front-end content updates, including text, images, headings, links, and page metadata where available.

Template-level code, server performance, caching, and infrastructure configuration were outside the scope of this project.

Lighthouse and accessibility findings were categorized based on whether they were:

- Content-level (editable)

- Template/infrastructure-level (requires IT or system admin support)

Performance results are interpreted within this scope.



<!-- # Control Boundaries & Governance Authority

## Project Context

This audit was conducted within the administrative interface of BigTree CMS. Access was limited to page-level content editing and module configuration. No backend, server, template, or infrastructure-level permissions were available.

This document defines the scope of authority and distinguishes between:

- Content-Level Controls (Directly Managed)

- CMS-Level Controls (Platform-Dependent)

- Infrastructure-Level Controls (IT Managed)

- Clear boundary identification ensures accurate attribution of audit findings and performance metrics.

## 1. Content-Level Controls (Direct Authority)

These elements are fully within editorial control and can be modified directly within the CMS interface.

- Accuracy & Governance
- Financial information (education award amounts, stipends)
- Program descriptions
- Dates and deadlines
- Contact information
- Office hours
- Policy text displayed on page
- Accessibility (Content Layer)
- Alt text for images
- Heading hierarchy (H1–H4)
- Link text clarity ("Apply Now" vs "Click Here")
- Removal of empty or broken internal links
- PDF replacement if outdated
- SEO (If Metadata Fields Available)
- Page titles
- Meta descriptions
- Open graph descriptions (if exposed)
- Internal linking structure
- Content Lifecycle
- Archiving outdated pages
- Removing duplicate content
- Updating outdated images
- Refreshing high-traffic content

## 2. CMS-Level Controls (Limited or Indirect Influence)

These elements are controlled by the BigTree CMS template or administrative configuration. Findings in these areas may require coordination with system administrators.

- Template-based heading structure
- Navigation architecture
- Global footer/header layout
- Default schema markup
- Automated metadata behavior
- Page rendering structure
- Global design elements affecting contrast

If audit findings fall within this category, they are documented and escalated rather than directly modified.

## 3. Infrastructure-Level Controls (Outside Scope)

These elements are managed at the hosting or IT infrastructure level and are not modifiable within CMS access.

- Server response time
- Caching configuration
- CDN implementation
- JavaScript bundling/minification
- CSS optimization
- Core performance architecture
- Hosting provider configuration

Lighthouse performance findings attributed to these areas are categorized as infrastructure-dependent.

## 4. Governance Classification Framework

Each audit finding is classified according to:

- Risk Level (High, Medium, Low)
- Control Level (Content, CMS, Infrastructure)
- Action Path (Fix, Escalate, Monitor)

This ensures performance scores are interpreted within the appropriate authority boundary and that corrective action is aligned with governance responsibility.

## 5. Why Control Boundaries Matter

Institutional website performance and compliance scores are multi-layered outputs influenced by content, system architecture, and hosting configuration.

By defining control boundaries:

- Accountability is accurately assigned
- Escalation pathways are clarified
- Governance maturity is demonstrated
- Audit findings are contextualized
- Performance metrics are interpreted responsibly

This structured approach ensures that optimization efforts remain aligned with both operational authority and institutional risk management standards. --!>
