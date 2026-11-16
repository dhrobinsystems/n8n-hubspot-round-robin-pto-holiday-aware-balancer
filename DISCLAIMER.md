# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-hubspot-round-robin-pto-holiday-aware-balancer`) are provided for educational and architectural demonstration purposes.

## No Liability

The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. This includes, without limitation, lost or delayed leads, leads assigned to unavailable, overloaded or wrong reps, unfair or uneven lead distribution and any resulting compensation disputes, overwritten contact owners, unintended exposure of employee calendar or time-off information, regulatory or employment-law claims, service interruptions, and API quota exhaustion.

## No Warranty

All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.

No warranty is given that calendar out-of-office states, PTO records, holiday calendars or working-hour settings are complete, current or correctly interpreted; that Google Calendar, Microsoft Graph or PTO API responses remain compatible with this workflow; that workload counts reflect true capacity; that weighted round-robin, capacity, territory or fallback logic produces the distribution you intend; or that owner updates and notes succeed.

## Production Testing Required

Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, with `SANDBOX_MODE=true`, `DRY_RUN=true` and `ASSIGN_LEADS=false` enabled, before you connect live HubSpot or Google/Outlook calendar credentials. Verify every rep's availability state against reality, confirm workload counts against HubSpot views, test each calendar provider you intend to use, and review the distribution with sales leadership before activating the webhook and sweep schedule.

Treat every automated assignment as an operational decision that your sales leadership must monitor and be able to correct.

## Third-Party APIs & Compliance

You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and equivalents), employment and works-council requirements, and security policies of HubSpot, Google Calendar, Microsoft Graph / Outlook, your PTO or HR system, and any connected services. That includes:

- informing sales reps, and obtaining any required agreement, that their calendar out-of-office state, time-off records and workload are used for lead routing;
- granting only the minimum calendar and directory permissions needed, scoped to the relevant mailboxes or calendars;
- securing, rotating and restricting access to OAuth tokens, the HubSpot private app token, the HubSpot app client secret and any PTO API key;
- reviewing distribution fairness regularly where lead allocation affects compensation;
- limiting access to n8n execution data, which contains lead and availability information, and applying a retention period that matches your policies;
- reviewing every automatically created or updated record.

## No Affiliation

HubSpot, Google, Google Calendar, Microsoft, Outlook, Microsoft Graph and n8n are trademarks of their respective owners. This project is independent and is not affiliated with, endorsed by, or sponsored by any of them. All people, reps, companies, identifiers, calendars and events in the fixtures and pinned data are fictitious.

## Not Professional Advice

Nothing in this repository constitutes legal, employment, privacy, security, or financial advice. Consult qualified professionals for your specific circumstances.

---

Released under the MIT License. Copyright (c) 2026 DH Robin (dhRobin Systems). See [LICENSE](LICENSE).

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 dhRobin Systems · Provided as-is, see the disclaimer.
