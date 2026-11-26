# Privacy Policy

**Movie Finder AI** for iPhone and **Ai Movie Finder** for Android

**Effective date:** November 26, 2026

**Publisher:** MovieFinder AI Studio

**Contact:** [moviefinderai.dev@gmail.com](mailto:moviefinderai.dev@gmail.com)

This policy covers the Movie Finder AI app for iPhone (App Store) and the Ai Movie Finder app for Android (Google Play), together called "the app". The app identifies movies and TV shows from short video clips. This policy explains what information the app handles, why, who receives it, how long it is kept, and what choices you have.

## Summary

- The app has no accounts. You never give us a name, email address or password to use it.
- The clip you choose to scan is sent to our server and to AI providers only to identify the title. It is deleted after the scan.
- History, favorites and your profile are stored on your device, not on our servers.
- We do not show ads, we do not track you across other apps or websites, and we do not sell personal information.
- Payments are handled by Apple or Google. We never see your card details.

## 1. Information we handle

### 1.1 Install ID (Support ID)

The app does not create accounts and does not use any sign-in service. On first launch it generates a random identifier, the **install ID**, and stores it on your device. In the app it is shown on the Profile screen as your **Support ID**.

We use the install ID to:

- Count scans against the free and Premium limits
- Check whether Premium is active for your install
- Find your records when you contact support
- Link an optional review submission (section 1.7) to an install

The install ID is not an advertising identifier and is not used for tracking.

### 1.2 Device check (iPhone only)

To stop the free scans from being reset by reinstalling the app, the iPhone app uses Apple's **DeviceCheck** service. The app asks iOS for a short-lived token and sends it to our server with scan and quota requests. Our server passes the token to Apple, which stores two bits of information for your device and our developer account: in practice, whether the free scans on that device have been used.

The token does not reveal your Apple Account, your name, or your device's serial number to us, and we cannot use it to identify you.

### 1.3 Clips, links and related content

When you ask the app to identify a title, it processes:

- A video you pick from your photo library or files
- A link or video you share to the app from TikTok, Instagram, Facebook, YouTube or another app
- Text that comes with the shared item, such as a caption, hashtags or the link itself
- Frames taken from the clip and, when needed to recognize an actor, cropped face regions from those frames
- An actor name, if you add one to help the search
- In Android versions before 1.0.7 only: a short screen recording, described in section 3

This content is sent to our server and, as needed, to the AI and movie-data providers listed in section 5, to return the title, poster, cast, description, ratings and where to watch.

On iPhone, the app reads only the video you select. It does not have access to the rest of your photo library.

### 1.4 TikTok, Instagram and Facebook sign-in cookies

Some Instagram and Facebook clips, and on Android some TikTok clips, can only be downloaded while signed in. In that case the app can open that platform's own sign-in page inside the app. If you sign in, the session cookies from that page are used **only** to download the clip you asked us to analyze, and may be sent to our server for that download.

We never see your password. We do not use those cookies to post, like, comment, message or take any other action on your account. Cookie files used on our server for a download are deleted after the download attempt.

### 1.5 Data stored on your device

The app stores the following on your device only:

- An optional display name and profile photo
- Your scan history and favorites
- The country used for where-to-watch results
- App settings and the install ID

If you use the backup feature, the app writes your history and favorites to a file that you choose where to save. We do not receive that file.

Clearing the app's data or deleting the app removes this information.

### 1.6 Scan counts and subscription status

For each install ID our server stores:

- Total and daily scan counts, with the related dates
- Whether Premium is active, as reported by RevenueCat

If you buy Premium, the purchase is processed by **Apple** (iPhone) or **Google Play** (Android). **RevenueCat** manages the subscription status on our behalf, using your install ID as the customer identifier. We do not receive or store your card number or billing address.

### 1.7 Optional review submissions

If a scan fails and you choose to send the link to us for review, we store the link, the platform, an optional reason, your install ID and the time. We use this to improve download and recognition reliability. Please do not submit links you do not want us to review.

### 1.8 Technical information

To run and troubleshoot the service, our server logs technical information about requests, such as the time, the result of a scan (success or failure), error messages, the where-to-watch country sent with the request, and the IP address the request came from.

The app contains no advertising or third-party analytics software.

## 2. Why we use this information

| Purpose | Information used | Legal basis (EU/EEA and UK) |
|---|---|---|
| Identify the movie or show you asked about | Clips, links, captions, frames, actor name | Performance of our contract with you |
| Download the clip you shared | Link, and sign-in cookies if you provide them | Performance of our contract with you |
| Apply free and Premium scan limits and prevent abuse | Install ID, scan counts, device check | Our legitimate interest in keeping the service fair and affordable |
| Provide and restore Premium | Install ID, subscription status | Performance of our contract with you |
| Keep the service working and fix faults | Technical information, review submissions | Our legitimate interest in running a reliable service |
| Answer support requests | Install ID, your email and message | Our legitimate interest in supporting users |

