# UGN Developer Portfolio

A complete static, responsive, interactive developer portfolio for Universal Gaming Network. No framework, build step, backend, or paid hosting required.

## GitHub Pages deployment

1. Create a new public repository on GitHub, for example `ugn-dev-portfolio`.
2. Upload **index.html**, **style.css**, and **script.js** to the **root** of the repository (not inside another folder). `README.md` is optional.
3. In the repository open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**. Choose **main** and **/(root)**, then save.
5. GitHub will show your Pages URL once the deployment finishes. For a project repo it usually follows `https://<username>.github.io/<repository>/`.

## Customize

- Update the introduction and About sections in `index.html` to add your preferred public developer name and personal background.
- Edit the `projects` array at the top of `script.js` to change project descriptions, statuses, tags, and links.
- Adjust UGN colors in `style.css` under `:root`.
- All navigation uses anchor links, so the website works at both root domains and GitHub project subpaths.
- The site uses Google Fonts when available, with local system-font fallbacks.

## Notes

- Statuses are illustrative editorial snapshots, **not live deployment checks**.
- This site deliberately does not publish private infrastructure addresses, credentials, server IPs, or private repository information.
- No analytics or trackers are installed. The search/filter/theme switch work entirely in the browser.
- External links open in a new tab. No backend forms are included.
- Test the site locally by opening `index.html` in a browser.
