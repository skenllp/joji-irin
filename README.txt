Joji Johnson & Irin Mathew — Wedding Invitation Website
=======================================================

HOW TO USE
----------
1. Keep index.html and the "assets" folder together in the same location —
   the page loads its background photos from assets/.
2. Double-click index.html to preview it in any browser.
3. To publish online, upload this whole folder (index.html + assets/) to any
   static web host (e.g. Netlify, Vercel, GitHub Pages, or your own hosting).
   No build step or server is required — it's plain HTML/CSS/JS.

WHAT'S INSIDE
-------------
index.html                The full site (opening curtain reveal, hero,
                           couple names, save-the-date, engagement, marriage,
                           reception, family, closing).
assets/hero.jpg            Portrait decoration photo used in the hero background.
assets/soft-bg.jpg         Softened/blurred variant used in the closing section.
assets/og-image.jpg        1200x675 preview image used when the link is
                            shared on WhatsApp/social media/iMessage etc.
assets/music.mp3            The wedding song, tap the note icon (bottom-right)
                             to play/pause it — never autoplays.

NOTES
-----
- The couple's names, dates, venues and family details are hard-coded as
  plain HTML text (not baked into images), so you can edit them directly
  in index.html with any text editor if anything needs correcting.
  The only image with text in it is assets/og-image.jpg (the social preview).
- Dates shown: Engagement — 14 November 2026 (Saturday);
  Marriage — 16 November 2026 (Monday). No event times were provided, so none
  are shown. The reception has no separate venue or time; it reads
  "Reception to follow in the respective premises".
- The two "View on Map" buttons open Google Maps searches for the church and
  the auditorium names — no street address was invented. The reception card
  has no map button because it has no venue of its own.
- Social-share preview (Open Graph) tags are set in the <head> of
  index.html, pointing to https://joji-irin.vercel.app/ and
  https://joji-irin.vercel.app/assets/og-image.jpg. If you deploy the site at
  a different URL, update the canonical, og:url, og:image and twitter:image
  values to match.
