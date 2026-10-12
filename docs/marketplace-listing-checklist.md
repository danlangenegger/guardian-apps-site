\# Atlassian Marketplace Listing Checklist



Reusable checklist for publishing Guardian Apps on the Atlassian Marketplace.



Last updated: October 2026



\---



\# 1. App identity



\## Vendor



Guardian Apps



\## App name



Use a clear product name that communicates the purpose of the app.



Example:



Backlog Guardian for Jira



\## App key



Recommended pattern:



com.guardianapps.<appname>



Example:



com.guardianapps.backlogguardian



\## Forge app



Select the matching Forge app from the Atlassian Developer Console.



Prerequisites:



\- App deployed to production

\- Distribution status set to Sharing

\- Guardian Apps Developer Space published



\---



\# 2. Payment model



Preferred model:



Paid via Atlassian



Use one edition unless there is a strong product reason to introduce multiple editions.



\---



\# 3. App logo



Marketplace requirement:



\- Square image

\- 144 x 144 px minimum or Marketplace-compatible upload

\- PNG or JPG

\- No small text

\- Must remain recognizable at small size



Guardian Apps visual direction:



\- Clean SaaS-style icon

\- Simple shapes

\- Strong contrast

\- Minimal details

\- Avoid Atlassian trademarks or Jira logos

\- Product concept should be understandable without text



\---



\# 4. App tagline



Maximum:



130 characters



Guidelines:



\- Explain the core benefit

\- Avoid vague marketing language

\- Do not end with punctuation

\- Mention Jira only when useful



Example for Backlog Guardian:



Keep Jira backlogs healthy with automated hygiene checks and a simple health score



\---



\# 5. App summary



Maximum:



250 characters



Guidelines:



\- Explain the problem

\- Explain the main functionality

\- Explain the resulting benefit

\- Keep wording concrete



Example for Backlog Guardian:



Backlog Guardian helps Jira teams identify stale, unassigned, overdue and unestimated work before backlog quality deteriorates. Monitor key hygiene issues, review affected tickets and track an easy-to-understand backlog health score.



\---



\# 6. Categories



Atlassian allows up to 2 categories.



Available category examples observed in Marketplace:



\- Administrative tools

\- Content and communication

\- Data and analytics

\- Design and diagramming

\- HR and team building

\- IT support and service

\- Project management

\- Sales and customer relations

\- Security and compliance

\- Software development



\## Backlog Guardian selection



\- Project management

\- Software development



\## Selection guideline for future apps



Choose categories based on the primary customer problem, not the implementation.



Examples:



Backlog / workflow app:

\- Project management

\- Software development



Service desk app:

\- IT support and service

\- Administrative tools or Project management



Analytics app:

\- Data and analytics

\- Project management or Software development



Security app:

\- Security and compliance

\- Administrative tools



\---



\# 7. Keywords



Atlassian allows up to 4 keywords.



Observed keyword options include:



\- Accessibility

\- Agile Methodology

\- Analytics

\- Archiving

\- Artificial Intelligence

\- Asset Management

\- Audit

\- Automation

\- Branch Management

\- Build Management

\- CI/CD

\- CRM

\- Calendar Management

\- Charts/Graphs

\- Chat

\- Checklist

\- Code Collaboration

\- Compliance

\- Custom Fields

\- Custom directory

\- Dashboard Gadgets

\- Data Management

\- Data Visualisation

\- Dependency Management

\- Document Management

\- Documentation

\- Email

\- Encryption

\- Feature Flag

\- Feedback and Surveys

\- Filter

\- Flowchart

\- Forecasting

\- Formatting

\- Gamification

\- Gantt Charts

\- Graphics \& Illustration

\- IT Support

\- Import/Export

\- Incident Management

\- Infographics

\- Integrations

\- Intranet

\- Work item Tracking

\- Knowledge Base

\- Language Packs

\- Learning and Training

\- Localization

\- Migration

\- Mobile

\- Monitoring

\- Notifications

\- Privacy Management

\- Pull requests

\- Release Management

\- Reporting

\- Requirements Management

\- Resource management

\- Risk Management

\- Roadmapping

\- SLA Management

\- Search

\- Templates

\- Testing \& QA

\- Themes \& Styles

\- Time tracking

\- UML Diagramming

\- User permissions

\- Video Conference

\- Whiteboard

\- Wireframing

\- Workflow



\## Backlog Guardian selection



\- Agile Methodology

\- Automation

\- Monitoring

\- Work item Tracking



\## Selection guideline for future apps



Prioritize keywords in this order:



1\. Core customer problem

2\. Primary workflow

3\. Automation or monitoring capability

4\. Product-specific functionality



Avoid selecting broad keywords only because they sound attractive.



\---



