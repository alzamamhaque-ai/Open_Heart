# Open Heart 💛

> *A safe, anonymous space where you can open your heart. No judgment. No real names. Just honest words and people who understand.*

Powered by **Firebase Firestore** — real-time, shared across all users, persistent forever.

---

## Setup (one time)

### 1. Firestore Security Rules
Go to **Firebase Console → Firestore → Rules tab** and paste the contents of `firestore.rules`. Click **Publish**.

### 2. Host on GitHub Pages
1. Create a GitHub repo (e.g. `open-heart`)
2. Upload `index.html` to the root
3. Go to **Settings → Pages → Source: main branch → Save**
4. Live at: `https://yourusername.github.io/open-heart/`

That's it. No npm, no build step. One file.

---

## How sharing works

| What | Link format |
|---|---|
| Full site | `https://yourusername.github.io/open-heart/` |
| Specific board | `https://yourusername.github.io/open-heart/#board=BOARD_ID` |

Board links are auto-generated. Users copy them from inside the board view.

---

## Firebase features used

- **Firestore** — real-time database, all boards and replies synced live
- **onSnapshot listeners** — new replies appear instantly, no refresh needed
- **subcollections** — each board has its own `replies` collection
- **serverTimestamp** — consistent timestamps across all timezones
- **increment()** — safe concurrent heart/reply counting

---

## Security rules summary (`firestore.rules`)

- Anyone can **read** all boards and replies
- Anyone can **create** boards (with field validation — no empty/spam posts)
- Only `hearts` and `replyCount` fields can be **updated** (stories can't be edited after posting)
- Anyone can **create** replies (with length validation)
- No deletions allowed from the client

---

## Crisis Resources (India)
- **iCall:** 9152987821
- **Vandrevala Foundation:** 1860-2662-345
- **AASRA:** 9820466627

---

*Built with care. For the ones who needed a place to speak.*
