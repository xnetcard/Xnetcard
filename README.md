# Editable College ID Card Generator

This small web app lets users edit **every** field that appears on the student ID card:
- College name, registration number, address, phone, website, session
- Logo and principal signature (upload images)
- Admission number (auto-generate or edit manually)
- Student name, DOB, father's name, address, mobile, photo

## How to use
1. Open `index.html` in a browser.
2. Fill student + college details on the left.
3. Upload photo/logo/signature if available.
4. Click **Preview ID Card** to update the card on the right.
5. Download as PNG / PDF or print.

## Files
- `index.html` — main single-file app (uses tailwind + html2canvas + jsPDF via CDN)
- `styles.css` — card styles
