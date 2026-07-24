LITURGY OF OURS — BRAND FONTS
=============================

The brand guide specifies five type roles:

  Headlines .......... Sainte Colombe Light   (licensed)
  Subheadlines ....... Sweet Sans Pro Medium  (licensed)
  Body copy .......... EB Garamond Regular     (free — loaded from Google Fonts)
  Italic accents ..... EB Garamond SemiBold Italic (free — loaded from Google Fonts)
  Script accents ..... Pink Champagne Regular  (licensed)

WHAT THE PAGE DOES NOW
----------------------
- EB Garamond (body + italic accents) loads for everyone via Google Fonts.
- Sainte Colombe, Sweet Sans Pro, and Pink Champagne render automatically for
  any viewer who has the licensed fonts installed on their machine.
- Anyone WITHOUT the licensed fonts sees close web-font stand-ins:
      Sainte Colombe -> Cormorant Garamond (Light)
      Sweet Sans Pro -> Montserrat (Medium)
      Pink Champagne -> Ms Madi

TO MAKE THE LICENSED FONTS RENDER FOR EVERYONE (self-hosting)
------------------------------------------------------------
1. Export/convert each licensed font to .woff2 and place the files here:
      assets/fonts/SainteColombe-Light.woff2
      assets/fonts/SweetSansPro-Medium.woff2
      assets/fonts/PinkChampagne.woff2
2. In styles.css, find the three @font-face blocks at the top and uncomment
   the url() line inside each (remove the /* and */ around it).
3. Confirm your license permits web embedding/self-hosting before deploying.

Font file names in the CSS can be changed to match whatever you export.
