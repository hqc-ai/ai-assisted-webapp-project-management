# 5SOffice Webapp — Three-Phase Product Roadmap

## Purpose

This roadmap shows how the 5SOffice Webapp can evolve from a structured static website into an operational platform and, later, an AI-enabled service system.

The roadmap is intentionally staged. Each phase must create a stable foundation for the next.

---

# Phase 1 — Structured Web Platform

## Objective

Create a reliable, fast, maintainable web platform that supports service discovery, location discovery, content publishing, and conversion.

## Main capabilities

- Homepage and reusable UI components
- Service pages
- City pages
- Building pages
- District and location pages
- News pages
- Legal knowledge pages
- Structured content collections
- Dynamic route generation
- Responsive design
- SEO, AEO, and GEO foundations
- Canonical URLs
- Sitemap
- Breadcrumbs
- Structured data
- Internal linking
- GitHub source control
- Cloudflare Pages deployment

## Business value

- Faster website performance
- Lower infrastructure cost
- Better search visibility
- Consistent location and service data
- Easier content expansion
- More reliable deployment
- Improved user access across devices

## Phase 1 exit criteria

- Stable build
- No critical route collision
- No broken internal links
- Valid sitemap
- Controlled content structure
- Preview deployment
- Production deployment readiness

---

# Phase 2 — Content Operations and Business Integration

## Objective

Turn the website into an operational platform that supports controlled publishing, lead handling, analytics, and business workflows.

## Planned capabilities

### Content management

- Lightweight CMS or controlled editorial interface
- Draft, review, approved, and published states
- Content owner
- Review date
- Scheduled publication
- Media library
- Content audit trail
- Bulk content validation

### Lead management

- Structured enquiry forms
- Service and location context captured with each enquiry
- Lead routing
- CRM integration
- Email or messaging notifications
- Lead status tracking
- Source and campaign attribution

### Analytics

- GA4 or equivalent analytics
- GTM event tracking
- CTA tracking
- Zalo, phone, WhatsApp, and form events
- Content performance dashboard
- Location and service conversion reporting
- Search and referral reporting
- AI referral monitoring where technically available

### Operations

- Automated content checks
- Broken-link monitoring
- Sitemap validation
- Deployment notifications
- Scheduled reports
- Role-based permissions
- Backup and rollback procedures

## Business value

- Reduced manual content handling
- Better lead traceability
- Faster response to enquiries
- Measurable marketing performance
- Clear ownership and approval
- Improved content governance

## Phase 2 entry conditions

- Phase 1 routes and data model are stable
- Content categories are controlled
- Production deployment is operating reliably
- Business owners agree on lead and publishing workflows

---

# Phase 3 — AI-Enabled Service and Knowledge Platform

## Objective

Use AI to improve service discovery, knowledge access, customer qualification, and business decision support.

## Planned capabilities

### AI service finder

Users can describe their needs in natural language, for example:

```text
I need a virtual office in Hanoi near Cau Giay for company registration.
```

The system can recommend:

- Suitable service
- City
- Building
- Area
- Available options
- Relevant legal knowledge
- Contact action

### AI knowledge assistant

A controlled assistant can answer questions based on approved content:

- Service definitions
- Location information
- Office-use conditions
- Registration-address guidance
- Legal knowledge articles
- Frequently asked questions

The assistant should use approved source content and provide traceable references.

### Retrieval and search

- Semantic search
- Natural-language search
- Retrieval-augmented generation
- Related-content recommendations
- Service and location matching
- Duplicate-content detection
- Knowledge gap identification

### Sales and CRM support

- Enquiry qualification
- Lead summarisation
- Recommended follow-up
- Suggested service package
- Conversation context transfer
- CRM record enrichment

### AI-assisted content operations

- Draft assistance
- Metadata suggestions
- Internal-link suggestions
- Content freshness alerts
- Inconsistency detection
- Data validation
- Human approval workflow

### AI governance

- Approved data sources
- Human review
- Prompt and output controls
- Logging and traceability
- Access control
- Privacy protection
- Accuracy monitoring
- ISO/IEC 42001-aligned governance direction

## Business value

- Faster customer guidance
- Improved service matching
- Better use of existing knowledge
- Reduced repetitive support workload
- More consistent information
- Data-driven sales support
- Scalable content operations

## Phase 3 entry conditions

- Stable structured content
- Sufficient approved knowledge base
- Reliable analytics data
- CRM or lead workflow available
- Clear AI governance and risk controls
- Human escalation process defined

---

# Maturity model

| Level | Product state | Main value |
|---|---|---|
| 1 | Structured website | Visibility and conversion |
| 2 | Operational platform | Workflow and measurement |
| 3 | AI-enabled platform | Intelligence and scale |

---

# Governance principle

AI must not be added only for appearance.

Each AI capability should have:

- A defined business problem
- Approved data
- Measurable outcome
- Human oversight
- Risk controls
- Clear fallback process
