# Lanyard

A one-file link-in-bio page. No build step, no dependencies. It shows your avatar, name, typing line, bio, badges, status and links on a customizable card with themes, particle effects and an optional enter screen.

## Put it on GitHub Pages

1. Create a new repository on GitHub and add `index.html` and this `README.md` to it.
2. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
3. After a minute your page is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Make the page yours

1. Open your live page and add `#edit` to the end of the address, for example `https://YOUR-USERNAME.github.io/YOUR-REPO/#edit`.
2. Press **Customize**. Change your name, bio, links, badges, look and effects. Your changes are saved in your own browser while you work.
3. When you like it, open **Backup**, press **Copy profile for publishing**, and paste the result over the JSON inside the `profile-data` block near the bottom of `index.html`.
4. Commit the file. Everyone who opens the page now sees your version.

Visitors never see the editor unless they add `#edit` themselves, and anything they change stays in their own browser.

## What this version does not have

This is a static site, so it has one profile and no accounts. Sign-in, a People list and developer-granted staff badges need a server to store who people are. In this version you choose your own badges, including Staff and Moderator, in **Customize**. To turn it into a multi-person site you would add a backend such as Supabase or Firebase.

Audio files you pick in the editor play on your screen only and are not part of the published page.
