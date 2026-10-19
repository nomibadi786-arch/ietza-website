# IETZA Official Website

Static website for the Islamic Educational Trust of Zambia (IETZA), Great East Road, Lusaka. It uses plain HTML, CSS and JavaScript only, so it runs free on GitHub Pages.

## Pages
| File | Page |
|---|---|
| index.html | Home |
| about.html | About IETZA |
| madrassa.html | Madrassa Rahmaniyyah |
| primary-school.html | IETZA Primary School |
| darul-mufazamia.html | Darul Mufazamia |
| masjid-e-luqman.html | Masjid-e-Luqman |
| admissions-2027.html | Admissions 2027 |
| gallery.html | Gallery |
| contact.html | Contact Us |

## Folders
- css/style.css: colours, fonts and layout
- js/main.js: mobile menu
- js/gallery.js: gallery photo list (edit this to add photos)
- assets/images/ietza-logo.jpg: official logo
- assets/images/masjid-e-luqman.jpg: mosque photo

## Publishing on GitHub Pages
1. Create a free account at https://github.com and sign in.
2. Click the + at the top right, then New repository. Name it ietza-website, set it to Public, and click Create repository.
3. Click "uploading an existing file" (or Add file, then Upload files). Drag in all files and folders from the ietza-website folder, keeping the structure. Click Commit changes.
4. Click Settings, then Pages in the left menu.
5. Under Build and deployment, set Source to "Deploy from a branch". Set Branch to main and the folder to / (root), then click Save.
6. Wait 1 to 2 minutes and refresh the Pages screen. The live address appears as https://nomibadi786-arch.github.io/ietza-website/
7. Open that address and test every page, the menu, the Register Now buttons and the WhatsApp and phone links.
8. Replace nomibadi786-arch in sitemap.xml and robots.txt with your GitHub username, then upload those two files again.

## Gallery
Open js/gallery.js. Each line is one gallery slot. Save the photo in assets/images/, then set src, alt and caption for that line. Lines with src "" show a placeholder. Upload the photo and the edited js/gallery.js to GitHub.

## Items to confirm before publishing
Search the files for PLEASE CONFIRM, HISTORICAL and PHOTO PLACEHOLDER:
- IETZA founding date, registration status, accreditation, leadership, and official mission statement
- Description of IETZA Primary School and Darul Mufazamia, plus their programmes, fees, requirements, hours and accommodation
- Masjid-e-Luqman association with IETZA, address, history, capacity, facilities, services, prayer times
- Madrassa Rahmaniyyah timeline entries, programme descriptions and enrolment figures with reporting date
- Admission requirements, deadlines and fees
- Map coordinates and social media links
- Whether WhatsApp is active on +260 979 284 412 (the WhatsApp buttons use this number)
- Claim about Zambia's oldest Islamic institution: [HISTORICAL CLAIM TO VERIFY]

## Changing the registration link
Search all files for tally.so and replace the address. The link is used in every Register Now button.

## Security
No passwords, API keys or private credentials are included.
