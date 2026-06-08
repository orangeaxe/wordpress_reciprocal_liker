# WordPress.com OAuth Setup

Reciprocal Liker uses the official WordPress.com OAuth API.

---

## Create an Application

Visit:

https://developer.wordpress.com/apps/

Click:

Create New Application

---

## Application Settings

Application Name:

Reciprocal Liker

Description:

Optional

Website URL:

https://YOUR-DOMAIN.COM

Redirect URL:

https://YOUR-DOMAIN.COM/wp-admin/admin-post.php?action=rcl_exchange_code

---

## Save

After saving, WordPress.com provides:

Client ID
Client Secret

Copy both.

---

## Configure Reciprocal Liker

Paste the Client ID and Client Secret into:

Settings → Reciprocal Liker

Click Save Settings.

---

## Authorize

Click:

Authorize with WordPress.com

Approve access.

The plugin will exchange the authorization code automatically.

---

## Success

The following values should populate automatically:

Access Token
Blog ID
Blog URL

You should not need to manually exchange tokens.

---

## Reauthorizing

If the plugin reports:

invalid_token

or

The OAuth2 token is invalid

simply click:

Authorize with WordPress.com

again.
