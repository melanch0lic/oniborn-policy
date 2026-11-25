# ONIBORN Privacy Policy

The privacy policy of ONIBORN, the roguelite game for Android and iOS, published with GitHub Pages.

Public URL (the one entered in Google Play Console and App Store Connect, and linked from the game's
Settings → About): https://melanch0lic.github.io/oniborn-policy/

Support page (the App Store's Support URL): https://melanch0lic.github.io/oniborn-policy/support.html

## What it describes

The policy describes what the ONIBORN apps actually do with data, as audited in their code on
2026-11-25 (version 1.5.0):

- offline play; progress, settings and a local diagnostic journal kept only in the app's private storage;
- the optional Hall of Legends (Supabase): anonymous account created only when the player picks a
  nickname; nickname and run results stored and shown publicly; Leave in Settings deletes them
  (`delete_my_leaderboard_data`);
- the update check: a public versions file on GitHub Pages, and Google Play in-app updates on Android;
- no ads, analytics, tracking, crash reporting or purchases; the support link is Android only;
- device backups left at their defaults (Android Auto Backup, iCloud / computer backup on iOS).

It must stay in sync with the app, the Google Play Data safety form, the App Store privacy answers and
`ios/Runner/PrivacyInfo.xcprivacy`. Update it **before** releasing a version that adds an SDK, a
network call, a permission, accounts, purchases or cloud saves.

## Updating the policy

1. Edit `index.html` (or `support.html`, the help page: keep its answers in step with the game's
   labels in `lib/l10n/app_en.arb`): the content and both "Last updated" dates (the header's `<time>` and the footer).
2. Open it in a browser to check it.
3. Commit and push to `main`. GitHub Pages republishes the site in a minute or two at the same URL.

The page is a single self-contained HTML file: no build step, no scripts, no external resources.
