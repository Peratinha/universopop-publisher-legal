# Privacy Policy — Universo Pop Cortes Publisher

**Effective date:** 17 September 2026

## 1. Scope

This policy describes what data Universo Pop Cortes Publisher (the
"Application") handles. The Application is a private tool with a single user:
the owner of the TikTok account **@universopopcortes** (the "Operator"), who
runs it on their own computer to publish their own videos to their own
accounts. No other person's data passes through the Application.

## 2. Data the Application accesses

When the Operator connects a platform account, the Application receives, via
the platform's official API:

| Data | Why it is needed |
|---|---|
| OAuth access token and refresh token | To make API calls on behalf of the Operator's account |
| Basic profile of the connected account (display name, avatar, account ID) | To show the Operator which account is connected before posting |
| Creator settings returned by the platform (available privacy levels, duet / stitch / comment settings, video limits) | To present the correct posting options and respect the account's settings |
| Status of posts created by the Application | To confirm that a post was published |

The Application does **not** access followers, messages, comments from other
users, analytics beyond what is listed above, or any data about people other
than the Operator.

## 3. Data the Application stores, and where

- **Tokens and account settings** are stored in a local configuration file on
  the Operator's computer. They are never uploaded to any server controlled by
  the Operator or by third parties, and they are excluded from any code
  repository.
- **Videos, captions and cover images** are files the Operator created and
  keeps on their own computer.
- **A local log** records which video was posted, when, and the resulting
  post URL, so the Operator can keep track of their own publications.

When a cover image needs a public URL to be accepted by a platform's API, the
Application may upload that image (and only that image) to a temporary file
host; the file expires automatically after a short period.

## 4. Data sharing

The Application shares data only with the platforms the Operator has
connected (TikTok, Instagram, YouTube), and only the data required to create
the post the Operator has confirmed. It does not sell, rent or share data with
anyone else, does not use advertising or analytics SDKs, and does not run any
server that collects data.

## 5. Retention and deletion

Tokens remain on the Operator's computer until the Operator deletes the
configuration file or revokes the Application's access on the platform. The
Operator can revoke TikTok access at any time in *Settings and privacy →
Security → Manage app permissions*; after revocation the stored token is
useless and can be deleted. Local logs and media are kept or deleted at the
Operator's discretion.

## 6. Security

Credentials are kept only in a local file on a machine controlled by the
Operator. The Application communicates with the platforms exclusively over
HTTPS using their official API endpoints.

## 7. Children

The Application is not directed at children and has no users other than the
adult Operator.

## 8. Changes

If the Application changes in a way that affects this policy, this document
will be updated and the effective date revised.

## 9. Contact

Questions about this policy can be sent to the Operator at the contact
address listed on the TikTok profile @universopopcortes.
