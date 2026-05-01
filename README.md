# WestSmit Home Assistant Add-ons

A collection of custom Home Assistant add-ons.

## Add to Home Assistant

[![Add repository](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/WestSmit/ha-apps)

Or manually: **Settings → Apps/Add-ons → Install app/Add-on Store → ⋮ → Repositories** and paste:

```
https://github.com/WestSmit/ha-apps
```

---

## Apps (Add-ons)

### [TG Watch](tgwatch/)

Monitors selected Telegram channels and fires a Home Assistant webhook or custom event when a message matches your keywords or a regex rule.

**Features:**
- Keyword matching (substring list) or regex matching
- Skip regex to ignore noisy messages
- Webhook delivery to Home Assistant
- Custom event firing via the Supervisor API
- Anti-spam / dedup rate limiting

See [tgwatch/README.md](tgwatch/README.md) for full documentation and configuration options.
