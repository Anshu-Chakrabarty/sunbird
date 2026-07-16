SUNBIRDS RV RESORT & VILLAGE — Coming Soon site
================================================

FILES (keep them together)
  index.html            the website
  sunbirds-logo.png     main logo (used in the hero)
  sunbirds-wordmark.png  wordmark (used in the footer)

HOW TO HOST ON VERCEL
  Option A — drag & drop (easiest):
    1. Go to https://vercel.com  ->  Add New  ->  Project.
    2. When it asks for a repo, choose "deploy without Git" / or use the
       Vercel CLI. Simplest: install the Vercel CLI and run  `vercel`
       from inside this unzipped folder, then follow the prompts.
  Option B — GitHub:
    1. Put these files in a GitHub repo (root level).
    2. In Vercel: Add New -> Project -> import that repo -> Deploy.
    No build settings needed — it's a plain static site.

SIGNUP EMAILS
  Every signup is emailed to: anshu@brandmirchi.com
  The FIRST time someone submits the form on your live site, FormSubmit
  sends anshu@brandmirchi.com a one-time "Activate" email. Click that link
  once. After that, every signup is delivered automatically — no dashboard,
  no login, nothing else to manage.

  To change the recipient later, open index.html, find:
     var NOTIFY_ENDPOINT = "https://formsubmit.co/ajax/anshu@brandmirchi.com";
  and replace the email at the end.

CONTACT LINKS
  The "Email us" buttons and footer link point to:
     sunbirdsrvresortvillage@gmail.com

FACEBOOK
  In index.html, find  https://www.facebook.com/  and replace it with your
  real page URL.
