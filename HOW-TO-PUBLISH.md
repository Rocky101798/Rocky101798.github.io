# How to publish your portfolio (free)

Your whole website is one file: `index.html`. It has no build step and no installs. You upload that one file and the site is live.

---

## Option A: GitHub Pages (recommended, free forever)

Your site will live at **https://rocky101798.github.io**

1. Sign in to https://github.com (account: Rocky101798).
2. Click **+** (top right) → **New repository**.
3. Repository name: **`Rocky101798.github.io`** (exactly this, so it becomes your main site address).
   - Set it to **Public**.
   - Click **Create repository**.
4. On the new repo page, click **"uploading an existing file"**.
5. Drag `index.html` from `C:\Users\BARCONATIONWRW\Cluade Work\portfolio\` into the browser, then click **Commit changes**.
6. Go to **Settings** → **Pages** (left menu).
   - Under **Build and deployment → Source**, choose **Deploy from a branch**.
   - Branch: **main**, folder: **/ (root)** → **Save**.
7. Wait 1–2 minutes, refresh the Pages settings screen, and you'll see "Your site is live at https://rocky101798.github.io".

## Option B: Netlify Drop (fastest, about 30 seconds)

1. Go to https://app.netlify.com/drop
2. Drag the whole **`portfolio`** folder onto the page.
3. You get a live link immediately. Create a free account to keep it, then rename it in **Site configuration → Change site name**, e.g. `godfrey-moyo.netlify.app`.

## Option C: Vercel (your CV already lists siphamandlamoyo.vercel.app)

1. Do Option A steps 1–5 first (the code needs to be on GitHub).
2. Go to https://vercel.com → sign in with GitHub → **Add New → Project**.
3. Import the repo → leave all settings as default → **Deploy**.
4. To use the `siphamandlamoyo.vercel.app` address: if that project already exists in your Vercel account, open it → **Settings → Git** and connect it to this new repo instead.

---

## How to make changes later

**On GitHub (no software needed):**
1. Open your repo → click `index.html` → click the ✏️ pencil icon.
2. Press **Ctrl+F** to find the text you want to change (e.g. a job title or project description) and edit it.
3. Click **Commit changes**. The live site updates within about a minute.

**Common edits:**
| To change… | Search the file for… |
|---|---|
| Mark AWS Solutions Architect as done | `In Progress`: change `status prog` to `status done` and the text to `✓ Certified`, delete the `<div class="progress">…</div>` line, and remove the hero badge that starts with `Currently completing` |
| Add a project | Copy a whole `<article class="glass hover proj …">` … `</article>` block, paste it below, and edit the text and link |
| Add a new job | Copy a `<div class="glass job …">` block in the Experience section |
| Colours | The `--cyan`, `--violet`, `--magenta`, `--amber` values near the top |

**Or ask Claude:** open this folder again and say what you want changed. Then re-upload `index.html` (GitHub → repo → **Add file → Upload files** → drag it in → Commit).

---

## After it's live
- Add the link to your **LinkedIn** (Intro → Website), your **GitHub profile** (Edit profile → Website), and your **CV** header.
- Test it on your phone.
- Paste the link into a LinkedIn post to check the preview card shows your name and tagline.
- Optional: buy a custom domain (e.g. `godfreymoyo.co.za`) and connect it under **Settings → Pages → Custom domain** on GitHub.
