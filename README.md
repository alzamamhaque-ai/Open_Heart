# Open Heart 💛

> *A safe, anonymous space where you can open your heart. No judgment. No real names. Just honest words and people who understand.*

A single-file web app for emotional expression and anonymous support. Built for humans, not profiles.

---

## Features

- **Anonymous boards** — Share your story with a chosen anonymous name. No account, no email.
- **Persistent storage** — All stories and replies are saved in `localStorage`. Refresh won't erase anything.
- **Shareable links** — Every board has a unique link (`#board=id`). Share a specific story OR the full site.
- **Reply threads** — Anyone with the link can reply anonymously and support the original poster.
- **Heart reactions** — Show support silently with a heart tap.
- **Tag filtering** — Filter boards by emotion: Grief, Anxiety, Loneliness, Anger, Relationship, Loss, Just Venting.
- **Responsive** — Works on mobile and desktop.

---

## Hosting on GitHub Pages

1. Create a new GitHub repository (e.g. `open-heart`)
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages**
4. Set source to `main` branch, `/ (root)` folder
5. Click **Save** — your site will be live at:
   `https://yourusername.github.io/open-heart/`

That's it. Single file. Zero dependencies. Zero backend.

---

## Sharing

- **Full site link:** `https://yourusername.github.io/open-heart/`
- **Specific board link:** `https://yourusername.github.io/open-heart/#board=BOARD_ID`

Board links are auto-generated when a user creates a board. They can copy the link from inside the board view.

---

## Important Note

Data is stored in the **visitor's own browser** (localStorage). This means:
- Each device/browser has its own set of boards
- If you want a shared community space (all users see all boards), you'll need a backend (Firebase, Supabase, etc.) in a future version

For now, this works perfectly as a shareable personal space — share the link and let people read and reply.

---

## Crisis Resources (India)
- **iCall:** 9152987821
- **Vandrevala Foundation:** 1860-2662-345
- **AASRA:** 9820466627

---

*Built with care. For the ones who needed a place to speak.*
