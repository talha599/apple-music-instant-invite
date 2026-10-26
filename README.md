# Apple Music – Instant Link Invite (Interactive Prototype)

A simple, AI-assisted, clickable UX prototype created for a Product Owner Trainee assessment. It explores a faster way to invite friends to collaborate on a music playlist.

> **Disclaimer:** This is an independent student concept, not an official Apple Music product and not affiliated with Apple. It uses sample data and does not connect to Apple Music or provide real multi-device synchronization.

## The problem

Collaborative playlist setup can involve unnecessary steps. This concept demonstrates how a one-tap invitation link and a simple sync control could reduce friction in the joining experience.

## Features demonstrated

- Create or name a collaborative playlist.
- Generate a **demo invitation link** and copy it.
- Preview the invitation from a friend's perspective.
- Join the playlist in the simulated flow without manual approval.
- Add songs to a shared playlist in the demo.
- Turn a background Auto Sync **toggle** on or off (UI simulation only).

## How to run locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. No installation, build step, environment variables, or API keys are required.

## Demo walkthrough

1. Enter a playlist name (for example, **Summer Vibes**).
2. Select **Generate instant invite link**.
3. Select **Copy** to demonstrate copying the example link.
4. Switch **Background auto-sync** on or off.
5. Select **Preview friend's invitation**, then **Join playlist instantly**.
6. Open the collaborative playlist, enter a song name, and select **Add to shared playlist**.

## Deploy to Vercel

1. Create a new GitHub repository.
2. Upload `index.html` and `README.md` to the repository **root**.
3. Sign in at [Vercel](https://vercel.com/new) using GitHub.
4. Import the repository.
5. Set **Framework Preset** to **Other**; no build command is required for this static site.
6. Keep **Root Directory** at `./` and deploy.
7. Open the deployed URL in a private/incognito browser window to confirm public access without login.

## Technology

- HTML
- CSS
- Vanilla JavaScript
- No external dependencies

## Important limitations

- The invitation link is an **illustrative placeholder** and is not a working Apple Music invitation. It cannot be used to join a playlist on another device.
- Joining, playlist updates and Auto Sync are simulated in the browser, not backed by a server.
- The prototype is intended to demonstrate a proposed user journey, not production-ready functionality.

## Assessment submission

**Feature:** Instant Link Invite for Apple Music  
**Deliverable:** Interactive prototype demonstrating an easier collaborative playlist experience.
