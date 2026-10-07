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
1. In Vercel, choose **Add New → Project** and import this GitHub repository.
2. Leave every setting as it is and press **Deploy**. The `vercel.json` at the repo root
   tells Vercel to skip install/build and serve the `hotel-demo` folder as-is.
3. To use the client's domain, open the project's **Settings → Domains** and add it.

(Alternative: set **Root Directory** to `hotel-demo` and **Framework Preset** to *Other*.)
