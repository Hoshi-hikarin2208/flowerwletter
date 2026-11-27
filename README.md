# The Whole Life of a Flower

A glowing flower that sprouts, blooms, wilts and is reborn, with butterflies. Plain HTML, CSS and JavaScript in one file, no libraries.

## Features
- Pink, red, violet, magenta or any custom color
- 22 flowers with picture icons, from Dahlia and Rose to Water Lily and Carnation
- Growth sequence: falling seed, sprout, unfurling leaves, bud and sepals, bloom
- Layered grass that sways and bends away from your pointer
- 5 bloom styles: Gentle, Spiral, Burst, Breathing, Wave
- 4 skies: Aurora, Moonlit, Galaxy, Twilight, with meadow grass and fireflies
- Dice button for a random mix
- Bouquet: up to 5 flowers together, each with its own type and color
- 112 ready-made messages for cards, sorted by mood (including Tagalog)
- Timeline slider to jump to any stage
- Butterflies (can be turned off)
- Tap or click the scene for sparkles
- Full-screen layout for phones and desktops
- Keys: `Space` pause, `R` restart, `H` hide controls, `←` `→` change flower, `S` surprise, `F` full screen
- Effects get lighter automatically on slower devices

## Flower cards
Pick a flower, color, bloom and sky, press **Send as a card**, write your message and press **Create card**.

| You want | Do this |
|---|---|
| A quick link, no music | Copy the link and send it |
| Music, or a page of its own | **Download card page**, upload the `card-….html` file to your repository (for example in a `cards/` folder), then send `https://<username>.github.io/<repository>/cards/card-….html` |

## Privacy and security
- No server, database, analytics, cookies or external files. A Content Security Policy blocks the page from making network requests of its own.
- Optional password: the card is encrypted in your browser (AES-256-GCM, key from PBKDF2-SHA256, 600,000 rounds). Without a password, anyone with the link or file can read it.
- A password protects only as well as it is hard to guess. Use a long one and send it separately.
- Card text is displayed as plain text, never as HTML.
- A card file uploaded to a public repository can be seen by anyone, and stays in the Git history after you delete it. Always lock personal cards.
- The host (GitHub Pages) can still see ordinary visit data such as IP addresses. Links are also kept in browser history.
- Your last flower, color and sky are remembered in your own browser only.
- Only share music you have the right to share.

## Run
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a repository and upload `index.html` and `README.md`.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then `main` and `/ (root)`, and save.
4. After a minute or two the site is at `https://<username>.github.io/<repository>/`.
