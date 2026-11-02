Isha Health Solutions – Option 2 homepage (static site)

Folder layout (keep exactly like this):
  index.html
  i/            <- all images and icons (54 files). index.html loads them as i/<name>
  vercel.json

GitHub
  1. Create a repo and upload the CONTENTS of this folder to the repo root
     (index.html and the i folder must sit side by side at the top level).
  2. Upload the whole i folder – drag the folder itself, not just index.html.
  3. File names are case-sensitive on GitHub/Vercel: do not rename anything.

Vercel
  1. New Project -> import the repo.
  2. Framework preset: "Other". Build command: (leave empty). Output directory: (leave empty / root).
  3. Deploy.

Check: open https://<your-site>.vercel.app/i/hero1.jpg – it should show a photo.
If it returns 404, the i folder is missing or not at the repo root.
