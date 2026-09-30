# Proof Skincare — Privacy Policy

*Last updated: September 2026*

Proof Skincare ("Proof") is built on a simple rule: your face and your skin
data belong on your iPhone, not on our servers. This policy explains
exactly what stays on your device, the small amount of anonymous data that
doesn't, and why.

## What stays on your iPhone — everything personal

- **Your scan photos.** Captured, analyzed, and stored entirely on your
  device using Apple's on-device Vision framework. They are never uploaded,
  never backed up by us, and never leave your iPhone through Proof.
- **Your measurements.** Every skin metric (redness, breakouts, texture,
  tone evenness, shine), your Skin Score, your history, and your trends are
  computed and stored on your device. They are not uploaded anywhere.
- **Your profile.** Anything you enter about yourself during setup stays
  on the device.

Proof has no user accounts, no sign-in, and assigns you no identifier. We
could not link data to you even if we wanted to — there is no "you" in our
systems.

## Face data

Proof is a camera-based skin measurement app, so this section states
exactly what it does with face data. It is written to be read literally.

**What face data Proof collects.** Three things, all created on your
iPhone:

1. **Scan photographs of your face**, taken by you using the app's camera
   screen.
2. **Face landmark positions** — the approximate location of your eyes,
   nose, mouth and jaw within a photo — computed on your device by Apple's
   Vision framework. Proof uses them for one purpose only: to work out
   which part of the image is your forehead, cheeks, nose and chin, so
   measurements can be reported per area. These landmark positions are used
   during analysis and are **not saved**; they exist only in memory while a
   scan is being processed.
3. **Numeric measurements derived from the photo** — for example redness,
   visible blemish count, evenness of tone, and how much light your skin
   reflects — plus capture quality values such as head angle and image
   brightness.

**What Proof does not do.** Proof does **not** perform face recognition or
face identification. It does not create, derive or store a faceprint, face
template, or any biometric identifier. It cannot recognise you, match you
to another photo, or tell one person from another. It does not use Face ID,
ARKit face tracking, or the TrueDepth camera. Face data is never used for
authentication, advertising, profiling, or training any model.

**Where face data is stored.** Entirely on your iPhone. Scan photographs
are stored in the app's private container with iOS file protection
enabled. Measurements are stored in the app's local database on the same
device. Proof has no user accounts and no server-side storage of any kind
for face data — there is no copy of your photographs or face data on our
servers, because they are never sent there.

**Sharing with third parties.** Proof never transmits your photographs,
your face landmarks, or any image of you to us or to any third party. The
only data that ever leaves your device is described in the section below,
and it consists of numbers and text you entered — never an image. There is
no analytics SDK, no advertising SDK, and no third-party service that
receives face data.

Two actions can move a photo off your device, and both are started by you,
one at a time, with the destination chosen by you:

- **Sharing a comparison image.** If you tap Share on the photo comparison
  screen, iOS's own share sheet opens and you choose where the image goes.
- **Backing up your data.** If you tap "Back up my data" in Settings, Proof
  writes a single file containing your scans, photographs and measurements
  and hands it to the iOS share sheet so you can save it where you choose,
  such as the Files app or iCloud Drive. Proof does not upload this file
  anywhere, and we never receive it.

**How long face data is retained.** For as long as you keep it, and no
longer. Proof applies no expiry and performs no automatic deletion, because
the value of the app is your own history over time. You can delete
individual data or everything at once, at any time, using Settings →
"Delete everything", which erases every photograph, measurement, experiment
and profile detail from the device immediately and irreversibly. Deleting
the app from your iPhone also removes all of it. Because Proof holds no
copy on any server, deletion on your device is complete deletion — there is
nothing left for us to delete, and nothing for us to return.

## What leaves your device — anonymous and minimal

Three features talk to a server. None of these requests includes your name,
an account, your photos, or any device identifier.

1. **Verdict narration.** When you conclude an experiment, the numeric
   results (for example: "redness −2.4, high confidence") and the
   experiment's title (for example: "Added niacinamide serum") are sent to
   our server, where an AI model turns those numbers into a short written
   explanation. The numbers and title are processed to generate that text
   and are not stored as content; we retain only technical metadata
   (processing time and cost) to operate the service.

2. **Product barcode lookup.** When you scan a product barcode, the barcode
   alone is sent to look up that product's name, brand, and ingredients.
   Nothing else is sent, and nothing about your shelf is uploaded: products
   you add or edit stay on your device. Proof has no way for users to write
   to its product database.

3. **Weather context (optional, off by default).** If you switch on "Record
   the weather with each scan" in Settings, Proof asks iOS for your
   **approximate** location at the moment of a scan and sends it to Apple's
   WeatherKit service to look up the temperature, humidity and UV index.
   Proof never asks for your precise location, and your location is never
   stored — only those three weather values are saved with that scan, on
   your device. Weather data is provided by Apple Weather; Apple's use of this
   data is governed by Apple's own terms, available at
   [https://weatherkit.apple.com/legal-attribution.html](https://weatherkit.apple.com/legal-attribution.html).
   Switching the setting off stops this entirely.

If you never conclude an experiment, never scan a barcode, and leave
weather recording off, Proof sends nothing at all.

## What we don't do

- No advertising, and no ad SDKs.
- No analytics or usage tracking of any kind.
- No selling, sharing, or transferring of data to third parties for
  marketing.
- No reading or writing of Apple Health data.
- No tracking across other apps or websites.

## Purchases

Proof+ subscriptions are processed entirely by Apple through your Apple
Account. We receive no payment details and no purchase history tied to you.
Manage or cancel anytime in your Apple Account settings.

## Deleting your data

Settings → "Delete everything" erases all scans, photos, measurements, and
history from your device immediately and permanently. Because personal data
only ever existed on your device, that single action is complete — there is
nothing server-side to request deletion of.

Deleting the Proof app itself also removes this data. It is included in
your iPhone's own backups, so restoring a device or moving to a new iPhone
keeps it, but deleting the app is permanent. A backup file you export
yourself is under your control, in the location you chose to save it.


## Changes

If this policy changes, the updated version will be posted at this address
with a new date. Material changes to what data leaves your device would
also be reflected in the app's own disclosures.

## Contact

Questions about privacy in Proof Skincare: **stoqn780@gmail.com**
