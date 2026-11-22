JOY BEAUTY SALON — FREE WEB AR STARTER

WHAT THIS IS
A starter web page for image-tracked AR using MindAR + A-Frame. It is designed to recognize the JOY promotional image and show it in the camera view. It is a starter, not yet a published/fully configured AR campaign.

FILES
- index.html: AR webpage
- joy-promo.png: current JOY Beauty Salon promotional design; use this exact image as the tracking card for the first test.

REQUIRED SETUP (FREE)
1. Open the MindAR Target Compiler:
   https://hiukim.github.io/mind-ar-js-doc/tools/compile/
2. Upload joy-promo.png and compile it.
3. Download the generated targets.mind file.
4. Put targets.mind in this same folder beside index.html and joy-promo.png.
5. Test on a phone using an HTTPS host. Camera access will not work from an ordinary file:// open.

FREE HOSTING WITH GITHUB PAGES
1. Create/sign in to a GitHub account.
2. Create a PUBLIC repository named joy-beauty-salon-ar.
3. Upload index.html, joy-promo.png, and targets.mind.
4. In repository Settings > Pages, enable deployment from the main branch and root folder.
5. Wait for the Pages URL, then open it on a phone and allow camera access.
6. Make a QR code that points to that published URL. The QR code printed inside the generated promo art is decorative and is NOT a working QR code.

IMPORTANT
- The phone number, address, and social icons shown in the generated promotional artwork are placeholders. Replace them with verified salon details before printing or advertising.
- This project uses MindAR (open-source) and A-Frame. It needs an internet connection to load the libraries from their CDNs unless you download and host those libraries yourself.
- Image tracking works best with a sharp, matte, high-detail print and good lighting. Glossy reflections can reduce tracking reliability.
- This starter displays the promotional artwork as a tracked plane. A custom animated 3D stylist/avatar and real booking/social links are the next customization step.
