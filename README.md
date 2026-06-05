# Dr. Ali Murtaza / SCALAR Labs Academic Website

This repository contains the source for Dr. Ali Murtaza's academic website and SCALAR Labs pages. The code is hosted at https://github.com/ShariqShoaib07/Scalar-Labs.git. It is a static site built with plain HTML, CSS, and JavaScript, so there is no build step or package installation required.

The site currently includes:

- A homepage with bio, experience, contact details, and selected publications.
- Dedicated sections and pages for publications, projects, videos, and lab information.
- Supporting content under `data/`, `images/`, `lab/`, `projects/`, `publications/`, `students/`, and `videos/`.

## Repository Structure

- `index.html` - main homepage.
- `css/` - shared styling.
- `data/` - site data used by the pages.
- `images/` - profile, publication, and asset images.
- `lab/`, `projects/`, `publications/`, `students/`, `videos/` - section pages.
- `CNAME` - custom domain configuration for GitHub Pages.

## Run Locally

Use any static file server. The quickest option is Python 3:

```powershell
Set-Location -Path 'D:\web2.0\ali-murtaza-academic-site'
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

If `python` is not available on Windows, try:

```powershell
py -3 -m http.server 8000
```

An optional live-reload option is:

```powershell
npm install -g live-server
live-server --port=8000
```

## Deploy to GitHub Pages

1. Push the repository to GitHub on the `main` branch. The repository URL is https://github.com/ShariqShoaib07/Scalar-Labs.git.
2. Open the repository settings and go to **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the root folder, then save.
5. GitHub Pages will publish the site at your Pages URL.

If you use a custom domain, update the `CNAME` file with your domain and make sure your DNS records point to GitHub Pages.

## Updating Content

Most updates can be made directly in the HTML files and the `data/` folder. Replace profile details, publication entries, images, and links as needed.

## Contributing

Pull requests are welcome for bug fixes, design updates, content corrections, or feature improvements.
