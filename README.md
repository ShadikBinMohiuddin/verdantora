# WildFrame — Nature Photography Website

A responsive, static photography business website built with HTML, CSS, and vanilla JavaScript. No build step or backend is required.

## Run locally

Open `index.html` in a browser. For a local development server, use the VS Code Live Server extension.

## Personalize before publishing

1. In `index.html`, replace `WildFrame` with your chosen brand name.
2. Replace `[Your Name]` in the About section.
3. In the `SITE_SETTINGS` object near the end of the file, replace `hello@yourdomain.com` with your real email address. The contact form uses the visitor's email app via `mailto:`; it does not store or send submissions through a server.
4. Replace demo Unsplash images with your own photographs or images you have permission to use. Update each image's `alt` text to describe it accurately.
5. Update the location and service descriptions to match your actual business.

## Deploy to GitHub and Vercel

1. Create a GitHub repository, for example `nature-photography-website`.
2. Upload `index.html` and `README.md` to the repository root (the top level, not inside another folder).
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository and authorize access if asked.
5. For a plain HTML site, leave the framework preset as **Other** and do not set a build command. Leave the output directory blank unless Vercel requests otherwise.
6. Click **Deploy**. Vercel will provide a live `vercel.app` URL.
7. When you make changes in GitHub and push/commit them to the connected branch, Vercel normally redeploys automatically.

## Features

- Responsive layout for phones, tablets, and desktops
- Gallery filters: landscapes, forests, waterfalls, wildlife
- Full-screen image viewer with next/previous, Escape, and arrow-key controls
- Mobile navigation menu
- Contact form that prepares an email in the visitor's mail app

## Note

This is a static website. The contact form does not send messages on its own or save visitor details. For a server-backed form, connect a form service or add a backend later.
