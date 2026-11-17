# Twilio ISV SMS Onboarding Demo

A clickable prototype that shows how a software platform (an ISV) can onboard its own customers to SMS with Twilio. It covers two markets:

- **🇺🇸 United States** uses a toll-free number, the Compliance Embeddable, and the Compliance Toolkit.
- **🇪🇸 Spain** uses an alphanumeric sender ID registered with the CNMC, plus the AlphaSender API.

**Live demo:** https://joshskifstrom.github.io/twilio-isv-sms-onboarding-demo/

## Controls

| Key | Action |
|---|---|
| `→` / `←` | Next / previous step |
| `1` / `2` | Switch to US / Spain |
| `B` | Toggle the behind-the-scenes panel |
| `N` | Toggle the talk track |
| `W` | Outline the embedded Compliance Embeddable area (US) |
| `R` | Reset |

This is a single static `index.html` with no build step and no dependencies. All businesses and data are fictional, and the demo makes no real API calls.
