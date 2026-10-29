# After-School Planner

Static web app. No build step.

Deploy: drag this folder (or the zip) onto https://app.netlify.com/drop,
or connect a Git repo with publish directory `.`.

Plans save in the browser on each device (localStorage). Use Tray → Backup
to export a JSON file and import it on another device.

When you change any file, bump `VERSION` in `sw.js` so installed copies update.