We do not use your information for advertising or for automated decisions that have legal or similarly significant effects on you.

## 3. Screen recording (older Android versions only)

The Android app does not record your screen from version 1.0.7 onward, and no longer asks for that permission. In earlier Android versions, when a shared clip could not be downloaded directly, the app could ask for Android's screen capture permission. Recording starts only after you approve the system prompt, a notification is shown while it runs, and it captures a short segment of what is on screen so it can be analyzed. It is not used for background monitoring. The recording is treated like any other clip: it is sent to our server for identification and deleted after processing.

The iPhone app does not record your screen.

## 4. How long we keep information

| Information | Kept for |
|---|---|
| Clips, frames, screen recordings and download cookies | The duration of the scan. They are deleted when the scan finishes. If cleanup fails, leftover temporary files are removed during normal server maintenance. |
| Scan counts for an install ID | As long as needed to apply the scan limits |
| Device check bits (iPhone) | Held by Apple for your device until we reset them |
| Review submissions | Until they have been reviewed, or until you ask us to delete them |
| Server logs | A limited period, for troubleshooting and abuse prevention |
| History, favorites, display name, profile photo | On your device, until you remove them or delete the app |
| Subscription records | As kept by Apple, Google Play and RevenueCat under their own policies |

## 5. Who receives information

We do not sell personal information and do not share it for advertising. We use the following service providers, each only for the purpose shown:

| Provider | Purpose | What it receives |
|---|---|---|
| Railway | Server hosting | Scan requests, clips and frames while they are processed, install ID, scan counts |
| xAI (Grok); OpenAI as a fallback | AI analysis | Frames, face crops, captions and related text |
| TMDB; OMDb | Movie and TV data | Title searches and the where-to-watch country |
| Apple | App Store distribution, payments, DeviceCheck (iPhone) | Purchase details, device check token |
| Google Play | Distribution and payments (Android) | Purchase details |
| RevenueCat | Subscription status | Install ID, purchase and entitlement status |
| TikTok, Instagram, Facebook, YouTube | Fetching the clip you shared | The request for that clip, and your session cookies if you signed in |

These providers handle information under their own terms and privacy policies. We may also disclose information if the law requires it or to protect the rights and safety of users and the service.

Movie Finder AI is not affiliated with TikTok, Instagram, Facebook or YouTube. This product uses the TMDB API but is not endorsed or certified by TMDB.

## 6. International transfers

Our providers operate in several countries, including the United States, so your information may be processed outside the country where you live. Where the law requires it, transfers rely on safeguards such as the European Commission's standard contractual clauses or the provider's certification under an approved data-transfer framework.

## 7. Your choices

You can:

- Decide which clips you scan. Nothing is sent until you start a scan
- Decline to sign in to TikTok, Instagram or Facebook when asked
- Decline the screen capture permission, in Android versions before 1.0.7
- Decline to submit a failed link for review
- Remove items from history or favorites, or clear them, in the app
- Cancel Premium at any time:
  - **iPhone:** Settings → your name → Subscriptions
  - **Android:** Google Play → Payments & subscriptions → Subscriptions
- Ask us to delete the server-side data for your install (section 9)

## 8. Your rights

Depending on where you live, you may have the right to:

- Ask for a copy of the information we hold about your install
- Ask us to correct or delete it
- Ask us to restrict how we use it, or object to our use of it
- Receive it in a portable format
- Complain to your local data protection authority

To use any of these rights, email [moviefinderai.dev@gmail.com](mailto:moviefinderai.dev@gmail.com) and include your Support ID. Because the app has no accounts, the Support ID is the only way we can find your records. We answer within one month.

## 9. Deleting your data

- **On your device:** clear history and favorites in the app, or delete the app.
- **On our server:** email [moviefinderai.dev@gmail.com](mailto:moviefinderai.dev@gmail.com) with your Support ID (Profile screen; tap it to copy). We will delete the scan counts and any review submissions linked to it.

We may keep limited information where needed to meet legal obligations or to prevent fraud and abuse of the free scans. Deleting the app does not cancel a subscription; cancel it as described in section 7.

## 10. Children

The app is not directed to children. It is not intended for anyone under 13, or under the minimum age required in their country for this kind of service. We do not knowingly collect personal information from children. If you believe a child has sent us information, contact us and we will delete it.

## 11. Security

Traffic between the app and our server is encrypted with HTTPS, clips are kept only while they are being processed, and access to the server is restricted. No online service can guarantee complete security.

## 12. Changes to this policy

We may update this policy as the app changes. The current version is always on this page, with its effective date at the top. If a change significantly affects how your information is used, we will also tell you in the app or on the store listing.

## 13. Contact

Questions, requests and complaints about privacy:

[moviefinderai.dev@gmail.com](mailto:moviefinderai.dev@gmail.com)

See also: [Support](./support)
