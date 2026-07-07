# Admin setup for Iptv channels

This folder includes an admin-ready setup using Decap CMS.

The admin page will be:

`https://iptv-channels-tv.netlify.app/admin/`

Important: the admin login will not work from a drag-and-drop upload alone. A secure admin needs Netlify connected to a GitHub repository, with Netlify Identity and Git Gateway enabled.

Admin username/email:

`samcharlie974@gmail.com`

Do not place the password inside the website files. The password should be created privately through the Netlify Identity invite email. If you want to start with `IptvChannels`, change it to a stronger private password after the first login.

## Steps

1. Create a GitHub account if you do not already have one.
2. Create a new GitHub repository for this website.
3. Upload these website files to the repository root: `index.html`, `admin`, `content`, and `ADMIN_SETUP.md`.
4. In Netlify, create or reconnect the site from that GitHub repository.
5. In Netlify, go to Identity and click Enable Identity.
6. In Identity settings, set Registration to Invite only.
7. In Services, enable Git Gateway.
8. Invite `samcharlie974@gmail.com` as an Identity user.
9. Open the invite email and create the admin password.
10. Open `/admin/` on your live website and log in.

After that, you can edit the website content from the browser. Changes will save to GitHub and Netlify will redeploy the site automatically.

## What the owner can edit

- Business name and logo tagline
- Hero headline and paragraph
- WhatsApp, Telegram and email
- Prices for all four plans
- Support hours and languages
- Footer legal notice
