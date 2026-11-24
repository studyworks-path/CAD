# Clinical Assessment and Diagnosis · Case Trainer

EMT-level case trainer for PARA603 (AUT paramedicine), anchored to the NZ CPGs.

Students work through each case from dispatch to disposition: scene, primary survey, the four frames, vital signs and EWS, physical assessment, working diagnosis, differentials and disposition. There are 284 cases covering 124 diagnoses, with paediatric tools (assessment triangle, paediatric EWS charts and infant GCS) for children.

It also includes:

- Learn the diagnoses: an explanation, key findings, red flags, time-critical features and differentials for every diagnosis.
- Practise the skills: the 15 skills on the PARA603 skills log with their minimum criteria, practice ticks and a sign-off tracker.
- Four games: Keep them stable, Time critical, Beat the clock and Hot Seat with a Heads Up option.
- Do a shift: five jobs from five different presenting complaints, back to back, with an end-of-shift summary.
- Weak spots: any case a student doesn't diagnose right first time comes back after three days, and drops off once they get it right.
- A "Report a problem" link on every step of every case, which opens an email to the paper coordinator with the case and step filled in.

## Install on a phone

Once this repo is published with GitHub Pages, students can install the trainer like an app and use it offline:

- iPhone or iPad (Safari): tap Share, then Add to Home Screen.
- Android (Chrome): tap Install app when it's offered, or use the menu and choose Install app.

After the first visit it works with no signal. When it's online it checks for a newer version each time it opens. If you update `index.html` and want installed copies to refresh their offline cache straight away, change the version number in `CACHE` at the top of `sw.js`.

## Files

- `index.html`: the whole app.
- `manifest.json`, `sw.js` and the three `icon-*.png` files: these make it installable and let it work offline.
- `.nojekyll`: tells GitHub Pages to serve the files as they are.

The app is all in `index.html`. No sign-in, no server and no tracking. Progress, skill ticks and personal bests are saved only in the student's own browser.

Check all treatment against the current NZ CPGs.

The dyslexia-friendly reading option includes the OpenDyslexic font by Abbie Gonzalez, embedded under the SIL Open Font License 1.1 (see `OpenDyslexic-OFL.txt`).
