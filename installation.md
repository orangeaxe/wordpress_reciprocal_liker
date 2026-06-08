# Reciprocal Liker Installation Guide

## Requirements

Before installing Reciprocal Liker, make sure you have:

- A self-hosted WordPress website
- A WordPress.com account
- Administrator access to your WordPress site
- Permission to install plugins

---

## Install the Plugin

1. Download the latest release ZIP.
2. In WordPress Admin:
   - Plugins → Add New Plugin
   - Upload Plugin
3. Select the ZIP file.
4. Click Install Now.
5. Click Activate.

You should now see:

Settings → Reciprocal Liker

---

## Create a WordPress.com OAuth Application

Visit:

https://developer.wordpress.com/apps/

Create a new application.

Recommended settings:

Application Name:
Reciprocal Liker

Application Website:
https://YOUR-DOMAIN.COM

Redirect URI:

https://YOUR-DOMAIN.COM/wp-admin/admin-post.php?action=rcl_exchange_code

---

## Configure the Plugin

Open:

Settings → Reciprocal Liker

Enter:

Client ID
Client Secret

Save Settings.

---

## Authorize the Plugin

Click:

Authorize with WordPress.com

Approve access.

You should be returned to WordPress.

The plugin will automatically save:

- Access Token
- Blog ID
- Blog URL

---

## Verify Installation

Enable:

Dry Run

Click:

Clear Queue/Seen
Clear Log
Scan Likes

If successful, you should see:

Notification scan complete

and queued items should appear.

---

## First Live Test

Leave Dry Run enabled.

Wait until an item becomes due.

Click:

Process Queue

The log should indicate that the plugin would have liked a post.

Once confirmed, disable Dry Run.
