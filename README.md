# PCC Student Life — Expanded Orientation Simulation

**Unofficial educational prototype, not an approved PCC orientation requirement.**

## What is included
- Eight modules and 36 branching-feedback decision scenarios
- Explanations and practical next steps referencing the PCC 2026–2027 Student Handbook
- Browser-local progress, optional export/import between devices
- Personalized print-to-PDF completion certificate after all scenarios and acknowledgment
- Responsive keyboard-friendly controls and semantic labels

## Deploy to GitHub Pages
1. Create a new repository (or open an existing one).
2. Upload `index.html`, `style.css`, `content.js`, and `app.js` to the repository **root**.
3. Commit changes. In **Settings → Pages**, choose **Deploy from a branch**, main, root.
4. Open the published Pages URL.

Do not upload the containing folder alone unless Pages is configured to serve from that folder. All four files must be in the same published directory.

## Important limitations
- GitHub Pages is static hosting. It does **not** authenticate students, transmit completion records, or securely enforce a required orientation.
- The certificate is generated locally and can be modified or reproduced; it is **not verified evidence** of institutional completion.
- Student names and answers are saved locally in the browser. Avoid using shared public computers for personal information.
- Progress export files include the entered name and answers; handle them privately.
- For an institutionally required program, integrate with an approved LMS (such as D2L/Brightspace), verify accessibility and policy accuracy, and use authenticated completion tracking.
- This learning adaptation is based on the supplied PCC 2026–2027 Student Handbook. It paraphrases policy and may omit exceptions. The official current handbook, relevant procedures, and course syllabi control. The AI scenario is guidance to check course permissions, not a claimed universal PCC AI policy.
- The prototype intentionally allows retry and does not impose an arbitrary passing score. All scenarios must be viewed and answered to unlock the local certificate.
- Resource contact information and hyperlinks should be reviewed by PCC before institutional launch.

## Editing
Scenario text and answer indices live in `content.js`, generated from a structured source. The `correct` index is zero-based. Keep the handbook citation pages accurate when revising content.
