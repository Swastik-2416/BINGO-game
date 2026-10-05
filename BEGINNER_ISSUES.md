# Beginner-Friendly Issues for Hacktoberfest / Open Source

Here are several beginner-friendly issue descriptions you can create in your GitHub repository to attract new contributors. Feel free to copy and paste these into your GitHub Issues tab, and make sure to add the `good first issue` and `hacktoberfest` labels to them!

---

## Issue 1: Add a "Copy to Clipboard" button for Room Codes
**Title:** Add a "Copy to Clipboard" button next to the Room Code
**Labels:** `good first issue`, `enhancement`, `ui`

**Description:**
Currently, when a user creates a custom room, they are given a 6-letter room code to share with their friends. However, users have to manually highlight and copy the code.

It would be a great quality-of-life improvement to add a small "Copy" icon/button next to the room code that copies the code to the user's clipboard and briefly shows a "Copied!" tooltip or text.

**Where to look:**
- `game.html` (where the room code is displayed)
- You'll need to add a bit of JavaScript using the `navigator.clipboard.writeText()` API.

---

## Issue 2: Expand the Avatar selection
**Title:** Add more emoji avatars to the selection screen
**Labels:** `good first issue`, `enhancement`

**Description:**
The landing screen (`index.html`) currently has a small selection of animal emojis (🦊, 🐯, 🐼, etc.) for the player to choose as their avatar. 

We would like to expand this list to give players more options! 
Please add at least 10 new emojis to the `emojis` array. They don't have to be animals—feel free to add objects, food, or faces!

**Where to look:**
- `index.html` (search for `const emojis = [...]`)
- Make sure the new emojis fit nicely into the `avatar-selector` grid CSS in `style.css` if necessary.

---

## Issue 3: Add background music or sound effects toggle
**Title:** Add a mute toggle button for sound effects
**Labels:** `good first issue`, `feature`, `javascript`

**Description:**
The game currently plays sounds when certain actions occur (e.g., matching a number). Some players might want to play quietly. We should add a "Mute" toggle button (perhaps a speaker icon 🔊 / 🔇) in the header or settings area.

When toggled, it should set a variable (or save to `sessionStorage`/`localStorage`) to disable audio playback in the game.

**Where to look:**
- `game.html` and `index.html`
- Look for any audio `.play()` calls in the JS and wrap them in a check for the mute state.

---

## Issue 4: Improve mobile responsiveness of the landing page
**Title:** Fix landing page padding and margins on mobile devices
**Labels:** `good first issue`, `css`, `ui`

**Description:**
On smaller screens (mobile devices), the landing page cards in `index.html` can sometimes look a bit cramped. The spacing around the "Host Room" and "Join Room" buttons, and the padding of the `.landing-card`, could be improved using CSS media queries.

Task:
- Add a CSS media query in `style.css` for screens smaller than 600px.
- Adjust the padding and gap properties to make it look cleaner and more breathable on mobile.

**Where to look:**
- `style.css`
- `index.html`

---

## Issue 5: Add a "How to Play" modal or section
**Title:** Add a "How to Play" button and instruction modal
**Labels:** `good first issue`, `ui`, `documentation`

**Description:**
New players might not know how the Bingo game works or the difference between the 3 modes (Local, Online, Custom). 

We should add a "How to Play" button on the landing page (`index.html`) that opens a simple modal overlay explaining the rules of the game and how the multiplayer works. 

**Where to look:**
- `index.html` (add the button and the hidden modal div)
- `style.css` (style the modal overlay)
- Add simple Vanilla JS to toggle the modal's visibility.
