## How to deploy on any Static Web Host

# Advanced

# Vercel
## Step 1
If you haven't already, create a [Vercel](https://vercel.com) account. Sign into your Vercel account, go to your [dashboard](https://vercel.com/dashboard) and click **Add New**. Then, select **Project** and click on "**Import 3rd-party git repository.**"

Alternatively, you can go directly to [https://vercel.com/new/git/third-party](https://vercel.com/new/git/third-party) after signing in.

## Step 2 - Semi Advanced

You will need to fork ``https://github.com/interstellarnetwork/interstellar-vercel/`` and then go into the /static/ folder and then the /uv/ folder. Then click uv.config.js and change the bare server from ``https://example.com/bare/`` to another bare server.

**How do I use another proxy's bare server?**

There are several ways to get a bare server, if you have a ultraviolet based proxy that isn't blocked for you, you can type /bare/ at the end of the link and paste it into the uv.config.js file.

This will make your link work on any **Static Web Host**, Including Vercel & Netlify.

**How do I make my own bare server?**

You can deploy your own interstellar instance and then put /bare/ at the end of the link, now take that link and update the uv.config.js file with your link. Replace ``https://example.com/bare/`` with your link.

## Step 3 (Final Step)
Once the deployment has finished, go to the deployments dashboard and then go to **Settings** (you can find this in the top navigation bar).

Scroll down until you find the "**Build & Development Settings**" panel. Flip the override switch on "**Output Directory**" and set the input box to "static". Press "**Save**".

## That's it!
You now have a functioning link, good job!

