# Privacy Policy for Ai Movie Finder

**Effective date:** July 30, 2026

**App name:** Ai Movie Finder (also referred to as Movie Finder)

**Developer / Publisher:** Ai Movie Finder Studio

**Contact email:** moviefinderai.dev@gmail.com

Ai Movie Finder is an Android app that helps users identify movies and TV shows from short video clips. You can share clips or links from TikTok, Instagram, or Facebook, or upload a video from your device. This Privacy Policy explains what information the app collects, how it is used, and what choices you have.

## 1. Information we collect

### Device / install identifier (no traditional account)

Ai Movie Finder does **not** create email/password accounts and does **not** use Google Sign-In or Firebase Authentication.

When you install the app, we generate a random **install ID** (a UUID stored on your device). We use this install ID to:

- Enforce free-tier and Premium scan limits
- Check Premium entitlement status
- Associate optional review/debug submissions with a device install

The install ID is not your Google Advertising ID. You can view and share it from the app’s Profile screen.

### Uploaded, shared, or captured video content

When you use the app to identify a movie or show, we may process:

- A video clip you upload from your device
- A video or link you share from TikTok, Instagram, Facebook, or another app
- Shared text, caption text, comments, hashtags, or URL text related to the clip, when available
- A short on-screen **screen recording** (see Section 3) when direct download of the shared clip fails and you approve Android’s screen capture permission
- Video frames and, when needed for identification, cropped face/actor regions extracted from those frames

This content is sent to our backend servers and may be forwarded to AI providers and movie-metadata services to return results such as title, poster, cast, description, rating, and where to watch.

### Social login session cookies (Instagram / Facebook)

For some Instagram or Facebook clips, the app may open an in-app WebView so you can log in to that platform. Session cookies from that login may be sent to our backend **only** so we can download the specific shared clip you asked us to analyze.

We do **not** use those cookies to post, like, comment, message, spam, or otherwise act on your social account. Temporary cookie files used for download are deleted after the download attempt.

### Local profile, history, and favorites

On your device, the app may store:

- Optional display name and profile photo you choose
- Analyze history and favorites/watchlist items
- Watch-country preference for streaming-provider results
- App settings and the install ID

History and favorites are stored **locally on your device** (not in a cloud account). Clearing app data or uninstalling the app removes this local data.

### Scan quota and Premium status

On our servers, we may store per–install ID:

- Lifetime and daily scan counts and related dates
- Whether Premium appears active (checked via RevenueCat using your install ID)

### Payment and subscription information

If you purchase Premium, payment processing is handled by **Google Play** and **RevenueCat**. We do not receive or store your full payment card details.

We may receive or store subscription-related status such as:

- Whether Premium is active
- Entitlement status
- Purchase/restore status
- The app user ID linked to the purchase (your install ID)

### Optional review / debugging links

If a match fails and you choose **Send to MovieFinder for Analysis** (or a similar review option), we may log:

- The URL you submit
- Platform and an optional reason
- Your install ID and a timestamp

This is used to improve download/identification reliability. Do not submit links you do not want us to review.

### Technical information

We may collect technical information needed to operate and debug the app, such as:

- App activity related to scans (success/failure, analyze status)
- Error messages and backend request status
- Device/app interactions needed for screen capture
- Watch-country preference sent with analyze requests

## 2. How we use information

We use collected information to:

- Identify movies or TV shows from clips, links, captions, and frames
- Provide free and Premium scan limits and prevent abuse
- Download the specific shared clip you asked to analyze (including via temporary social session cookies when needed)
- Show results, cast, descriptions, ratings, and watch-provider information
- Process Premium status and restore purchases
- Improve reliability (including optional review-link submissions)
- Provide user support when you contact us

## 3. Screen capture permission

When a shared TikTok, Instagram, or Facebook clip cannot be downloaded directly, Ai Movie Finder may ask for Android **screen capture** permission (MediaProjection).

