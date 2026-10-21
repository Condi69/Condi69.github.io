# Still — iPhone PWA

This folder is the installable, offline-capable web app bundle. It has no analytics, accounts, server calls, or external assets.

## Publish for free with GitHub Pages

GitHub Pages is free for public repositories. A public repository means the app's source files can be viewed by anyone.

1. Create a public GitHub repository, for example `still-block-puzzle`.
2. Upload every file in this folder to the repository's top level.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and `/(root)`, then save.
5. Wait for the Pages URL shown on that screen to become available.
6. On the iPhone, open that HTTPS URL in Safari, tap **Share → Add to Home Screen**, then launch Still from the new icon.
7. Open the game once while online so the service worker can cache it. Then try it in Airplane Mode.

The game itself needs no network connection after its first successful load. Its score stays in the current game session and is not sent anywhere.