# steIN.github.io
steIN docs and privacy policies


# Privacy policy (linkedIN)

## Privacy Policy — whoS-te-IN

**Effective date:** 2026-02-06

### 1) Who we are
**whoS-te-IN** (“the App”) is an open-source, client-side application.

**Project repository (source and releases):**

https://github.com/BrianHeeseIs/steIN.github.io/

**Contact:** [brian@captech.dev](mailto:brian@captech.dev)

### 2) Scope of this policy

This Privacy Policy explains how the App handles information when you use it with LinkedIn authentication and LinkedIn API access.

### 3) High-level summary

* The App uses **LinkedIn OAuth 2.0** to authenticate you.
* If you authorize it, the App accesses your **LinkedIn 1st-degree connections data** via the LinkedIn API.
* The App is **client-side only** and does **not** operate any developer-controlled servers for collecting or storing personal data.
* Any data the App stores is stored **locally on your device**.
* The App does **not** transmit your LinkedIn data to the developer or to third parties.

### 4) LinkedIn endpoints the App uses

The App interacts with LinkedIn using these endpoints:

```text
https://www.linkedin.com/oauth/v2/authorization
https://www.linkedin.com/oauth/v2/accessToken
https://api.linkedin.com/v2/connections
```

### 5) Permissions requested (OAuth scopes)

The App requests the following LinkedIn OAuth permissions:

* `r_1st_connections` — permission to retrieve the authenticated member’s 1st-degree connections
* `r_compliance` — compliance permission that can also allow access to connections (for approved compliance use cases)

### 6) Information the App may access

Depending on what you authorize through LinkedIn OAuth, the App may access:

* **Authentication/authorization data**

  * OAuth authorization results and **access token(s)** issued by LinkedIn for the App.
* **Connections data**

  * Data returned by the LinkedIn API endpoint the App calls for connections:

    * `https://api.linkedin.com/v2/connections`
  * This may include information about your **1st-degree connections** as returned by LinkedIn under the permissions you granted.

The App only uses this information to provide the App’s functionality.

### 7) Where information is stored

* **Local device storage only:** Any information the App stores (including OAuth token(s) and any LinkedIn data retrieved through the API) is stored on the **same device** where you run the App.
* **No developer-hosted storage:** The developer does not receive or store your LinkedIn data on any servers.

### 8) How the App uses information

The App uses authorized information solely to:

* Authenticate you via LinkedIn OAuth 2.0
* Retrieve and display/use your LinkedIn connections data within the App

### 9) Data sharing

* The App does **not** sell, rent, or share your data with third parties.
* The App does **not** send your LinkedIn data to the developer.

**LinkedIn:** When you authenticate or authorize access, you interact with LinkedIn services governed by LinkedIn’s own terms and privacy policy.

### 10) Data retention

* **OAuth tokens:** Stored locally on your device to keep you signed in and reduce repeated login prompts, subject to LinkedIn expiry/revocation and your device’s storage behavior.
* **LinkedIn connections data:** Any data cached or stored by the App remains on your device until you delete it (see “Your choices and control”).

### 11) Your choices and control

You can remove the App’s local data and stop further access by:

* **Uninstalling/removing the App** (which removes locally stored App data, subject to your operating system’s behavior)
* **Revoking the App’s access in LinkedIn** (so the App can no longer access authorized data)

### 12) Security

Because the App stores data locally, security depends on your device and environment. You are responsible for protecting access to your device (e.g., OS account security, encryption, secure backups).

### 13) Children’s privacy

The App is not intended for children. If you are not permitted to use LinkedIn under LinkedIn’s rules, you should not use the App.

### 14) International use

The App is distributed as open-source software and may be used globally. The developer does not operate servers that collect or store personal data for the App.

### 15) Changes to this policy

This policy may be updated as the project evolves. The repository will reflect the current version and the **Effective date** will be updated when changes are made.

### 16) Contact

If you have questions or requests about this Privacy Policy, contact: **[brian@captech.dev](mailto:brian@captech.dev)**
