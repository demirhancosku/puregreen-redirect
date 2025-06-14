# PureGreen Redirect Page

This is a static redirect page that detects the user's device and redirects to the appropriate app store after a 3-second delay, showing a loading bar and the PureGreen logo.

## Project Structure

- `index.html` — Main redirect page
- `store-urls.json` — Contains the Apple and Play Store URLs
- `puregreen-splash-temp.png` — Logo and background image
- `vercel.json` — Vercel configuration

## How to Deploy on Vercel

1. **Push this repository to GitHub, GitLab, or Bitbucket.**
2. **Go to [vercel.com](https://vercel.com) and import your repository.**
3. **Choose the default settings for a static site.**
4. **Deploy!**

No build step is required. All files will be served statically. The `vercel.json` ensures that `index.html` is the entry point and all assets are accessible.

## Customization
- Update `store-urls.json` with your actual App Store and Play Store URLs.
- Replace `puregreen-splash-temp.png` if you want a different logo/background. 