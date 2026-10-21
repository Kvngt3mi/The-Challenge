# Challenge tracker

A view-only performance page for the trading challenge, with a hidden admin mode for adding trades.

## Put it online (GitHub Pages)

1. Create a free account at github.com and click **New repository**. Name it, for example, `challenge`, and set it to **Public**.
2. On the new repository, click **Add file**, then **Upload files**. Drag in `index.html`, `data.json` and `README.md`, then click **Commit changes**.
3. Open **Settings**, then **Pages**. Under **Build and deployment**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/challenge/`. Send that link to your friends.

## Add trades (admin)

1. On your own phone or laptop, open your site address followed by `#admin`, for example `https://YOUR-USERNAME.github.io/challenge/#admin`. Do this once per device. The **Add trades** and **Settings** tabs then appear for you only.
2. Under **Settings**, enter the challenge rules, start date and length.
3. Under **Add trades**, enter the day's trades. Chart screenshots are optional.
4. A bar appears at the top saying you have changes that are not live yet. Tap **Download data.json**.
5. In your GitHub repository click **Add file**, then **Upload files**, drop in the new `data.json` (it replaces the old one), and click **Commit changes**. The live site updates in about a minute.

## Good to know

- Your unpublished changes are saved as a draft in your own browser. The backup box under **Add trades** gives you a copy you can store elsewhere.
- Friends cannot change anything. The admin tabs are only shown on your device, and the live data only changes when someone with access to your repository uploads a new `data.json`.
- Anyone with the link can read `data.json`, so don't put anything private in the trade notes.
- Chart screenshots are stored inside `data.json`, so keep them to a few per day to keep the file small.
- Sharing the daily and overall report cards as JPEG, PDF and PNG works the same as before. The AI caption button is not included in this version, but you can still type your own caption.
