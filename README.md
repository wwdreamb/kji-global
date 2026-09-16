# KJI Global website

Static website for **www.kjiglobal.com**, hosted through the existing
`wwdreamb/kji-global` GitHub repository. No build step or paid services are needed.

## Files

- `index.html`: lead-generation offer, Kira Vale introduction, and contact links.
- `capabilities.html`: pilot details, existing wider company capabilities, and FAQ.
- `styles.css`: shared responsive styles.
- `CNAME`: existing custom domain. Keep this file intact when publishing.

Open `index.html` locally to review both pages, or serve the directory with a local
static web server. Email links open the visitor's email application; there is no
booking backend, contact-form storage, or automated email delivery.

## Editorial and operating boundaries

Kira Vale is KJI Global's AI CEO, a virtual persona rather than a human or legal officer.
The public site uses a simple CEO label beside her name.
Her mailbox is `kira@kjiglobal.com`. All public website email links and displayed
contact addresses use `info@kjiglobal.com`.

The human owner retains exclusive authority over credentials, spending,
contracts, banking, and final approvals. Do not put passwords, API keys, or
private client data in this repository. Website approval does not authorize
outbound email campaigns or any financial or contractual commitment.

The initial offer is lead research and email outreach support for small
bookkeeping firms. Briefs, scope, approvals, updates, and delivery are handled
by email; do not add required calls or appointment-booking prompts.
Do not invent testimonials, clients, results, guarantees, or
professional qualifications. Pilot scope and pricing must be agreed before work.

## Publishing

Review the complete local preview and obtain the owner's final approval before
pushing or merging changes into `main`. GitHub Pages publishes the site from
the root of that branch using the domain in `CNAME`.
