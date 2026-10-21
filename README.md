# Gregory Polo – Portfolio Website

## Put it online with GitHub Pages (free, about 10 minutes)

1. Sign in at https://github.com (create a free account if you need one).
2. Click **+** (top right) → **New repository**.
   - Name it exactly: `YOUR-USERNAME.github.io` (use your real GitHub username).
   - Set it to **Public**, then click **Create repository**.
3. On the new repo page, click **uploading an existing file**.
   Drag in everything from this folder: `index.html`, `Gregory-Polo-Resume.pdf`,
   `README.md`, and the whole `images` folder. Click **Commit changes**.
4. Go to **Settings** → **Pages**. Under "Build and deployment", set
   Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**. Click **Save**.
5. Wait 1–2 minutes, then visit `https://YOUR-USERNAME.github.io`.

## What is already filled in
- Every section is written from your resume, CPU lab, pendulum lab, and chemistry report,
  with the numbers from those documents.
- Photos already on the site: your headshot, the FPGA board photo and Quartus schematic
  (CPU project), and the lab bench photo and results chart (caffeine project).
- A section hides itself if its photo is missing, so nothing looks broken.

## Add more photos (optional)
Upload a file with the exact name into the `images` folder and it appears automatically.
See `images/README.txt` for the names. A good first addition is `game-1.jpg`
(a screenshot of the cybersecurity game).

## Edit the text
Open `index.html` on GitHub, click the pencil icon, and use Ctrl+F to find the words you
want to change. Colors are listed at the top of the `<style>` section.

## Update the resume
The "Download my resume" section offers your basic resume as a PDF.
Upload a new PDF named exactly `Gregory-Polo-Resume.pdf` (it replaces the old one), and also
replace `images/resume-preview.jpg` with a picture of page 1 so the preview matches.
The PDF on this site has the phone number removed on purpose, since the site is public.

## Notes
- Your phone number is intentionally left off the site. Email and LinkedIn are enough.
- Don't post photos of campers. Only post summit photos you have permission to share.
- Check your course policies before posting class code (like the CPU's VHDL) publicly.
- The CPU photo and schematic come from your Lab 11 report. They don't include the
  instructor's markings or initials.
