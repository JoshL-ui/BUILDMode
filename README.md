BuildMode | BEASTMode

A dark, industrial, strength-training tracker built as an installable iPhone web app (PWA).

## What's included
- BEASTMode dashboard and visual identity
- Monday / Wednesday / Friday machine-focused training program
- Individual exercise logging with weight, reps and set completion
- Previous-session performance reference
- Workout history and weekly session count
- Body-weight check-ins and editable weight goal
- Progress screen with logged-lift and body-weight summaries
- Searchable exercise library with muscle-group filters
- Offline caching after the first successful load

## Publish with GitHub Pages
1. Download and unzip this package.
2. Open your existing BuildMode GitHub repository.
3. Replace the existing app files with **all files inside this folder**. Keep them in the repository root, not inside another folder.
4. Commit the changes to your live branch.
5. Open Settings → Pages and confirm it is publishing from `main` and `/ (root)`.
6. Once GitHub Pages has deployed, open the same app address in Safari on your iPhone.
7. If the old version still appears, fully close Safari and reopen the app. The service worker cache is versioned to refresh the new design.
8. If the app is already on your Home Screen, open it again after the site has updated.

## Important
- Workout logs and weigh-ins are stored on that iPhone in Safari's local storage. They are not synced between devices and are not backed up to the cloud.
- Do not clear Safari website data if you want to keep your locally stored training history.
- The app uses your existing `buildmode_v1` local storage key so the redesign can continue using the data format from the earlier version. Still, keep your old ZIP as a backup before replacing files.
- The suggested starting weights are reference points only. Confirm loads safely and use controlled technique.
- This version is a first functional build. It has not yet been tested on your actual iPhone or gym workflow.
