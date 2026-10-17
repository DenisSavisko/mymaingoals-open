# open.mymaingoals.app

Universal link domain for the MyMainGoals iPhone app. Links here open the app when it's
installed; otherwise the page redirects to the App Store. Used by the web app's Settings
button, since links on mymaingoals.app itself stay in Safari.

- `.well-known/apple-app-site-association` — claims every path for the app.
- `index.html` / `404.html` — App Store redirect for when the app isn't installed.
- `.nojekyll` — lets GitHub Pages serve the `.well-known` folder.
