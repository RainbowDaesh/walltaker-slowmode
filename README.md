# Slowmode for Walltaker
### Modifies your Walltaker link to have a one minute cooldown between changes.
The link owner still has full permissions.

![Warning Dialog](screenshots/SlowmodeAction.png)

---
## Installation
1. Edit your link

![Step 1](screenshots/WT1.png)

2. Paste the contents of the html below somewhere into your description
```html
<style>@import url("https://rainbowdaesh.github.io/walltaker-slowmode/wtslo.css");</style>
```

![Step 2](screenshots/WT2.png)

3. Save

![Step 3](screenshots/WT3.png)

It can take about a minute for the css import to work its magic. You can import the contents of `wtslow.html` instead to instantly make changes to your link. It'll just be very cluttered, so importing is preferred. Try hard refreshing your browser (`CTRL+F5` or `CMD+SHIFT+R`).

---
## License
This project is licensed under the GNU GPL v3. See [LICENSE](LICENSE) for details.
