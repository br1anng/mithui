# A little something for you ♡

A small static love-letter website with a chaotic handmade pixel-art style. It has a fake romance-software warning, a letter, a memory timeline, and a pixel-peach timing mini game with a bashful anime celebration. The jokes are intentionally easy to rewrite. Styling is included in the HTML so the page also renders correctly in simple previews. It needs no build step or package installation.

## Site contents

- Personalized for bi dz and Mít Thúi, with 19 photos and 10 transparent cutouts.
- The welcome title-bar buttons create up to eight stacked windows. Either Yes button plays the photo, flower, and heart burst before opening the main page.
- Date roulette gives homestay a 90% chance; theatre, workshop, picnic, and dinner each have 2.5%.
- Boba roulette has 16 equally likely shops. Confirming saves the chosen shop on that browser; it does not send a notification or place an order.
- Secret gift always lands on “100 kisses for bi.” All three spinners can be replayed.
- Coupon redemption is saved in localStorage when available. Photos and decorative assets are embedded in `index.html`, so the standalone preview works without neighboring files.
- Edit the `dateOptions`, `bobaShops`, and `secretGifts` arrays in `index.html` to change options. The secret gift's fixed prize must remain in its array.
- The fonts load from Google Fonts; system monospace and sans-serif fonts are the fallback.

## Open locally

Open `index.html` in a browser. There is no install or build command.

## Free public hosting

This is a static site and can be published free with GitHub Pages. Push the repository to GitHub, then open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save. GitHub will show the public URL on that Pages settings screen. A custom domain is optional and usually costs money.
