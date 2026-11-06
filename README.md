# EST Internship Hub

View-only website listing partner companies and internship vacancies for EST (Eco Socio Tech School) students.

The whole site is one file: `index.html`. No build step, no login, no server.

## Put it online with GitHub Pages (free)

1. Sign in at github.com and click **New repository**. Name it, for example, `internship-hub`. Set it to **Public** (free Pages needs a public repository).
2. Click **uploading an existing file** and drag in `index.html`, `.nojekyll` and `README.md`. Click **Commit changes**.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. Wait 1–2 minutes. The site will be at `https://YOUR-USERNAME.github.io/internship-hub/`.

## Update the companies

Open `index.html` on GitHub, click the pencil icon, and edit the `COMPANIES` list at the top of the file.

- `quota` = total places, `filled` = places taken. "Places left" is calculated automatically.
- To add a company, copy one block and give it a new unique `id`.
- To remove a company, delete its block.
- Grade 10 dates are in `SETTINGS` at the very top.
- Click **Commit changes**. The site updates in about a minute.

## Use your own address (optional)

In **Settings → Pages → Custom domain**, enter a subdomain such as `internship.yourschool.sch.id`, then ask your IT person to add a CNAME record pointing to `YOUR-USERNAME.github.io`.
