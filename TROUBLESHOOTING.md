# Troubleshooting

## invalid_token

Meaning:

The OAuth token is invalid or expired.

Solution:

1. Open Settings → Reciprocal Liker
2. Click Authorize with WordPress.com
3. Complete authorization again

---

## token_target_mismatch

Meaning:

WordPress.com refused access to a target site.

This usually indicates:

- Private site
- API restriction
- Unsupported target

The plugin skips the site automatically.

---

## No queued items

Possible causes:

- No recent likes
- Notifications already processed
- Queue already cleared

Try:

Clear Queue/Seen
Scan Likes

---

## Critical Error After Update

Deactivate the plugin.

Install the latest release.

Reactivate.

If the problem continues, create a GitHub issue and include:

- Plugin version
- PHP version
- Error message

---

## Queue Never Processes

Verify:

Hourly Automation is enabled

or

Use:

Process Queue

manually.

---

## Plugin Responds To Itself

This should never happen in version 1.0.3 or newer.

If it does:

1. Clear Queue/Seen
2. Update to the latest release
3. Scan again

Report the issue on GitHub if it persists.
