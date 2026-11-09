# PiplipopAIStudio website

This is a static, build-free website for the PipliPop game. It contains the home page, contact page, and app privacy policy.

## Pages

- `index.html` — home page
- `contact.html` — contact details for PiplipopAIStudio
- `privacy-policy.html` — PipliPop and website privacy policy
- `styles.css` — shared responsive styles

The app's in-app privacy link is `https://piplipopaistudio.github.io/Piplipop/privacy-policy.html`. The repository workflow `.github/workflows/publish-website.yml` publishes the **contents** of `website/` as the Pages artifact when manually run from the `main` branch. It does not deploy on every push.

The site has no build step, analytics, third-party fonts, or embedded tracking scripts. In GitHub repository settings, set **Settings → Pages → Build and deployment → Source** to **GitHub Actions** before running the workflow.
