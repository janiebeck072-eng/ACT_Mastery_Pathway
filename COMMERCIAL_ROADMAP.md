# Commercial Roadmap — From GitHub Prototype to $1,000 Center License

## Positioning
Sell the product as a **center-wide instructional system**, not a folder of worksheets: diagnostic, skill compaction, strategy-first instruction, mastery gates, parallel post-assessment, and actionable tutor analytics.

## A credible $1,000/year tutoring-center package
Suggested packaging to test with buyers (not a claim about market price):
- 1 tutoring-center location
- up to a defined annual active-student allowance (for example 100–150)
- unlimited tutor accounts at that location
- diagnostic + personalized pathways + post-assessment
- center dashboard and printable/exportable reports
- curriculum updates during the license year
- onboarding guide and short staff training

Avoid “unlimited students forever” at $1,000. A clear usage allowance protects margins and gives larger centers an obvious upgrade path.

## Production architecture
**Use GitHub for source control, not as the security boundary.** A public static site exposes client-side questions, answer keys, and application logic to anyone who can load the page. Even a private repository does not make JavaScript delivered to a browser secret.

Recommended production stack:
- GitHub: source/version control
- Front end: GitHub Pages can remain suitable for a public demo/marketing build; for the licensed application, use a deployment platform that supports environment variables and server-side/API functions.
- Authentication/database: Supabase or Firebase
- Data model: organizations → sites → staff → cohorts → students → attempts → item responses → mastery events
- Authorization: organization-scoped role rules so one center cannot see another center's data
- Licensing: organization record with plan, active-student allowance, renewal date, and status
- Analytics: strategy correctness, answer correctness, attempts, time-on-task, module mastery, diagnostic/post growth

## Teacher/tutor dashboard requirements
1. Roster and cohort management
2. Student pathway status
3. Domain/subtopic heat map
4. “Needs intervention” queue
5. Strategy-error vs execution-error analysis
6. Attempts and time-on-task
7. Assignment controls and due dates
8. Diagnostic/post growth
9. PDF/CSV reports
10. Center-level usage/license status

## Commercial content requirements
- Multiple diagnostic/post forms or a sufficiently deep calibrated item bank
- At least 15–25 practice items per subtopic before broad commercial deployment
- Multiple worked examples per subtopic
- Visual question renderer for tables, coordinate grids, triangles, circles, graphs, and diagrams
- Difficulty bands and item metadata
- Accessibility: keyboard navigation, contrast, alt text/accessible SVG labels, responsive layouts
- Item versioning so edits do not corrupt historical analytics

## Buyer-facing proof points to build
- Minutes of instruction saved through skill compaction
- Module completion rate
- Diagnostic-to-post raw growth
- Percentage of students mastering each subtopic
- Tutor intervention reports
- Pilot testimonials only after real use and permission

## Pilot plan
Run a small pilot before charging full commercial price. Collect usability feedback, item-error reports, completion data, and tutor workflow observations. Fix friction, then pilot with a second independent center. Use those results to decide the final annual price, student allowance, and support promise.

## Brand/IP note
Use original questions and original diagrams. Do not market the product as official or affiliated with ACT. Have commercial terms, privacy language, and any use of ACT trademarks reviewed before launch.
