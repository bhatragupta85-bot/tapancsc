TAPANCSC - Common Service Centre website

Files
  index.html   The complete website (HTML, CSS and JavaScript in one file)
  hero.mp4     The hero section video
  poster.jpg   Still image shown while the video loads
  Keep all three files in the same folder.

How to use
  1. Unzip this folder.
  2. Double-click index.html to open it in your browser.
  3. To put it online, upload all three files to any static host
     (Netlify, GitHub Pages, Cloudflare Pages, or your hosting's public_html folder).

How to edit
  Open index.html in any text editor.
  - Phone, address and opening hours: search for "var CFG" near the bottom
    and change the values. Phone format: country code + number, no plus sign
    (example: 917077111403). Add hours like: hours: "Mon-Sat, 9 am - 7 pm"
  - Services list: search for "var S = [" and edit, add or remove rows.
    Each row is: category, name, Hindi name, description, documents to bring.
  - Hero video: replace hero.mp4 with your own clip (same file name),
    ideally a short, muted, under 5 MB MP4.
  - Colours: search for ":root{" at the top of the style section.

Note: fonts load from Google Fonts, so they need an internet connection.
