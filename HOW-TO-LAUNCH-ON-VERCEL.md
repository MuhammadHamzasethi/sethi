# Launch the Sethi Studio portfolio on Vercel

Everything in this folder is the finished site: `index.html`, `work/` (the 3 sample portfolios), `videos/` (the 3 SaaS videos), and `vercel.json` (clean links and fast video loading). You don't need a build step or a framework.

## Easiest way: GitHub + Vercel (about 10 minutes)

1. **Unzip** `sethistudio-vercel.zip` on your computer.
2. **Make a GitHub repo.** Go to github.com/new. Name it `sethi-studio`, keep it Public, and click **Create repository**.
3. **Upload the files.** On the new repo page, click **"uploading an existing file"**. Drag in everything from inside the unzipped folder: `index.html`, `vercel.json`, and the `work` and `videos` folders. Don't drag the outer folder itself. Then click **Commit changes**.
   - Check that `index.html` is at the top level of the repo, not inside another folder.
4. **Import it on Vercel.** Go to vercel.com, sign up with **Continue with GitHub**, then click **Add New... > Project**. Pick `sethi-studio` and click **Import**.
5. **Settings.** Set Framework Preset to **Other**. Leave Build Command and Output Directory empty, then click **Deploy**.
6. After about 30 seconds you get a link like `sethi-studio.vercel.app`. Open it and check the work section: the videos should play when you click them.

## Change the link name

Go to Vercel > your project > **Settings > Domains**. Edit the `.vercel.app` name to something free, like `sethistudio.vercel.app`. If you buy a domain later (for example `sethistudio.com`), add it on the same page and follow the DNS steps Vercel shows you.

## Updating the site later

Upload the changed file to the same GitHub repo (Add file > Upload files > Commit). Vercel redeploys on its own within a minute.

## Other way: command line

If you have Node.js installed, open a terminal inside the unzipped folder and run:

```
npx vercel
```

Log in when it asks, and accept the defaults. Then run `npx vercel --prod` to make it live.

## After it's live

Send me the new link. I'll switch your emails, Fiverr and Upwork over to it.
