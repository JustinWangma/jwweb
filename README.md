# vCard - Personal portfolio

vCard is a fully responsive personal portfolio website, responsive for all devices, built using HTML, CSS, and JavaScript.


## License

MIT

## Running

python -m http.server 8000 // windows

python3 -m http.server 8000  // mac 

[http://localhost:8000](vscode-file://vscode-app/c:/Users/yingq/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-browser/workbench/workbench.html)


brower url
http://localhost:8000/

To stop the server, press `Ctrl + C` in the terminal.


## Publishing to GitHub Pages

### Prerequisite: Repository must be public

GitHub Pages requires a public repository on the free plan. To check or change:

1. Go to your repo on GitHub → **Settings**
2. Scroll to the bottom → **Danger Zone**
3. If it says "This repository is currently private", click **Change visibility** → **Make public**

> Alternatively, upgrade to GitHub Pro ($4/mo) to use Pages with a private repo.

### Enable GitHub Pages

1. On GitHub, open your repo and click the **Settings** tab
2. In the left sidebar, click **Pages**
3. If you see a **Source** dropdown, select `Deploy from a branch`
4. Under **Branch**, select `main` and leave the folder as `/ (root)`, then click **Save**
5. Wait ~1-2 minutes — your site will be live at:
   https://justinwangma.github.io/personal-website/

### Updating the site

After making changes, push to GitHub and Pages will redeploy automatically:

```bash
git add .
git commit -m "your message"
git push
```