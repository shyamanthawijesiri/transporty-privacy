# Transporty Privacy Policy

Nov 7, 2026 · @shyamantha

## Introduction

Transporty does not ask for your name, email, phone number or an account. You can use the app without signing up. The only personal data it handles is your phone's location, and only while you choose to share live location during a trip.

This policy explains what the Transporty mobile app (package `com.transporty.transporty`) collects, why, who can see it, and the choices you have. It applies to the Android app published on Google Play. "We", "us" and "our" mean the Transporty team that operates the app.

**Effective date:** 7 November 2026

## Information we collect

We collect four kinds of data. None of it includes your name or contact details.

| Data | What it is | When it is collected |
| --- | --- | --- |
| Device identifier | A random ID (UUID) the app creates on first launch and stores on your phone. It is not your advertising ID, IMEI or phone number. | First time you open the app |
| Precise location | Your phone's GPS latitude and longitude. | Only while you turn on live location sharing for a trip, including when the screen is off during that trip |
| Trip activity | Trips you start or stop, stops you mark as arrived (by hand or by GPS), and bus turns you mark as cancelled for a day, each with the time and your device identifier. | When you take those actions |
| Technical data | IP address and request logs that our hosting provider records when the app connects to its servers. | Each time the app talks to the server |

We do **not** collect your contacts, photos, files, microphone, camera, calendar, payment details or advertising ID. The app has no ads and no analytics or tracking SDKs.

## How we use information

We use this data only to run the app's core feature: crowdsourced bus tracking. Users on a bus share its position and mark the stops it reaches, so other users can see where the bus is.

- **Live bus position.** Your shared location is shown to other users following the same trip, so they can see the bus approaching.
- **Automatic stop arrivals.** The app checks your location against each stop's area on your phone and records an arrival when the bus enters it.
- **Trip and turn status.** Trip starts, stops, arrival marks and cancellations update what every user sees for that route.
- **Preventing misuse.** The device identifier lets the app allow only the phone that took an action to undo it, and keeps only one phone sharing location per trip at a time.
- **Real-time updates.** Some bus turns are enabled by their operator for instant (real-time) updates; others refresh about once a minute. This choice is made by the operator and does not change what data is collected from you.

We do not sell your data, use it for advertising, or build profiles of you.

## Sharing and third-party services

Trip data and live location are visible to other users of the app, and are stored with one service provider. We share it with no one else.

- **Other users.** While you share live location, anyone using Transporty to view that trip can see the bus's current position. Arrival marks and cancellations are also visible to them. They see an anonymous device identifier at most, never your name.
- **Bus operators.** Operators who manage routes in the Transporty admin system can see trip records for their routes.
- **Supabase** ([privacy policy](https://supabase.com/privacy)) hosts our database and real-time service. It processes data on our behalf and only under our instructions.
- **Google Play services** may be used by Android to provide location fixes. Google handles that data under [Google's privacy policy](https://policies.google.com/privacy).
- **Legal reasons.** We may disclose data if required by law or to protect the safety of users.

All data is sent over encrypted connections (HTTPS).

## Permissions the app requests

The app asks for location and notification permissions only when you start sharing live location. Browsing routes, buses and turn times needs no permissions.

| Permission | Why it is needed |
| --- | --- |
| Precise and approximate location (while using the app) | To share the bus's live position and detect when it reaches a stop |
| Foreground service (location) | To keep sharing location while the screen is off during a trip you started sharing. A "Sharing live bus location" notification shows the whole time. |
| Notifications (Android 13+) | To show that ongoing sharing notification |
| Internet | To load routes and send trip updates |

The app does **not** request background location access. Location stops when you stop sharing, stop the trip, or close the app.

You can turn off any permission at any time in your phone's **Settings > Apps > Transporty > Permissions**. The app keeps working for browsing without them.

## Data retention and deletion

We store only your most recent shared position for each trip, not a history of your route. Trip records, arrival marks and location records are kept for up to **90 days** after the trip ends, then deleted automatically by a daily cleanup job.

- **Undoing actions.** You can undo a trip start, an arrival mark or a cancellation from the same phone; undoing a trip start deletes it and its location record.
- **Your device identifier** stays on your phone until you clear the app's storage or uninstall the app. After that, a new random ID is created and old records can no longer be linked to your phone.
- **Deletion requests.** Because there are no accounts, email us at **shyamanthawijesiri33@gmail.com** to ask us to delete data linked to your device. We will tell you how to find your device identifier and act within 30 days.

## Security, children and your rights

**Security.** Data travels over HTTPS, and database rules limit which actions each device may take. No method of storage or transfer is 100% secure, but we take reasonable steps to protect your data.

**Children.** Transporty is a general-audience transport app and is not directed at children under 13. We do not knowingly collect personal data from children. If you believe a child has shared location through the app, contact us and we will delete it.

**Your rights.** Depending on where you live, including under Sri Lanka's Personal Data Protection Act, No. 9 of 2022, you may ask to access, correct or delete data linked to your device, or object to its use. Contact us using the details below.

## Changes and contact

If we change this policy, we will update the effective date above and, for significant changes, tell you in the app or on its Google Play listing.

Questions, requests or complaints:

- **Developer:** Shyamantha Wijesiri
- **Email:** shyamanthawijesiri33@gmail.com
