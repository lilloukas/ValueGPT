# Repository agent instructions

## PR visual evidence

This requirement applies repository-wide, alongside existing validation rules; scoped instructions must not waive it.

- For any PR involving frontend or visual changes (including visible copy, layout, styling, assets, and native UI), the minimum is actual **before and after screenshots** of the affected running application. Capture the baseline before editing or run the baseline commit separately. Inspect both versions and exercise the changed scenarios before claiming the work is visually verified or ready for review.
- Label each capture **Before / baseline** or **After / current**, with the commit, device or browser, viewport/window dimensions, and scenario/state. Match the baseline and current conditions so reviewers can compare the change directly.
- Embed or durably link the screenshots in the **PR body itself**, using GitHub attachments or persistent hosting accessible to the intended reviewers. Check the published evidence renders/opens with the appropriate access. Local paths, chat-only evidence, inaccessible private raw URLs, and expiring links are insufficient.
- For motion or interaction changes, ideally upload a matched **side-by-side before/after video or GIF** when practical, showing the same sequence and timing. Recordings supplement the minimum screenshots; they do not replace them.
- Use honest runtime evidence, not generated mockups presented as tested behavior. Use safe fixtures and exclude secrets and private user data from public artifacts. If runtime access or any required capture is missing, keep the PR draft and explicitly disclose the missing evidence and blocker in its body and handoff; do not claim readiness or visual verification, and never fabricate evidence.
