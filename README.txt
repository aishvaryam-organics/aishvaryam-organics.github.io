AISHVARYAM ORGANICS WEBSITE
===========================

This folder is the whole website. Open index.html in a browser to see it.

BEFORE YOU PUT IT ONLINE (2 edits, both in index.html)

1. Contact details
   Search for "EDIT 2 of 2" near the bottom of index.html and fill in:
     whatsapp:  digits only with country code, e.g. "919876543210"
     phone:     as you want it shown, e.g. "+91 98765 43210"
     email, instagram (handle without @)
   The "Send on WhatsApp" button stays switched off until whatsapp is filled in.

2. Photos
   The five photos in images/ are AI-generated placeholders. While any of them
   is in use, keep class="illustrative" on the <body> tag ("EDIT 1 of 2"): it
   shows a small "Illustrative image" tag on each photo and a line in the footer.
   To use your own photos, replace the files and keep the same names:
     fodder.jpg   + fodder-sm.jpg    landscape, about 1800 px wide / 900 px wide
     gir.jpg      + gir-sm.jpg       portrait 4:5, about 1440 px wide / 640 px wide
     kankrej.jpg  + kankrej-sm.jpg   portrait 4:5
     feed.jpg     + feed-sm.jpg      landscape 3:2
     milking.jpg  + milking-sm.jpg   landscape 3:2
   When every photo is from your own farm, remove the word "illustrative" from
   the <body> tag.

PUTTING IT ONLINE
   It is a static site (no database, no server code). Upload this folder as it is
   to any static host, for example Netlify, Cloudflare Pages or GitHub Pages, and
   point your domain at it. After it is live, add the og:image and canonical
   lines noted near the top of index.html so WhatsApp link previews show a photo.

FONTS
   Rozha One and Anek (Latin, Gujarati) are open-source fonts under the SIL Open
   Font License. The licence texts are in fonts/.
