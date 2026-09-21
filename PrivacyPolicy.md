# LumenVision — Privacy Policy

**Last updated: 22 September 2026**

LumenVision is a single-player climbing game with no account, no advertising, no
analytics and no third-party code of any kind. It has no server behind it. This
page describes exactly what the game writes down, where that lands, and how to
erase it.

The short version: everything the game stores is your own game progress, it
lives on your device and in your own iCloud storage, and none of it reaches me
or anyone else.

---

## Everything LumenVision stores

There are two kinds of stored data, and this is the complete list of both.

**Progress, saved on the device and mirrored to your iCloud account:** best
score, best combo, best distance climbed, coins earned, coins spent, current
coin balance, which marble skin is selected, which skins are unlocked, the date
of your last daily reward, and two bookkeeping values used to decide which
device's save is newest.

**Preferences, saved on the device only:** music volume, sound-effects volume,
haptics on or off, reduce motion on or off, high contrast on or off. These do
not sync; each device keeps its own.

That is the whole of it. There is no player profile, no identifier, no history
of what you did or when you played.

---

## Where it goes

Progress is written locally through Apple's `UserDefaults` and mirrored to
Apple's `NSUbiquitousKeyValueStore` — your private iCloud key-value storage,
attached to your own Apple Account. Apple operates that storage; I cannot see
inside it, and no copy is sent anywhere else. If you are not signed in to
iCloud, the game simply keeps everything on the device.

Nothing else leaves your device. The game generates each shaft as you climb
rather than downloading anything, so a normal session uses no network at all.

---

## Email you choose to send

*Settings → Feedback → Send Feedback* opens your own mail app with a subject
line already containing your platform, OS version, device model and app version,
because those are the details I need to reproduce a bug. The message sits in
your mail app until **you** press Send, and I receive only what you actually
send. If no mail app is set up, the game copies my address to the clipboard
instead. Anything you email me is kept only as long as it takes to answer you.

---

## What the game never does

It does not ask for your name or email, and has no sign-in. It contains no
analytics, no advertising SDK, no crash reporter and no third-party libraries
whatsoever — the entire app is Apple's own frameworks and code written for this
game. It does not track you across other apps or websites, does not read your
location, camera, microphone, photos, contacts or health data, and shows no
advertising. The bundled privacy manifest declares no tracking, no tracking
domains and no collected data types, which is a claim Apple's tooling checks
against the shipped binary.

The one system feature that reaches outside the game is Apple's review prompt,
which may ask you to rate the app after you have played a while. It is Apple's
standard prompt and it hands me nothing but the rating you choose to leave in
the App Store.

---

## Erasing everything

- **Reset progress:** *Settings → Reset All Progress* clears scores, coins and
  unlocked skins on the device and in iCloud. It cannot be undone.
- **Remove the local copy:** deleting the app removes everything it stored on
  that device.
- **Remove the iCloud copy:** delete it from your device's iCloud storage
  settings, under this app's entry.

There is no account to close and no deletion request to send me, because nothing
of yours is held on my side. If you would like help confirming that, write to me
and I will walk through it with you.

---

## Children

LumenVision is rated 4+ and is safe for young players. It collects nothing, has
no advertising, no in-app purchases, no chat or messaging, no account, and no
links that lead out of the game during play. Because no personal information is
collected from anyone, there is nothing for a parent to consent to or withdraw
under COPPA, the GDPR or similar laws elsewhere.

---

## Changes and contact

If this policy changes, the date at the top changes with it, and the previous
wording stays visible in this document's history.

Questions about anything above:

**davinci.dalhi@gmail.com**

This policy covers LumenVision on iPhone, iPad, Mac and Apple Vision Pro, and is
maintained by Ahmed DALHI, the game's sole developer.
