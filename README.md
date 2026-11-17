# HM Craft Labs site

Static pages for the Play listing. Publish them from a **separate public repo** so the app code stays private.

1. On GitHub, create a public repo named exactly `Harshada87.github.io`.
2. Copy everything in this `site/` folder to the root of that repo and push.
3. Settings › Pages: Source = Deploy from a branch, `main`, `/ (root)`.
4. After a minute these are live:
   - https://harshada87.github.io/focuscoach/privacy.html (Play: App content › Privacy policy; also linked from the app's Settings)
   - https://harshada87.github.io/focuscoach/delete-account.html (Play: App content › Data deletion)
   - https://harshada87.github.io/app-ads.txt (after you add your AdMob publisher ID)
5. In Play Console, set the store listing **Website** to `https://harshada87.github.io` so AdMob can find `app-ads.txt`.

The app links to the first two URLs, so keep the paths the same.