Screen capture is used only after you approve the Android system permission prompt. A foreground notification is shown while capture is active. The app records a short segment of what is on screen so it can be uploaded for analysis. The app does **not** use screen capture for unrelated background monitoring, and capture is not used as continuous surveillance.

The recorded clip is treated like other uploaded video: it is sent to our backend for AI identification and is intended to be deleted after processing when cleanup succeeds.

## 4. How long we keep data

- **Analysis media** (uploaded videos, screen captures, extracted frames, and temporary cookie jars used for download) is processed for the request and is intended to be deleted afterward when cleanup succeeds.
- **Install ID quota records** (scan counts and related dates) may be kept on our servers while needed to enforce limits and operate the app.
- **Optional review-link submissions** may be kept for debugging and product improvement until we remove them as part of normal operations or you request deletion.
- **History, favorites, display name, and avatar** remain on your device until you clear them in the app, clear app data, or uninstall.
- **Subscription records** are also governed by Google Play and RevenueCat retention practices.

Some technical logs or failed cleanup records may remain briefly for debugging, abuse prevention, or operational purposes.

## 5. Sharing of information

We do not sell your personal information.

We may share or process information with service providers needed to run the app, including:

- **Our backend hosting** (for example, Railway), which receives analyze requests, videos/frames, optional social cookies for clip download, install ID, and related metadata
- **AI analysis providers** (including xAI / Grok and, when used as a fallback, OpenAI), which may receive frames, face crops, captions, and related text to identify titles and actors
- **TMDB** (The Movie Database) and related movie-data services (and optionally OMDb), to fetch metadata, posters, cast, and watch-provider information
- **Google Play**, for Android distribution and payments
- **RevenueCat**, for subscription entitlement management
- **Social / media download helpers** needed to fetch the clip you shared (for example, platform CDNs or download tooling), using the URL you shared and, when applicable, temporary session cookies

These services process data as needed to provide app functionality and according to their own terms and privacy policies.

## 6. Third-party services

Ai Movie Finder may use third-party services, including but not limited to:

- Google Play Billing
- RevenueCat
- xAI (Grok) and/or OpenAI for AI analysis
- TMDB movie data services (and optionally OMDb)
- Backend hosting (Railway)
- TikTok, Instagram, and Facebook (via share links, WebView login, and/or media download), only as needed for the clip you asked to analyze

Each third-party service may process information according to its own privacy and data-processing terms.

## 7. User choices

Users can:

- Choose whether to share or upload a clip
- Choose whether to log in via Instagram/Facebook WebView when prompted for download access
- Choose whether to approve Android screen capture permission
- Choose whether to submit a failed link for review
- Delete history or favorites items inside the app when available
- Cancel Premium subscriptions through Google Play
- Contact us to request deletion of server-side data associated with your install ID

## 8. Data deletion

Ai Movie Finder does not maintain a traditional user account. To request deletion of server-side data associated with your install, contact us at:

**moviefinderai.dev@gmail.com**

Please include your **Install ID** from the app’s Profile screen so we can locate the correct records (quota and any review-link submissions).

We may retain limited information if required for legal, fraud-prevention, payment, security, or operational reasons. Local history and favorites are removed by clearing them in the app, clearing app data, or uninstalling. Subscription management and cancellation remain available through Google Play.

## 9. Children

Ai Movie Finder is not intended for children under the age required by Google Play and applicable local law. Users should not submit personal information if they are not old enough to use the app under applicable rules.

## 10. Security

We use reasonable technical and organizational measures to protect information in transit and on our servers (for example, HTTPS for API calls and limited retention of analysis media). However, no internet-based service can guarantee perfect security.

## 11. International processing

Data may be processed in countries other than the country where you live, depending on the infrastructure used by our hosting provider, Google, RevenueCat, AI providers, TMDB, and other app services.

## 12. Changes to this Privacy Policy

We may update this Privacy Policy from time to time. If we make significant changes, we may update the effective date or notify users through the app or store listing.

## 13. Contact

For privacy questions or data deletion requests, contact:

**moviefinderai.dev@gmail.com**
