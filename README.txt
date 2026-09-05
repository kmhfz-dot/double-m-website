DOUBLE M WEBSITE V2
===================

FILES TO COPY INTO YOUR EXISTING GITHUB REPOSITORY:
- index.html
- favicon.svg
- company-profile.pdf
- images/   (copy the whole folder)

DO NOT DELETE .gitattributes FROM YOUR EXISTING REPOSITORY.

GITHUB DESKTOP UPDATE
1. Extract double-m-v2.zip.
2. Open GitHub Desktop and select the double-m-website repository.
3. Repository > Show in Explorer.
4. Copy index.html, favicon.svg, company-profile.pdf and the full images folder into that exact repository folder.
5. Choose Replace when Windows asks about existing files.
6. Return to GitHub Desktop.
7. Summary: Double M professional V2
8. Commit to main.
9. Push origin.
10. Wait around one minute and hard-refresh the GitHub Pages site (Ctrl+F5).

IMPORTANT REAL COMPANY DETAILS
Open index.html in Notepad and search for:
    const SITE_CONFIG={

Replace these fields with the real details:
- phoneDisplay
- phoneDigits
- email
- whatsappDigits
- instagram
- linkedin

Example formatting only:
    phoneDisplay: '+974 1234 5678'
    phoneDigits: '97412345678'
    whatsappDigits: '97412345678'

The floating WhatsApp button and enquiry form will automatically become active after whatsappDigits is filled in.

REAL-DATA SECTIONS
The site deliberately does NOT invent:
- client testimonials
- supplier/client relationships
- certifications
- employee names
- project counts
- years of experience

The layout for team, credibility, credentials and project case studies is already built. Replace the honest placeholders with verified company information when available.

CUSTOM DOMAIN
Do not add a CNAME file until you have actually purchased/selected a domain.
When ready: GitHub repository > Settings > Pages > Custom domain, enter the real domain and follow GitHub's DNS instructions.

360 VIEWER
The 360 viewer uses Pannellum from a CDN. Test the interactive tour on the live GitHub Pages website with internet access.

COMPANY PROFILE
company-profile.pdf is linked from the website and can be downloaded by visitors. It also uses concept imagery and sample contact details until the real company information is supplied.
