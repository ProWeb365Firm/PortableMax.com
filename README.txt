PortableMax - static HTML version
=================================

Upload the CONTENTS of this folder (including the hidden .htaccess file) to the web root of
portablemax.com, or to any subfolder for a staging preview. All links are relative.

All 15 working URLs are unchanged (home, 7 review posts, the reviews, portable-desks,
portable-hot-tub and portable-stands categories, the tag page and the author pages).
Each URL is a folder containing index.html.

Notes
-----
- The site has no contact form. The search box now opens a Google search limited to
  portablemax.com, since WordPress search needs WordPress.
- /best-5-portable-hot-tub-reviews/ is linked on the live site but already returns "not found"
  there (the working post is /the-best-5-portable-hot-tub-reviews/).

Noindex (staging)
-----------------
Every page has <meta name="robots" content="noindex, nofollow" /> and .htaccess sends an
X-Robots-Tag: noindex, nofollow header, so search engines will not index this copy.
BEFORE GOING LIVE on the real domain: remove that meta line from each page and delete the
"BEGIN noindex ... END noindex" block from .htaccess, or the site will drop out of Google.
