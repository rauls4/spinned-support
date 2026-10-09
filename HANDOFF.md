# Spinned Google Play handoff

Raul Silva is publishing the Android game Spinned. Continue in Play Console from the store listing. Do not repeat finished policy forms. Do not invent new screenshot sizes.

Play Console is signed in on Raul’s Mac. A remote agent cannot drive that browser. Do not ask him to sign the Google account into another machine.

## App

- Title: Spinned
- Developer: Raul Silva
- Android package: `com.silvadesign.spinned`
- iOS is already live: App Store id `466332297`
- Website: https://rauls4.github.io/spinned-support/
- Privacy policy: https://rauls4.github.io/spinned-support/privacy/
- Support: GitHub issues on https://github.com/rauls4/spinned-support
- Free. No ads. No in-app purchases. No Spinned account. No analytics.
- Internet is used only for optional Google Play Games.
- On the device only: best score, each day’s Daily Show best, settings, and counters (games played, fly swats, whether a review was already requested). The app requests vibration. It does not request contacts, photos, camera, microphone, or location.
- Optional Play Games sign-in shares the Play Games player ID, scores, and achievements with Google. The game works without signing in.
- Google Play in-app review is handled by Google Play.

## Already done in Play Console

- Phone number on the developer account is verified.
- The app exists as `com.silvadesign.spinned`.
- App content says nothing needs attention. These declarations are saved:
  - Data safety, submitted or saved through preview after the target-age requirement was cleared.
  - Sign-in details: **No**. No part of the app is restricted. Play Games is optional and there are no payments.
  - Target audience: **13–15, 16–17, and 18 and over**. Ages under 13 are intentionally not selected. Do not open the Families policy.
  - Content ratings: category **Game**, IARC terms accepted. Australia came back **General**. Saved.
  - Advertising ID: the app does not use an advertising ID.
  - Health apps: none.
  - Government apps: no.
  - Financial features: no.
- Privacy policy URL is already entered: `https://rauls4.github.io/spinned-support/privacy/`
- It is not on the Store settings page. That page has no privacy-policy field.

### Data safety answers, if a form is reopened

- Collect or share required user data: **Yes**
- Encrypted in transit: **Yes**
- Account creation: **My app does not allow users to create an account**
- Can users log in with accounts created outside the app: **Yes**
- How those accounts are created: **Other**
- Text for that box: `Players can optionally sign in with an existing Google account through Google Play Games. Spinned does not create the account.`
- “Do you provide a way for users to request that their data is deleted?”: **No**
- Data types, and only these: **Personal info → User IDs**, and **App activity → App interactions**
- User IDs: collected yes, shared yes, not processed ephemerally, users can choose, purposes **App functionality** and **Account management**
- App interactions: collected yes, shared yes, not processed ephemerally, users can choose, purpose **App functionality** only
- Do not declare location, name, email, photos, device IDs, or crash logs. On-device scores and settings never leave the phone, so they are not data types.

## Where he is stuck

**Grow users → Store presence → Store listings → Default store listing**, language **English (United States)**.

The page shows “Some languages have errors” until the required images are actually placed in the boxes. Uploading a file into the asset library does not place it. A slash on a thumbnail is the library marker. It is not, by itself, proof the file is the wrong size.

### Listing text already entered

**App name:** Spinned

**Short description:**

```
Spin the plates to the Sabre Dance. A free arcade game with no ads.
```

**Full description:**

```
Spinned is a plate-spinning arcade game. Keep the plates, cups, bowls, vases, and a wine glass spinning to the Sabre Dance.

Daily Show, leaderboards, and achievements are available when you sign in with Google Play Games. You can play without signing in.

Free, with no ads and no in-app purchases.

By Raul Silva.
```

Leave **Video** empty.

### Images

All files: https://github.com/rauls4/spinned-support/tree/cursor/play-listing-assets-8136/images/play

Pull request: https://github.com/rauls4/spinned-support/pull/4

| File | Use |
| --- | --- |
| `icon-512.png` | App icon. 512×512 PNG. If the App icon box is still empty, select this file. |
| `feature-graphic-2048x1000.jpg` | Feature graphic source. The crop tool rejects the exact 1024×500 file as too small. |
| `feature-graphic-1024x500.jpg` | Do not use. |
| `phone-1-title-2.jpg`, `phone-2-game-2.jpg`, `phone-3-stage-2.jpg` in the Play library | Phone screenshots. These are 1920×1080, 16:9. Already uploaded. |
| `Cropped (1) - phone-3-stage-2` | Already cropped to 16:9, 1920×1080. Cropping did not change the pixels. It still has to be added with the arrow. |
| `phone-*-large.jpg` (3840×2160) | Do not upload. Not needed. |
| Anything 1400×1050 | Do not use. Those are 4:3 iPad frames. The phone slot rejects them. |

### How the crop tool actually behaves

The crop dialog opens on **App icon**, which forces a square. That mistake already created a useless 512×512 crop of the feature graphic. Do not save a crop while **App icon** is selected unless the target really is the icon.

For a phone screenshot:

1. Click the crop button on the row, not the thumbnail.
2. Choose **Other sizes → 16:9 Landscape**.
3. Click **Save as copy**.
4. On the new cropped row, click the **arrow on the right**. That arrow is what puts the image into the red box. Clicking the thumbnail does nothing.

`phone-3-stage` is already through step 3. It still needs step 4. Then do steps 1–4 for `phone-1-title-2.jpg` and `phone-2-game-2.jpg`.

For the feature graphic, crop `feature-graphic-2048x1000.jpg` with the feature-graphic preset, not App icon, then use the arrow to place it. If the feature-graphic box is already filled, leave it.

Then click **Save as draft**. Do not click **Discard**.

## Immediately after the listing saves

**Store settings** (Grow users → Store presence → Store settings) was still incomplete:

- Category: **Arcade**. It was “Not selected”.
- Email: the Google account address under **Personal** at the top of Play Console. Use that inbox. Do not use an Apple private-relay address.
- Phone: leave blank.
- Website: `https://rauls4.github.io/spinned-support/`
- External marketing: leave it alone.

## After that, the release

The Android App Bundle is not in this website repo. It has to be uploaded from the machine that built the app.

- Track: **Test and release → Closed testing**. Internal testing does not count.
- A personal Play account must keep at least 12 testers opted in for 14 continuous days before production.
- The bundle must use package `com.silvadesign.spinned` and target Android 16 (API 36).
- Link **Play Games Services** for Daily Show, leaderboards, and achievements. Package name must match.
- App is free. No ads. No in-app products.

## Do not redo

- Do not ask Raul to screenshot every field.
- Do not add more image dimensions.
- Do not target children under 13.
- Do not say Spinned creates user accounts.
- Do not declare on-device-only data in Data safety.
