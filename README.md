# AI Accelerator: Git + Deploy Sandbox

A throwaway practice site so you can go through the real branch -> commit -> push -> pull request -> merge -> deploy loop tonight, on your own copy, without touching anyone's production product.

## Step 1: one click sets up your own GitHub repo and a live site (about 1 minute, free, no credit card)

Click the button below.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/landtakeoffs/ai-accelerator-sandbox&project-name=my-ai-accelerator-sandbox&repository-name=my-ai-accelerator-sandbox)

Vercel will walk you through:

1. Signing in, or creating a free account, using your GitHub login.
2. Naming a new git repository. This forks this sandbox into a brand-new repo under **your own** GitHub account, not this original one.
3. Importing that new repo as a Vercel project and deploying it immediately.

When it finishes you'll have your own GitHub repo and a live URL, both ready for the exercise below.

Prefer to fork on GitHub yourself first? Click **Use this template** at the top of this repo's page, then go to [vercel.com/new](https://vercel.com/new) and import your new repo from there instead.

## Step 2: do the exercise

1. Clone your new repo locally (or use GitHub's web editor if you don't want to install git tonight).
2. Create a branch, e.g. `git checkout -b my-change`.
3. Open `public/index.html` and change the headline, or add your name under "Built by".
4. Commit and push your branch: `git add -A && git commit -m "My first PR" && git push -u origin my-change`.
5. Open a pull request on GitHub from your branch into `main`.
6. Wait about 10-20 seconds. Vercel will post a preview link as a check on your PR. Click it, confirm your change shows up.
7. Merge the pull request.
8. Refresh your production URL (shown on your Vercel project dashboard). Your change is now live.

That loop, branch, PR, preview, merge, deploy, is the same one used to ship real products.
