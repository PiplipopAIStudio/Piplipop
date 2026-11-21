# PiplipopAIStudio website

This is a static, build-free website for the PipliPop game. It contains the home page, contact page, and app privacy policy.

## Pages

- `index.html` — home page
- `contact.html` — contact details for PiplipopAIStudio
- `privacy-policy.html` — PipliPop and website privacy policy
- `pip.png` — Pip character used as the website brand mark
- `styles.css` — shared responsive styles

The Contact Us page links to the closed-test signup and feedback forms. Form responses and uploaded screenshots are managed in the owner's Google account; keep form collaborators, response sheets, and upload files restricted to authorized people.

This folder is the website source in the PipliPop app repository; it does not deploy from here. Copy the **contents** of `website/` into the root of your separate GitHub Pages repository when you are ready to publish. Keep the filenames together so the page links and shared stylesheet work.

The app's in-app privacy link currently expects `https://piplipopaistudio.github.io/Piplipop/privacy-policy.html`. That matches a GitHub Pages site deployed at `https://piplipopaistudio.github.io/Piplipop/`. If your destination repository produces a different Pages URL, update the in-app link in `src/core/screens/ParentScreens.tsx` to match.

The site has no build step, analytics, third-party fonts, or embedded tracking scripts. In the destination repository, configure GitHub Pages for the publishing method you use and manually deploy the copied files.
