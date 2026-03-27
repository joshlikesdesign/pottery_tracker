# Pottery Tracker Pro — marketing

Working doc for web and cross-channel Pro messaging. Update when App Store pricing or product scope changes.

---

## Positioning

**One-liner:** Pro is for potters who outgrow the free tier — unlimited work on the shelf, deeper studio tools, and optional sync across your Apple devices.

**Audience:** Serious hobbyists through production potters; people juggling many pieces, firings, and glazes.

---

## Free vs Pro (product truth)

| | Free | Pro |
|---|-----|-----|
| Active pieces | Up to 40 | Unlimited |
| Core tracking, photos, tags, calendar | Yes | Yes |
| iCloud sync (optional) | — | Yes (Apple; Pro) |
| Kiln log | — | Yes |
| Studio analytics | — | Yes |
| Export PDF & CSV | — | Yes |
| Batch editing | — | Yes |
| Trim reminders (local notifications) | — | Yes |
| Piece / batch templates | — | Yes |

*Source: `PRO_SPEC.md`, in-app paywall (`ProPaywallSheet.swift`).*

---

## Pricing (US — verify in App Store Connect)

| Plan | Price | Notes |
|------|--------|-------|
| Monthly | $2.99/mo | |
| Yearly | $29.99/yr | Shown as ~$2.50/mo; **7-day free trial on yearly** where Apple offers it |

**Web:** `index.html` `#pro` shows USD as an example and states that regional pricing varies.

---

## Copy blocks (matches paywall order)

1. Unlimited pieces  
2. Private iCloud library sync  
3. Kiln log  
4. Studio analytics  
5. Export PDF & CSV  
6. Batch editing  
7. Trim reminders  
8. Piece templates  

**Purchase path:** In-app only. Marketing site links to the App Store listing; user subscribes inside Pottery Tracker (Settings → Pottery Tracker Pro, or any Pro-gated feature).

---

## Ship checklist

- [x] `#pro` section on `marketing/index.html` (highlights, feature list, pricing, CTA)
- [x] Nav link + meta/og description mention Pro
- [ ] Optional: dedicated Pro screenshots (`screenshots/screenshot-analytics.png`, kiln log, etc.) in a second row
- [ ] Re-read yearly trial + subscription legal copy after App Store review feedback

---

## Files

| File | Role |
|------|------|
| `marketing/index.html` | Main landing page including `#pro` |
| `marketing/styles.css` | Pro section layout |
| This doc | Strategy + checklist |
