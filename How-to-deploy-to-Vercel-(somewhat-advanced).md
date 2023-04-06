# How to deploy to Vercel

## Step 1
If you haven't already, create a [Vercel](https://vercel.com) account. Sign into your Vercel account, go to your [dashboard](https://vercel.com/dashboard) and click **Add New**. Then, select **Project** and click on "**Import 3rd-party git repository.**"

Alternatively, you can go directly to [https://vercel.com/new/git/third-party](https://vercel.com/new/git/third-party) after signing in.

## Step 2
Paste `https://github.com/interstellarnetwork/interstellar-vercel` into the Git repository field, then select continue. It will then prompt you to "**Create a Git Repository.**" Add a name to the repository and press continue.

## Step 3 (Final Step)
Once the deployment has finished, go to the deployments dashboard and then go to **Settings** (you can find this in the top navigation bar).

Scroll down until you find the "**Build & Development Settings**" panel. Flip the override switch on "**Output Directory**" and set the input box to "static". Press "**Save**".

## That's it!
You now have a functioning Vercel link, good job!