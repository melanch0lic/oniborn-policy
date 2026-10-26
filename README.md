# ONIBORN Privacy Policy

The privacy policy of ONIBORN, the offline roguelite game for Android, published with GitHub Pages.

Public URL (the one entered in Google Play Console): https://melanch0lic.github.io/oniborn-policy/

## What it describes

The policy describes what the ONIBORN Android app actually does with data, as audited in its code
on 2026-10-26:

- no accounts, ads, analytics, crash reporting, purchases or notifications;
- no `INTERNET` permission in the release build, and no runtime permissions;
- progress, settings and a local diagnostic journal kept only in the app's private storage;
- Android Auto Backup left at its default (on), so saves may be in the user's Google backup.

It must stay in sync with the app. Update it **before** releasing a version that adds an SDK
(Firebase, AdMob, Play Games, ...), a network call, a permission, accounts, purchases or cloud
saves, and update the Google Play Data safety form at the same time.

## Updating the policy

1. Edit `index.html`: the content and both "Last updated" dates (the header's `<time>` and the footer).
2. Open it in a browser to check it.
3. Commit and push to `main`. GitHub Pages republishes the site in a minute or two at the same URL.

The page is a single self-contained HTML file: no build step, no scripts, no external resources.