\# 8. Release behavior



Preferred for MVP launches:



Publish app immediately after approval



Use delayed publishing only when there is a coordinated launch reason.



\---



\# 9. More details



Recommended structure:



\## Opening value proposition



Explain the problem and benefit in 2 to 3 sentences.



\## Key functionality



List the main capabilities.



\## How it works



Explain the user workflow briefly.



\## Who it is for



Describe the target teams.



\## Privacy and hosting



Mention Forge and Atlassian-hosted infrastructure accurately.



Do not claim certifications or Marketplace badges unless actually granted.



\---



\# 10. Support



Guardian Apps public support URL pattern:



https://danlangenegger.github.io/guardian-apps-site/<app>/support.html



For Backlog Guardian:



https://danlangenegger.github.io/guardian-apps-site/backlog-guardian/support.html



Suggested support response target:



2 business days



Never promise 24/7 support unless this is actually provided.



\---



\# 11. Privacy Policy



URL pattern:



https://danlangenegger.github.io/guardian-apps-site/<app>/privacy.html



Backlog Guardian:



https://danlangenegger.github.io/guardian-apps-site/backlog-guardian/privacy.html



Before publishing a new app, verify that the Privacy Policy matches the actual:



\- Jira data accessed

\- Data stored

\- External services used

\- User identifiers stored

\- Retention behavior

\- Analytics or telemetry

\- Third-party processors



\---



\# 12. Terms of Service



URL pattern:



https://danlangenegger.github.io/guardian-apps-site/<app>/terms.html



Backlog Guardian:



https://danlangenegger.github.io/guardian-apps-site/backlog-guardian/terms.html



Review Terms before materially changing:



\- Pricing

\- Billing

\- Data processing

\- Support obligations

\- Service guarantees

\- External infrastructure



\---



\# 13. Personal data declaration



Do not copy the answer from another app.



Review each app individually.



For Backlog Guardian MVP:



Stores personal data:

No



Basis:



The app is designed not to persist Atlassian user profiles, email addresses or Atlassian account IDs in application storage.



Reassess this whenever storage behavior changes.



\---



\# 14. Marketplace screenshots



Recommended minimum set:



1\. Main product overview

2\. Core result or dashboard

3\. Issue or record drilldown

4\. Configuration screen



Guidelines:



\- Use realistic demo data

\- Avoid confidential information

\- Keep screenshots visually consistent

\- Show the product benefit, not only settings

\- Prefer clean Jira environments



\---



\# 15. Pricing



Before publishing:



\- Confirm current Atlassian revenue share

\- Confirm Marketplace pricing model requirements

\- Confirm free tier and trial behavior

\- Confirm production license behavior



Backlog Guardian launch concept:



\- Free for small Jira sites where appropriate

\- Paid tiers for larger sites

\- 30-day trial where supported

\- One product edition



Exact pricing should be reviewed before submission.



\---



\# 16. Technical release checklist



Before submitting an app:



\- `npm audit` clean where applicable

\- Production frontend build succeeds

\- `forge lint` succeeds

\- Production deployment succeeds

\- Required scopes reviewed

\- Storage behavior reviewed

\- Jira permissions reviewed

\- License behavior tested

\- Manual scan or main workflow tested

\- Scheduled triggers tested

\- Error handling tested

\- Support URL works

\- Privacy URL works

\- Terms URL works

\- Marketplace logo uploaded

\- Screenshots prepared



\---



\# 17. Backlog Guardian current Marketplace configuration



\## Categories



\- Project management

\- Software development



\## Keywords



\- Agile Methodology

\- Automation

\- Monitoring

\- Work item Tracking



\## App key



com.guardianapps.backlogguardian



\## App name



Backlog Guardian for Jira



\## Tagline



Keep Jira backlogs healthy with automated hygiene checks and a simple health score



\## Payment model



Paid via Atlassian



\## Release behavior



Publish app immediately after approval



\## Support



https://danlangenegger.github.io/guardian-apps-site/backlog-guardian/support.html



\## Privacy



https://danlangenegger.github.io/guardian-apps-site/backlog-guardian/privacy.html



\## Terms



https://danlangenegger.github.io/guardian-apps-site/backlog-guardian/terms.html



\---



\# 18. Future app workflow



For every new Guardian Apps product:



1\. Build and test MVP

2\. Deploy to staging

3\. Complete security/privacy review

4\. Deploy to production

5\. Enable Sharing

6\. Add support/privacy/terms pages

7\. Create Marketplace listing

8\. Select categories and keywords

9\. Add logo and screenshots

10\. Configure pricing

11\. Submit for review

12\. Publish

13\. Begin customer acquisition

14\. Measure installs, trials, conversions and support load

15\. Decide whether to invest, maintain or stop

