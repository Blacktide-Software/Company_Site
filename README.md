# Blacktide Software company site

The public website at https://blacktidesoftware.com. Plain HTML and CSS, no build step and no scripts.

## Pages

| URL | File |
| --- | --- |
| `/` | `public/index.html` |
| `/privacy` | `public/privacy/index.html` |
| `/terms` | `public/terms/index.html` |
| `/thanks` | `public/thanks/index.html` (shown after the contact form is sent) |
| Missing pages | `public/404.html` |

## How it goes live

Netlify watches the `main` branch of this repo. Any change merged into `main` is published automatically, usually within a minute. Settings are in `netlify.toml`.

The Netlify project lives in the Blacktide Software team, signed in with the captain@blacktidesoftware.com Google account.

**Free plan limits:** Netlify's free plan gives 300 credits a month, and each publish uses 15. That's roughly 20 publishes a month, minus whatever traffic uses. Batch small edits into one change instead of publishing each one separately.

## Contact form

The form on the home page uses Netlify Forms (free, unlimited on the current plan). Submissions show up in Netlify under **Forms**. Turn on email notifications to captain@blacktidesoftware.com under **Project configuration > Notifications > Emails and webhooks > Form submission notifications**.

## Still to do

- Add the virtual mailbox street address to the "Contact us" section of the privacy and terms pages once it's set up.
- Have a Florida attorney review the privacy policy and terms.
