# Privacy Policy

**Effective Date:** September 8, 2026  
**App Name:** TikTok Bot Studio  

## 1. Overview
TikTok Bot Studio is a creator desktop and web application designed to help authorized content creators generate short-form videos and publish them directly to their own TikTok accounts using TikTok's official Content Posting API.

## 2. Information We Collect and Process
Our application is designed with a strict privacy-first architecture:
- **OAuth Authentication Tokens:** The application securely manages OAuth tokens obtained directly through TikTok Login to interact with TikTok APIs on your behalf. These tokens are stored strictly on your local machine.
- **Media Content:** All synthesized video, audio, and visual assets are stored locally on your device storage.
- **Account Metadata:** Profile information (such as creator nickname/username) is fetched solely to identify the active connected account in the local dashboard.

We do **not** sell, transfer, transmit, or share your data or media with any third parties.

## 3. TikTok API Permissions & Scopes
TikTok Bot Studio utilizes the following TikTok Developer scopes:
- `user.info.basic`: Verifies account authentication and displays creator username in the studio.
- `video.publish`: Posts completed video assets with titles, descriptions, and hashtags directly to your TikTok profile.
- `video.upload`: Uploads video chunks to TikTok servers during publication.

## 4. Data Retention & Deletion
Because all data and tokens reside locally on the user's computer:
- Users can delete generated media at any time through the Video Vault interface.
- Users can revoke access or delete stored credentials at any time by logging out or revoking application access within their TikTok App Settings (*Security > Manage App Permissions*).

## 5. Security
All communications with TikTok APIs are conducted strictly over encrypted HTTPS protocols adhering to TikTok Developer Security standards.

## 6. Contact
For any inquiries regarding this policy, please reach out to the developer via GitHub.
