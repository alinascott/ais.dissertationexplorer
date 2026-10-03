# Adding images to the gallery

The "Selected Event" panel includes a Gallery next to it — a rotating slideshow
of images. For now, this isn't tied to any specific event; it's one shared pool
of images that rotates on every page load, regardless of which event, chapter,
or view you're looking at. (We can connect specific photos to specific events or
people later — this is just step one.)

You don't need to edit any code or JSON to add images — just upload files to the
right folder with the right names.

## 1. Prepare your images

- Convert each image to **.jpg** format (the site only looks for `.jpg` files).
- Name them **1.jpg, 2.jpg, 3.jpg**, and so on, in order, starting at 1 with no
  gaps. (If you have 3 images, name them 1.jpg, 2.jpg, 3.jpg — not 1.jpg, 3.jpg,
  5.jpg — the site stops looking at the first missing number.)
- Keep file sizes reasonably small (under ~1 MB each) so the page loads quickly.
  Most phone photos and archival scans will need to be resized or compressed
  first.
- If an image comes from an archive or museum collection (e.g. NMAI), keep a
  separate note somewhere of its catalog number and credit line — once it's
  renamed to "1.jpg" that information isn't preserved on the site itself. (Ask
  if you'd like captions/credits added to the gallery later — not built yet.)

## 2. Upload them to the repo on GitHub.com

1. Go to your repository on github.com (`alinascott/ais.dissertationexplorer`).
2. Click **Add file → Upload files**.
3. Near the top of the upload page, there's an editable path showing where the
   files will go (it starts as just the repo name). Click into it and type:

       images/gallery

   then press Enter. This creates the folder for you the first time — it
   doesn't need to exist beforehand.
4. Drag your renamed images (1.jpg, 2.jpg, …) into the upload box.
5. Scroll down and click **Commit changes**.

A minute or two after GitHub Pages rebuilds, refresh the site and the gallery
will appear in place of "No images yet," showing your images in a random order
with a small slideshow (hover over it for arrows and dots; it also auto-advances
every few seconds).

## Adding more images later

Go back to **Add file → Upload files**, navigate into the existing `images/gallery`
folder first (so you don't retype the path), and add new files continuing the
numbering where you left off (e.g. if you already have 1.jpg–5.jpg, add 6.jpg,
7.jpg, …).

## Notes

- There's no limit the site enforces, but it only checks up to 40 images, so
  that's the practical ceiling for now.
- If you make a mistake (skipped a number), just delete or rename the file in
  GitHub so the numbering has no gaps again.
