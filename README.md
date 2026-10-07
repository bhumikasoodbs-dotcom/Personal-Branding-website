# Bhumika Sood — Personal Brand Website

A static, responsive personal branding site for management consulting opportunities. Built with HTML, CSS and a small amount of vanilla JavaScript; no build step or paid service is needed.

## Preview locally

Open `index.html` in a browser. For a local server, run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Personalise before publishing

1. **Email:** in `index.html`, replace the empty `href="mailto:"` with your preferred public address, for example `href="mailto:name@example.com"`.
2. **Resume:** replace `assets/Bhumika_Sood_Resume.pdf` with the latest approved PDF using the same filename.
3. **LinkedIn:** verify the profile URL in the Contact section.
4. **Photo:** the hero currently uses an initials monogram. If you want a photo, add a properly licensed or personal image to `assets/`, then replace the `.hero-art` content with an `<img>` and meaningful alt text.
5. **Facts:** verify all figures and claims against your resume before making the site public, especially any client-derived metrics. Keep client identities and confidential information out of public copy.
6. **SEO:** update the title, description, Open Graph image and Person JSON-LD if your positioning or public details change. Replace `assets/og-image.svg` with a 1200×630 image if desired.

## Deploy free

### GitHub Pages

1. Create a GitHub repository and upload the contents of this folder (the `index.html` must be at the repository root).
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for the published URL shown on the Pages screen. GitHub Pages serves this static site without a build command.

### Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, import that repository.
3. Choose **Other** as the framework preset; leave the build command empty and set the output directory to `.`.
4. Deploy. Static asset paths are relative, so they work on the Vercel domain and GitHub Pages project paths.

A custom domain is optional; configure it in the hosting provider and point its DNS records as instructed there.

## Accessibility and checks

The page uses semantic landmarks, a skip link, keyboard focus styles, an accessible mobile menu, alt-free CSS decoration, and reduced-motion support. It has responsive breakpoints for mobile, tablet and desktop, descriptive page metadata, Open Graph tags, and Person JSON-LD. Test keyboard navigation, narrow layouts, links, and contrast in your target browser before publishing.

## Placeholders / checks before public launch

- Add your preferred public email address.
- Confirm that the included resume PDF is the version you want public.
- Verify the LinkedIn URL and all numerical claims.
- Replace the initials monogram with a professional photo if you choose to use one.
- Confirm that any quantified client impact is suitable for public disclosure.
