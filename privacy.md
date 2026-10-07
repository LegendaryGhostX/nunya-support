---
layout: default
title: Privacy Policy
---

# Privacy Policy — Nunya

_Last updated: 2026-10-06_

Nunya is a private photo and video vault, locked with Face ID or a passcode.
Everything you put into it stays on your phone. This page says exactly what
that means.

## The short version

Nunya has no server, no account, and no cloud sync. There is nothing to log
into and nowhere for your data to go except your own device.

This version of Nunya makes no network connections of any kind. It does not
use the local network or Bluetooth, and it advertises nothing to nearby
devices.

## What we collect

**Nothing.** Nunya's App Store privacy label answers "Data Not Collected" for
every category Apple asks about — contact info, user content, identifiers,
usage data, diagnostics, all of it. There is no analytics, no crash reporter,
no ad network, and no third-party code of any kind in the app.
`PrivacyInfo.xcprivacy`'s `NSPrivacyCollectedDataTypes` is an empty array,
matching this statement in the app's own machine-readable manifest.

## Where your data lives

Everything Nunya holds stays on this device. Vault photos and videos, people,
plans and settings are kept in the app's own storage. The app's data file and
its vault photos and videos are protected with iOS complete file protection
and excluded from iCloud and computer backups, so a backup of your phone never
carries a copy of them.

Your passcode is kept only in this device's Keychain, set so it never moves to
another device. It is never written into the app's data file.

Photos and videos you take with the in-app camera go straight into the vault.
For a video, iOS hands Nunya a temporary copy; Nunya deletes that temporary
copy once it has saved the video. If the save fails, Nunya tells you it could
not stash the clip and still deletes the temporary copy, so that recording is
not kept anywhere.

## Network connections

This version of Nunya makes no network connections of any kind. It does not
use the local network or Bluetooth, and it advertises nothing to nearby
devices. You will not see a Local Network or Bluetooth permission prompt.

Nearby phone-to-phone messaging is planned for a future update. This policy
will be updated before it ships.

## Deleting your data

**Wipe this device.** "Wipe this device" in Settings deletes vault photos and
videos, people, plans, any chats and messages, settings, and any preserved
copies of an unreadable data file. It also resets the passcode, clears the
failed-attempt counter, deletes the legacy device identifier, and returns the
app to first-launch setup. The optional "Erase after 10 failed attempts"
setting performs the same wipe. It counts wrong passcodes entered on the
passcode screen only; guesses typed on the calculator decoy never trigger it
and never add a delay.

**Deleting the app.** Deleting the app removes all of its files. iOS may keep
the app's small Keychain records (the passcode hash, the failed-attempt
counter and a legacy device identifier) after the app is deleted. Nunya
overwrites or clears them the next time it is installed and opened, and
nothing else survives.

## What this means

1. **What you put in Nunya stays on your phone.** It is protected with iOS
   complete file protection, kept out of iCloud and computer backups, and
   never uploaded or synced anywhere.
2. **Nunya does not connect to anything.** No server, no account, no cloud,
   no local network, no Bluetooth, and nothing advertised to nearby devices.
3. **You decide when it goes.** "Wipe this device" deletes everything listed
   above and resets the passcode. Deleting the app removes all of its files;
   only the small Keychain records described above can outlast it, and Nunya
   overwrites or clears them the next time it is installed and opened.

## Questions

This policy is published at
https://legendaryghostx.github.io/nunya-support/privacy, alongside the support
page at https://legendaryghostx.github.io/nunya-support/support. If anything
here is unclear, email nunya.support@proton.me.
