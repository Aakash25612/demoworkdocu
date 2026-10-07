# Hotel demo website

A single static page (`index.html`): no build step, no dependencies.

## Edit the details
Open `index.html` and change the `CONFIG` block near the bottom: name, city, address,
phone, WhatsApp number, email, rooms and prices, gallery photos and reviews.
Everything on the page updates from it.

## Photos
Put photos in `images/` and reference them from `CONFIG` (`img` on a room, `src` in `gallery`).
The hero photo is `images/campus.webp`.

## Deploy on Vercel
Live project: `atithi-bhavan-demo` (Root Directory is set to `hotel-demo`).
Every push to the connected branch redeploys automatically.

To set it up again from scratch:
1. In Vercel, choose **Add New → Project** and import this GitHub repository.
2. Set **Root Directory** to `hotel-demo` and **Framework Preset** to *Other*.
   (This matters: the repo root holds an old Rails app whose `package.json` breaks the build.)
3. Press **Deploy**. Add the client's domain under **Settings → Domains**.
