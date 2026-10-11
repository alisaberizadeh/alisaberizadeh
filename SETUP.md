# Setup — GitHub Profile README

This folder is ready for the public profile repository **alisaberizadeh/alisaberizadeh**.

## Install

1. On GitHub, create a **public** repository named exactly `alisaberizadeh` (the same as your account username). If this repository already exists, use it instead of creating another one.
2. Upload the contents of this folder to its **default branch**, keeping the directory structure intact:
   - `README.md`
   - `assets/hero-dark.svg`, `assets/hero-light.svg`, `assets/footer-dark.svg`, `assets/footer-light.svg`
   - `.github/workflows/snake.yml`
3. Go to the repository **Actions** tab and enable workflows if GitHub asks you to.
4. Open **Actions → Generate Contribution Snake → Run workflow** to generate the first snake images.
5. If the snake publishing action cannot push, go to **Settings → Actions → General → Workflow permissions** and choose **Read and write permissions**, then rerun the workflow. The workflow also explicitly requests `contents: write`.
6. Wait for the **output** branch to be created by the workflow. The README's snake image will then load, with light/dark versions selected automatically.
7. Visit <https://github.com/alisaberizadeh> to see the profile.

## Notes

- Header/footer use matching local SVG assets for light and dark modes. Their animated SVG waves may appear static in clients that restrict SVG animation.
- Typing, statistics, streak, skill icons, and activity graph use external image generators. These services may occasionally be slow, unavailable, or rate-limited.
- GitHub statistics and language rankings reflect GitHub's publicly available data and the third-party service's calculation rules; they are not hand-entered facts.
- You can remove any section of the README whenever you wish; there is intentionally no featured-projects section, no trophy section, and no visitor-counter badges.
- Emails are public in this README as requested.
