# qx-rules
Quantumult X Rules for CN &amp; GFW
# Quantumult X Rules

A clean and efficient ruleset for Quantumult X, optimized for international users.

## 📋 Ruleset Overview

| Ruleset | Purpose | Domains | Type |
|---------|---------|---------|------|
| `cn-domains.list` | China direct connection | 90+ | Bypass proxy |
| `gfw-domains.list` | International proxy | 80+ | Through proxy |
| `ad-block.list` | Ad & tracker blocking | 50+ | Block/Reject |

## 🚀 Quick Import

### Method: GitHub Pages (Recommended)

Add these to your Quantumult X config file under `[filter_remote]`:

```ini
[filter_remote]
# China Direct Rules
https://YOUR_USERNAME.github.io/qx-rules/filter/cn-domains.list, tag=🇨🇳 CN Direct, force-policy=direct, update-interval=604800

# GFW Proxy Rules
https://YOUR_USERNAME.github.io/qx-rules/filter/gfw-domains.list, tag=🌍 Proxy, force-policy=proxy, update-interval=604800

# Ad Block Rules (Optional)
https://YOUR_USERNAME.github.io/qx-rules/filter/ad-block.list, tag=🚫 Ad Block, force-policy=reject, update-interval=604800
