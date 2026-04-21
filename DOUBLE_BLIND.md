# Double-Blind Review Notice

This repository hosts the **project page** for a paper currently under
**IROS 2026 double-blind review**. All content in this repository —
including the project page, commit history, issues, and README — must
preserve anonymity until the review cycle is complete.

## Do NOT commit / publish

- **Author names** (given name, family name, nickname, or handle that
  could be traced back to an author).
- **Institutional affiliation** (university, lab, company, funding
  agency, grant number).
- **Hardware identifiers** that uniquely identify a group's platform
  (internal model names, proprietary serials, unpublished product
  codenames). Use generic descriptions such as
  *"16-DoF multi-sensory robot hand"*.
- **Personal contact info** (email addresses, phone numbers, personal
  websites, social handles).
- **Acknowledgements** to specific individuals or groups.
- **Links** to personal/lab repositories that reveal identity
  (use only the anonymous preprint / anonymous code portal in the
  paper).
- **Commit authorship that leaks identity** — see the note below.

## Git authorship hygiene

This project page should be committed by an anonymized contributor.
If you need to change the local author for commits in this repository,
use:

```bash
git -C <repo> config user.name  "project-robotics"
git -C <repo> config user.email "<anonymous contact>"
```

Do **not** enable global `user.name` / `user.email` with real values
while working in this repository.

## On media assets

- Videos/GIFs must not show printed lab banners, name tags, office
  nameplates, or posters identifying institutions.
- Screen captures should not include desktop wallpapers, file paths,
  usernames, calendar entries, or terminal prompts that reveal
  identity.
- Audio (if any) must not include recognizable voices.

## If you discover a leak

Remove the content, force-push the sanitized history if necessary,
and report it immediately through the anonymous preprint portal
referenced in the paper.

---

*This notice remains in place until the review cycle closes and the
paper is either accepted or the anonymity requirement is otherwise
lifted.*
