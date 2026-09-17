THE SMILE HUB — WEBSITE FILES
=============================

FILES
  index.html        Homepage — fully responsive (desktop, tablet, mobile)
  thank-you.html    Post-submit confirmation page
  assets/           Images, logos and testimonial videos
  support.js        Required runtime — must stay beside the HTML files
  image-slot.js     Image placeholder helper
  send-enquiry.php  Optional PHP email handler + reCAPTCHA verification

UPLOAD
  Upload the contents of this folder to the web root, keeping the structure
  intact (assets/ must stay a subfolder next to the HTML files).

RESPONSIVE
  index.html adapts at every width — no separate mobile file.
  On phones: hamburger drawer nav, portrait hero with overlaid copy,
  25px headings, 14px body text, treatments accordion, swipeable sliders,
  stacked doctor cards, and a sticky Call / WhatsApp / Book bar.

FORMS
  All three forms (footer, appointment modal, welcome popup) send to:
    1. the Pabbly webhook
    2. growthpixelagency@gmail.com
  then redirect to thank-you.html.
  To email from your own server instead, change each form's action to
  "send-enquiry.php".

reCAPTCHA v3
  Site key is embedded in index.html; the secret lives only in
  send-enquiry.php. Add the live domain in the reCAPTCHA admin console,
  or tokens will fail once deployed. The floating badge is hidden and
  replaced with the required inline "Protected by reCAPTCHA" notice.

DETAILS USED
  Phone / WhatsApp : +91 93723 03602
  Location link    : https://share.google/ugMBNsXz9sVdPpDHz
  Enquiry inbox    : growthpixelagency@gmail.com
