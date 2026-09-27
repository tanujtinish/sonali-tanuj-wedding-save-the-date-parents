Sonali & Tanuj — Save the Date
================================

WHAT TO UPLOAD
  index.html                     <- the site (shows 4th & 5th December)
  music/ishq-hai-o-rangrez.mp3   <- the music (must keep this folder name)
  5-dec-only.html                <- optional: same site, 5th December only

Keep index.html and the music/ folder side by side. Everything else
(artwork, fonts, map) is already inside index.html.

If you want the 5-Dec-only version to be the main site, delete index.html
and rename 5-dec-only.html to index.html.

HOSTING - GitHub Pages (free)
  1. github.com -> New repository -> name it, Public -> Create.
  2. "uploading an existing file" -> drag index.html and the music folder.
     Commit.
  3. Settings -> Pages -> Source: "Deploy from a branch",
     Branch: main / (root) -> Save.
  4. Two minutes later it is live at
     https://<your-username>.github.io/<repo-name>/
  5. Your own domain: Settings -> Pages -> Custom domain -> type it -> Save.
     Then at your domain registrar add:
       CNAME   www   <your-username>.github.io
       A       @     185.199.108.153
       A       @     185.199.109.153
       A       @     185.199.110.153
       A       @     185.199.111.153
     Tick "Enforce HTTPS" once it turns on (can take an hour).

EVEN SIMPLER - Netlify Drop
  app.netlify.com/drop -> drag this whole folder in -> live instantly.
  Then Domain settings -> Add custom domain.

ALREADY HAVE HOSTING (GoDaddy, Hostinger, cPanel...)
  Upload index.html and the music folder into public_html / www.
