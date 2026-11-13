# Tlhankane Attorneys website

Demo website for Tlhankane Attorneys, Attorneys, Notaries and Conveyancers, Plot 20275, Phase 2, Mfetlhedi Road, Gaborone.

Static site: `index.html` plus `assets/`. No build step, no server code and no secrets.

- 3D Lady Justice: three.js from jsDelivr, model in `assets/model/` (base64 text, decoded in the browser)
- Booking form opens WhatsApp with a pre-filled message; nothing is stored or sent by the site itself
- Fonts: Poppins from Google Fonts

To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.

Built by Neoterra.
