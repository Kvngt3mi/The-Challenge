# Challenge platform

A view-only performance site for trading challenges, with a password-protected admin mode. One site can hold several challenges of three types:

- **Prop firm with phases:** you choose how many phases must be passed (1 to 4). Each phase has its own profit target, loss limits and minimum trading days, followed by the funded account.
- **Prop firm, instant funded:** no phases. A funded account from day one with loss limits, a profit split and a payout target.
- **Broker account:** a plain account with a profit goal and optional loss limits.

## Put it online (GitHub Pages)

1. Create a free account at github.com and click **New repository**. Set it to **Public**.
2. Click **Add file**, then **Upload files**. Drag in `index.html`, `data.json` and `README.md`, then click **Commit changes**.
3. Open **Settings**, then **Pages**. Set the source to **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

If your site already has trades in it, upload only `index.html`. Do not replace your existing `data.json`. The new page converts your old data automatically the first time you open it as admin.

## Admin

1. Open your site address followed by `#admin`. If you set a password, enter it.
2. In **Challenges**, create a challenge: pick the type, the number of phases if it has them, and the account size. Then open **Settings** and match the rules to your prop firm or broker.
3. In **Add trades**, enter each day's trades. Chart screenshots are optional.
4. In a phases challenge, a green bar appears when the phase target is reached. Press **Pass phase** to start the next stage with a fresh account. The old phase's trades stay in the record.
5. Tap **Download data.json** when the bar at the top appears, then upload it to your repository (**Add file, Upload files**) to replace the old one. The live site updates in about a minute.
6. Set an admin password in the **Challenges** tab, then download and upload `data.json` so it takes effect.

## Good to know

- Your unpublished changes are kept as a draft in your own browser. The backup box under **Add trades** gives you a copy of everything to store elsewhere.
- Friends cannot change anything. The admin password is checked in the browser, so it keeps casual visitors out, but the real lock is your GitHub account.
- `data.json` is public, so keep private details out of trade notes.
- If a phase or the account breaks its loss limit, the page shows a red banner. Open **Challenges** to create a new attempt.
- Share cards (JPEG, PDF and PNG) work for every challenge and show the phase name.
