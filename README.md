# ACT Mastery Pathway

A GitHub-ready personalized ACT Math curriculum prototype: diagnostic → personalized modules → mastery gates → post-assessment → printable growth report.

## Publish this prototype on GitHub Pages
1. Create a GitHub repository.
2. Upload the project files to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. GitHub provides the public URL.

## Current product experience
- Premium student dashboard, course map, personalized study plan, and ACT Math toolkit
- 45-question / 50-minute diagnostic
- 15 tracked subtopics
- Diagnostic skill compaction
- Worked example + strategy lesson + common trap + test-day habit
- 3 strategy-first guided questions per module
- 5-question mastery gate requiring 4/5
- Fresh generated values on module retakes
- Locked 45-question post-assessment
- Printable diagnostic-to-post mastery report
- Local instructor preview/dashboard with strategy-process analytics
- Timed assessment navigator with flags, unanswered review, and autosave
- Retrieval brain breaks at mastery milestones
- Printable completion certificate
- Browser progress export/import

## Important prototype limitation
This GitHub Pages edition stores progress in browser `localStorage`. It has no secure login, central roster, multi-center database, or enforceable licensing. Client-side JavaScript and question data delivered to a browser are inspectable. Use this build as a polished pilot/demo. Before a paid center-wide launch, add authentication, an organization-scoped database, server-side licensing, and a larger QA-reviewed item bank. See `COMMERCIAL_ROADMAP.md`.

## Documentation
- `CURRICULUM_GUIDE.md` — instructional design, scope/sequence, mastery model
- `INSTRUCTOR_GUIDE.md` — tutor implementation protocol
- `COMMERCIAL_ROADMAP.md` — recommended path to a paid tutoring-center license

## Content note
The questions are newly authored ACT-style items informed by the skill types and representations in the supplied reference practice tests. They are not copies of those questions. This product should not be represented as official ACT material or as affiliated with ACT.

## Additional product documents
- `PRODUCT_OVERVIEW.md` — buyer-facing product architecture
- `DEMO_SCRIPT.md` — 7-minute demo flow
- `PILOT_CHECKLIST.md` — launch and content QA protocol
- `LICENSING_DRAFT.md` — draft $1,000/year center-license concept (not legal advice)
