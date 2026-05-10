# Privacy Policy for QazaqGuessr

Last updated: 2026-05-10

QazaqGuessr is a geography guessing game about Kazakhstan. This Privacy Policy explains what data QazaqGuessr collects, how it is used, how it is shared, and how users can request deletion of their data.

## Developer and Contact

QazaqGuessr is provided by Nurdaulet Kenges.

Privacy contact: qazaqguessr.support@atomicmail.io

## Data We Collect

QazaqGuessr does not request or collect the user's real-world physical location.

The app may collect the following data:

- Display name: a nickname chosen by the user for leaderboards and daily challenge rankings.
- Account identifiers: Firebase Authentication creates an anonymous user ID so scores and deletion requests can be associated with the correct player.
- Leaderboard data: player ID, display name, best score, selected region, region key, round count, and update timestamp.
- Daily challenge data: player ID, display name, daily date key, total score, round count, daily location IDs, round numbers, per-round scores, per-round distance in meters, and completion timestamp.
- Local app data: saved display name and local daily challenge completion marker.
- Analytics data: privacy-safe gameplay and app interaction events such as game start, round start, guess submitted, round completed, game completed, daily challenge usage, leaderboard opens, score submission result, share start, app language, session type, region key, score bucket, distance bucket, screen or surface, and Street View load failure information.
- Crash and diagnostic data: crash logs, stack traces, app version, device model, operating system version, performance diagnostics, and other technical information needed to diagnose app reliability.
- Device or app identifiers used by Google/Firebase services, such as Firebase installation identifiers, app instance identifiers, App Check signals, or similar identifiers used for analytics, security, abuse prevention, and diagnostics.

The app does not send exact target coordinates, exact guess coordinates, emails, phone numbers, contacts, photos, videos, messages, files, payment information, health information, or the user's physical location to QazaqGuessr servers.

Generated result images are created locally on the device. They are shared only if the user chooses to share them through Android's system share sheet.

## How We Use Data

QazaqGuessr uses collected data to:

- run the game and calculate scores,
- authenticate players anonymously,
- show global, regional, and daily leaderboards,
- prevent duplicate daily challenge attempts,
- keep official daily challenge results consistent,
- diagnose crashes, loading failures, and technical problems,
- measure aggregate gameplay funnels and improve the product,
- protect the backend from abuse through Firebase App Check and Firestore security rules,
- respond to user support and deletion requests.

QazaqGuessr does not sell personal data.

## Services and Sharing

QazaqGuessr uses Google and Firebase services to operate the app:

- Firebase Authentication for anonymous sign-in.
- Cloud Firestore for leaderboard rows, daily challenge definitions, and daily challenge attempts.
- Firebase Analytics for app usage analytics.
- Firebase Crashlytics for crash reporting and diagnostics.
- Firebase App Check for abuse prevention.
- Google Maps Platform, including Maps and Street View, for gameplay maps and panoramas.

These providers process data as service providers for app functionality, analytics, diagnostics, security, and compliance. Their processing is also governed by Google's privacy practices.

When a user chooses to share a generated result image, the selected destination app or service receives the shared content. That sharing is controlled by the user.

## Security

Data sent between the app and Google/Firebase services is transmitted using modern encrypted connections. Firestore security rules restrict writes to authenticated users and protect leaderboard, daily challenge, and deletion flows. Firebase App Check is used to reduce automated abuse.

No method of transmission or storage is perfectly secure, but QazaqGuessr is designed to minimize the amount of personal data collected and to avoid collecting sensitive categories that are not needed for gameplay.

## Retention

QazaqGuessr keeps user data only as long as it is needed for the purposes described in this policy:

- Local display name and daily completion marker stay on the device until the user deletes app data, uninstalls the app, or uses the in-app deletion flow.
- Leaderboard rows remain until they are replaced by a better score, removed through the deletion flow, or removed during maintenance.
- Daily challenge attempts remain so daily rankings can work, unless removed through the deletion flow.
- Analytics and crash diagnostics are retained according to the configured Firebase and Google service retention settings.
- Daily challenge definitions contain game content, not user data, and may be kept indefinitely.

## Data Deletion

Users can delete their QazaqGuessr user data inside the app:

1. Open QazaqGuessr.
2. Open Settings.
3. Choose Delete user data.
4. Confirm the deletion.

This deletes the saved display name, known leaderboard rows, daily challenge attempt data associated with the authenticated player, the anonymous Firebase account, local daily challenge status, and resets Firebase Analytics data for the app instance.

Some crash logs, analytics records, backups, or service logs that were already processed by Google/Firebase may remain for a limited time according to the relevant service retention settings, legal requirements, security needs, or backup systems.

Users can also request deletion outside the app by contacting qazaqguessr.support@atomicmail.io.

## Children's Privacy

QazaqGuessr is not designed to knowingly collect personal information from children. If you believe a child has provided personal data through QazaqGuessr, contact the privacy contact above so the data can be reviewed and deleted where appropriate.

## International Processing

QazaqGuessr uses Google and Firebase services that may process data in countries other than the user's country of residence. By using the app, users understand that data may be processed where these service providers operate.

## Changes to This Policy

This Privacy Policy may be updated as QazaqGuessr changes. The "Last updated" date will be changed when the policy is updated. Material changes should be reflected in the app, the public policy page, or the Google Play listing where appropriate.
