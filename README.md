[README.md](https://github.com/user-attachments/files/28694320/README.md)
# Reciprocal Liker

Version 1.0.4

Quality-of-life update for the existing **Reciprocal Liker** plugin.

## What changed in 1.0.4

- Replaces the Queue `Delay` column with `Responds In`.
- Adds live remaining-time labels such as `Due now`, `42m 10s`, or `1h 12m`.
- Sorts queue rows by next scheduled response.
- Adds a queue summary panel:
  - In queue
  - Ready now
  - Needs attention
  - Next response
- Adds row highlighting:
  - Green: ready now
  - Yellow: due within 30 minutes
  - Red: failed or needs review
- Keeps all v1.0.3 safety fixes:
  - blocks self-responses
  - blocks source-post self-targets
  - preserves existing OAuth settings

## Update instructions

1. Upload `reciprocal-liker-v1.0.4.zip`.
2. Choose **Replace current with uploaded**.
3. Go to **Settings → Reciprocal Liker**.
4. Confirm the Queue now shows `Responds In`.

You should not need to re-authorize.

## Disclaimer

This plugin is an unofficial automation tool for WordPress.com interactions.

Users are responsible for ensuring their use complies with WordPress.com Terms of Service and community guidelines.

The author provides this software as-is without warranty.

## Support

If you encounter an issue:

1. Update to the latest version.
2. Review TROUBLESHOOTING.md.
3. Open a GitHub issue.
4. Include:
   - Plugin version
   - WordPress version
   - PHP version
   - Relevant log entries
