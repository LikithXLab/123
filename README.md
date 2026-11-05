# Griha Pravesha Invitation Website

Static site: no build step. Edit the `CONFIG` block at the top of `index.html`
(names, date, time, address, program, WhatsApp number) and you're done.

Optional: add `assets/couple.jpg` (hero photo) and `assets/music.mp3` (background music).

## Deploy: GitHub + Vercel
1. Create a new repo on github.com (e.g. `our-housewarming`) and upload these files
   (drag & drop works on the repo page: "Add file > Upload files").
2. Go to vercel.com > "Add New... > Project" > sign in with GitHub > import the repo.
3. Framework preset: **Other**. Leave build command and output directory empty. Click **Deploy**.
4. You get a link like `https://our-housewarming.vercel.app`. Send it on WhatsApp.
5. To change anything later: edit `index.html` on GitHub and commit. Vercel redeploys in ~30 seconds.
