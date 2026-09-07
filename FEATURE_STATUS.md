# Feature status — Government & civic administration

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 320 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 2 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 3 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 3 | 0 | Native records/view |
| Activity & audit trail | audit | 5 | 0 | Native records/view |
| Provider connections | integration | 2 | 0 | Provider request records only |
| Contract clause library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fiscal year rate structure | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Direct cost ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fringe pool calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overhead pool calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| G&A pool calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Allocation base validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unallowable cost exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provisional billing reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Final rate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Funding ceiling control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Completion invoice preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Government negotiation support | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash recovery tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract rate analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jury Term | records | 1 | 0 | Native records/view |
| Juror Record | records | 1 | 0 | Native records/view |
| Juror Questionnaire | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summons Batch | records | 1 | 0 | Native records/view |
| Juror Summons | records | 1 | 0 | Native records/view |
| Service Request | records | 1 | 0 | Native records/view |
| Clerk Decision | records | 1 | 0 | Native records/view |
| Juror Attendance | records | 1 | 0 | Native records/view |
| Juror Payment | records | 1 | 0 | Native records/view |
| Operational Task | records | 2 | 0 | Native records/view |
| Rule Version | records | 2 | 0 | Native records/view |
| Document Requirement | records | 2 | 0 | Native records/view |
| Questionnaire completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deferral request summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accommodation request organization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service instruction draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attendance discrepancy review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment explanation draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Compensation Case | records | 1 | 0 | Native records/view |
| Expense Claim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer Offset | records | 1 | 0 | Native records/view |
| Case Document | records | 1 | 0 | Native records/view |
| Eligibility Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expense Decision | records | 1 | 0 | Native records/view |
| Award Decision | records | 1 | 0 | Native records/view |
| Case Payment | records | 1 | 0 | Native records/view |
| Compensation Appeal | records | 1 | 0 | Native records/view |
| Expense document extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Offset reconciliation brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Application completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reviewer decision preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Award explanation draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appeal evidence organization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meetings | records | 1 | 0 | Native records/view |
| Announcements | records | 1 | 0 | Native records/view |
| Departments | records | 1 | 0 | Native records/view |
| Services | records | 1 | 0 | Native records/view |
| FAQs | records | 1 | 0 | Native records/view |
| Permits | records | 1 | 0 | Native records/view |
| Ordinances | records | 1 | 0 | Native records/view |
| Chatbot | records | 1 | 0 | Native records/view |
| Service finder | records | 1 | 0 | Native records/view |
| Complaint classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appointment helper | records | 1 | 0 | Native records/view |
| Permit guide | records | 1 | 0 | Native records/view |
| Resource navigator | records | 1 | 0 | Native records/view |
| Multi language | records | 1 | 0 | Native records/view |
| Accessibility | records | 2 | 0 | Native records/view |
| Feedback | records | 2 | 0 | Native records/view |
| Admin analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exports | records | 1 | 0 | Native records/view |
| Permit eligibility | records | 1 | 0 | Native records/view |
| Categorize feedback | records | 1 | 0 | Native records/view |
| Service sla escalation | records | 1 | 0 | Native records/view |
| Ballot Verification | records | 1 | 0 | Native records/view |
| Redistricting | records | 1 | 0 | Native records/view |
| Voter Registration | records | 1 | 0 | Native records/view |
| Campaign Finance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Ballot Integrity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Voter Audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Gerrymandering | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ballot Cure Queue | records | 1 | 0 | Native records/view |
| Precincts | records | 1 | 0 | Native records/view |
| Poll Workers | records | 1 | 0 | Native records/view |
| Equipment | records | 1 | 0 | Native records/view |
| Ballots | records | 1 | 0 | Native records/view |
| Chain of Custody | records | 1 | 0 | Native records/view |
| Training Sessions | records | 1 | 0 | Native records/view |
| Voter Lines | records | 1 | 0 | Native records/view |
| Incident Reports | records | 1 | 0 | Native records/view |
| Election Judges | records | 1 | 0 | Native records/view |
| Recounts | records | 1 | 0 | Native records/view |
| Observers | records | 1 | 0 | Native records/view |
| Supplies | records | 1 | 0 | Native records/view |
| Vehicles | records | 1 | 0 | Native records/view |
| Ballot Drop Boxes | records | 1 | 0 | Native records/view |
| Accessibility Audits | records | 1 | 0 | Native records/view |
| Language Support | records | 1 | 0 | Native records/view |
| Transmissions | records | 1 | 0 | Native records/view |
| AI · Line Wait Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Equipment Reallocate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Incident Triage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Recount Readiness Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Chain-of-Custody Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Executive Brief | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI · Poll-Worker Schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Language Support Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Accessibility Gap Analyze | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Observer Coordination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Supply Resupply Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Transmission Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Ballot Routing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Training Gap Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Voter Communication Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Post-Election Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training qa copilot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident report draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disinformation quiz generate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rules translate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Approvals | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Webhooks | integration | 2 | 0 | Provider request records only |
| Poll worker break coverage | records | 1 | 0 | Native records/view |
| Wait Time Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crowd Flow Recommendation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Accessibility Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dining Queue Prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Personal Concierge | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Upsell / Merch | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rides | records | 2 | 0 | Native records/view |
| Shows & Entertainment | records | 1 | 0 | Native records/view |
| Dining | records | 1 | 0 | Native records/view |
| Attractions | records | 2 | 0 | Native records/view |
| Gift Shops | records | 2 | 0 | Native records/view |
| Facilities | records | 2 | 0 | Native records/view |
| Park Zones | records | 2 | 0 | Native records/view |
| Tickets & Passes | records | 1 | 0 | Native records/view |
| agentic personal concierge building itin | records | 1 | 0 | Native records/view |
| real time crowd intelligence ingesting w | records | 1 | 0 | Native records/view |
| dynamic pricing ai extending dynamicpric | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| accessibility inclusivity recommender fo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| group planning ai extending groupplannin | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| upsell merchandise recommender learning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| wait time prediction ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| accessibility recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| live wait time data ingestion still | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| mobile push notifications | records | 1 | 0 | Native records/view |
| webhook surface for ticket scan | integration | 1 | 0 | Provider request records only |
| audit log 0 references | records | 1 | 0 | Native records/view |
| file upload for guest photo | records | 1 | 0 | Native records/view |
| Shows | records | 1 | 0 | Native records/view |
| Restaurants | records | 1 | 0 | Native records/view |
| Tickets | records | 1 | 0 | Native records/view |
| Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pass5 tools | records | 1 | 0 | Native records/view |
| Itinerary heat stress guard | records | 1 | 0 | Native records/view |
| Route Planning | records | 1 | 0 | Native records/view |
| Ridership Data | records | 1 | 0 | Native records/view |
| Schedules | records | 1 | 0 | Native records/view |
| Fare Modeling | records | 1 | 0 | Native records/view |
| Fleet Allocation | records | 1 | 0 | Native records/view |
| Budget & Contracts | records | 1 | 0 | Native records/view |
| Incidents | records | 2 | 0 | Native records/view |
| Staff Management | records | 1 | 0 | Native records/view |
| Performance KPIs | records | 1 | 0 | Native records/view |
| Stops & Stations | records | 1 | 0 | Native records/view |
| Maintenance | records | 1 | 0 | Native records/view |
| Energy | records | 1 | 0 | Native records/view |
| Safety | records | 1 | 0 | Native records/view |
| Rider Chat | records | 1 | 0 | Native records/view |
| Demand Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equity Report | records | 1 | 0 | Native records/view |
| GTFS Import | records | 1 | 0 | Native records/view |
| Crowding Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance Triage | records | 1 | 0 | Native records/view |
| dynamic pricing | records | 1 | 0 | Native records/view |
| climateresponsive operations | records | 1 | 0 | Native records/view |
| equity impact simulation | records | 1 | 0 | Native records/view |
| autonomous shuttle planner | records | 1 | 0 | Native records/view |
| intermodal trip planner | records | 1 | 0 | Native records/view |
| behavioral nudging | records | 1 | 0 | Native records/view |
| crowdingprediction peak loads by stoptime | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| maintenancetriage uptimemaximizing priori | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| accessibilitycompliancecheck audit agains | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| staffingshiftoptimization preferenceaware | records | 1 | 0 | Native records/view |
| existing equityreport is shallow compared to | records | 1 | 0 | Native records/view |
| realtime passenger alertsannouncements sm | records | 1 | 0 | Native records/view |
| fare payment mobile ticketing integration | integration | 1 | 0 | Provider request records only |
| operator scheduling conflict detection | records | 1 | 0 | Native records/view |
| servicechange impact modeling route x dis | records | 1 | 0 | Native records/view |
| public webhookopen data api | integration | 1 | 0 | Provider request records only |
| notifications system for staff | records | 1 | 0 | Native records/view |
| audit log of dispatch decisions | records | 1 | 0 | Native records/view |
| Intersections | records | 1 | 0 | Native records/view |
| Signals | records | 1 | 0 | Native records/view |
| Detectors | records | 1 | 0 | Native records/view |
| Signal Plans | records | 1 | 0 | Native records/view |
| Transit Priority | records | 1 | 0 | Native records/view |
| Emergency Preemptions | records | 1 | 0 | Native records/view |
| Pedestrian Phases | records | 1 | 0 | Native records/view |
| Bike Phases | records | 1 | 0 | Native records/view |
| Work Zones | records | 1 | 0 | Native records/view |
| Special Events | records | 1 | 0 | Native records/view |
| Signal Groups | records | 1 | 0 | Native records/view |
| Comms Cabinets | records | 1 | 0 | Native records/view |
| Sensors Health | records | 1 | 0 | Native records/view |
| Video Feeds | records | 1 | 0 | Native records/view |
| Controllers | records | 1 | 0 | Native records/view |
| Performance Metrics | records | 1 | 0 | Native records/view |
| AI · Incident-Aware Retime | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Ped Conflict Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Transit Priority Suggest | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Work Zone Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Special Event Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Corridor Coordination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Intersection Prioritize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Work Order Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Signal Health Prognostic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Equity Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Emission Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Citizen Complaints | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Sensor Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Performance Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vendor Quality Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Congestion forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Signal timing optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency preempt sequence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident response coordinate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equity response time | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equity neighborhoods | records | 1 | 0 | Native records/view |
| Public | records | 1 | 0 | Native records/view |
| Traffic Flow Simulation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Population Density Modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Infrastructure Impact Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Zoning Compliance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Environmental Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Noise Level Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Green Space Planning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Land Use Management | records | 1 | 0 | Native records/view |
| Building Permits | records | 2 | 0 | Native records/view |
| District Zones | records | 2 | 0 | Native records/view |
| Transportation Routes | records | 2 | 0 | Native records/view |
| Public Facilities | records | 2 | 0 | Native records/view |
| Traffic simulations | records | 1 | 0 | Native records/view |
| Population density | records | 1 | 0 | Native records/view |
| Infrastructure impact | records | 1 | 0 | Native records/view |
| Environmental assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Noise analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Green space | records | 1 | 0 | Native records/view |
| Land use | records | 1 | 0 | Native records/view |
| Gis map | records | 1 | 0 | Native records/view |
| Simulator | records | 1 | 0 | Native records/view |
| Compliance engine | records | 1 | 0 | Native records/view |
| Citizen portal | records | 1 | 0 | Native records/view |
| Scenario workbench | records | 1 | 0 | Native records/view |
| Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| zoning scenario optimizer maximizing affordable housing commercial green space | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| infrastructure impact predictor for schools utilities transit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| environmental compliance checker for nepa wetlands endangered species | records | 1 | 0 | Native records/view |
| community benefit analyzer quantifying jobs tax housing impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| historic preservation advisor flagging districts and compatible development | records | 1 | 0 | Native records/view |
| public comment moderation pipeline with sentiment analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| critical only 1 ai endpoint despite scenario compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| conversational planning copilot for citizens or officials | records | 1 | 0 | Native records/view |
| predictive permit approval ml | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real time gis integration arcgis qgis | integration | 1 | 0 | Provider request records only |
| public comment stakeholder feedback system | records | 1 | 0 | Native records/view |
| multi year zoning amendment tracking | records | 1 | 0 | Native records/view |
| density far calculation utility | records | 1 | 0 | Native records/view |
| webhooks notifications | integration | 1 | 0 | Provider request records only |
| public portal citizen self service | records | 1 | 0 | Native records/view |
| Saved Searches | records | 1 | 0 | Native records/view |
| Applications | records | 2 | 0 | Native records/view |
| Decision Center | records | 1 | 0 | Native records/view |
| Missing features | records | 1 | 0 | Native records/view |
| Production readiness | records | 1 | 0 | Native records/view |
| NLP Search | records | 1 | 0 | Native records/view |
| Jobs | records | 1 | 0 | Native records/view |
| API Docs | records | 1 | 0 | Native records/view |
| RFP Workspace | records | 1 | 0 | Native records/view |
| Company Profiles | records | 1 | 0 | Native records/view |
| Proposal Templates | records | 1 | 0 | Native records/view |
| Outcome Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lifecycle Overview | records | 1 | 0 | Native records/view |
| Contract Matters | records | 1 | 0 | Native records/view |
| Clauses & Playbooks | records | 1 | 0 | Native records/view |
| Obligations | records | 1 | 0 | Native records/view |
| Amendments | records | 1 | 0 | Native records/view |
| Renewals & Options | records | 1 | 0 | Native records/view |
| Risk & AI Evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Suite Overview | records | 1 | 0 | Native records/view |
| Acquisition Operations | records | 1 | 0 | Native records/view |
| Negotiation Intelligence | records | 1 | 0 | Native records/view |
| Vendor Risk | records | 1 | 0 | Native records/view |
| Smart-Contract Assurance | records | 1 | 0 | Native records/view |
| Sports Contracts | records | 1 | 0 | Native records/view |
| Governance | records | 1 | 0 | Native records/view |
| Dashboard | records | 1 | 0 | Native records/view |
| Generate | records | 1 | 0 | Native records/view |
| Quick actions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proposal drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bid analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Win probability | records | 1 | 0 | Native records/view |
| Similar contracts | records | 1 | 0 | Native records/view |
| Opportunity predictions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Opportunity alerts | records | 1 | 0 | Native records/view |
| Optimize strategy | records | 1 | 0 | Native records/view |
| Comprehensive analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Batch analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 320 feature pages were visited in the browser; 318 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 125 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

125 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
