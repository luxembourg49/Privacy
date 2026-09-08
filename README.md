# App Privacy Policies

This is one GitHub Pages website with a separate privacy-policy page for each app. The policies themselves are plain Markdown files, so editing one is just copy, paste, and replacing the bracketed placeholders.

## First-time GitHub setup

1. Create a GitHub repository named `privacy` in the GitHub account or organization that will own these policies. For example, the `yourcompany` organization produces `https://yourcompany.github.io/privacy/`.
2. Upload or push this folder's contents to the repository's default branch, usually `main`.
3. On GitHub, open the repository's **Settings** > **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/(root)`, and select **Save**.
6. Wait for the Pages deployment to complete. GitHub shows the published address in **Settings** > **Pages**.

Do not choose a repository named `<yourcompany>.github.io` unless you want a site at the domain root. The repository must be named `privacy` to use the `/privacy/` address shown here.

## Published URLs

Once Pages has deployed, the URLs will be:

```text
https://yourcompany.github.io/privacy/
https://yourcompany.github.io/privacy/LuxPhoto/
https://yourcompany.github.io/privacy/WrinkleDoc/
```

Replace `yourcompany` with your GitHub account or organization name. Paste the app-specific URL into App Store Connect's **Privacy Policy URL** field.

## Add a New App

1. Copy an existing app folder, such as `LuxPhoto`.
2. Rename the copied folder to the new app's URL-safe name, for example `MyNewApp`.
3. Edit the copied `index.md`: replace the app name and every `[bracketed placeholder]` with the app's actual policy details.
4. Add a link to the new folder in the root `index.md`.
5. Commit and push the changes. GitHub Pages republishes automatically.

Keep spaces out of folder names so each App Store URL stays simple and dependable.

## Before You Publish

Make the policy accurately match the app's App Privacy answers in App Store Connect and any SDKs or services it uses. A privacy policy is a legal disclosure; have it reviewed when appropriate for your business and jurisdiction.