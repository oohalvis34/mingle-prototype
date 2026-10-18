# Mingle

**See who's around you. Shoot your shot before they're gone.**

Mingle is a proximity-based dating app concept for Singapore. You spot someone you like on the MRT, at a café or at a gig, but walking up to them feels too awkward and too risky. Mingle lets you see their profile and send a request while you're both still there.

This repository holds a **clickable prototype** of the app. It runs entirely in the browser, so testers can try the full flow on their phone without installing anything.

> **Prototype only.** Every profile is fictional. Singpass verification, payments and ads are simulated, and no data leaves your device.

## Try it

Open the live link on your phone and tap **Get started**.

- Live link: *add your Vercel URL here once it's deployed*

## What you can try

1. **Onboarding:** verify with Singpass (simulated), set up your profile, pick your blob avatar and choose your vibes.
2. **Location and home:** set a home spot, where your visibility turns off automatically.
3. **Discover who's nearby:** a radar-style map and a list view, plus scenes for the MRT, a concert and OurSpace@72.
4. **Send a request:** view a profile with what you align and clash on, choose a gift, and wait through the ad (free plan).
5. **Get connected and chat:** once they accept, you're connected and can start chatting.
6. **Receive a request:** see what it's like when someone nearby sends you one.
7. **Plan a date:** browse date spots on Mingle Maps and plan the date in chat.
8. **Safety and Premium:** report or block someone, and see what Premium unlocks.

## Feedback we're looking for

- Does seeing who's nearby feel **exciting or creepy**? We especially want to hear from women testers.
- Is the 20-second ad before a request annoying enough to make you consider Premium?
- Which screen confused you, or where did you get stuck?

## How it's built

The whole prototype is a single self-contained file, `index.html`, with no build step and no dependencies to install. Fonts load from Google Fonts. Everything else, including the illustrations, is embedded in the file.

The screens are based on the **Mingle iPhone Journey** design in Claude Design, using the Mingle design system (the mochi and bubble mascots).

## Deploying

The site is static, so any static host works.

**Vercel:** import this repository at [vercel.com/new](https://vercel.com/new), keep the defaults (Framework: Other, no build command) and click **Deploy**. Every push to `main` updates the live link.

**Run it locally:** download `index.html` and open it in a browser.

## Team

Built by the TWC Startup team.
