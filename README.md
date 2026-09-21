# AI Accelerator: Git + Deploy Sandbox

A throwaway practice site so you can go through the real branch -> commit -> push -> pull request -> merge -> deploy loop tonight, on your own copy, without touching anyone's production product.

## Step 0: get your own copy (30 seconds)

Click **Use this template** at the top of this repo's GitHub page, or the button below to fork it. Either way, GitHub will ask you to sign in (or create a free account) and will create a new repo under your own account.

[![Use this template](https://img.shields.io/badge/Use%20this%20template-2ea44f?style=for-the-badge)](https://github.com/landtakeoffs/ai-accelerator-sandbox/generate)

## Step 1: connect it to Vercel (about 1 minute, free, no credit card)

Click the button below. If you don't have a Vercel account yet, this same click creates one for you using your GitHub login, then imports your new repo and deploys it.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/landtakeoffs/ai-accelerator-sandbox&project-name=my-ai-accelerator-sandbox&repository-name=my-ai-accelerator-sandbox)

Important: run this from **your own forked copy's GitHub URL**, not this original repo, so the site that gets created is yours to edit. Swap `landtakeoffs/ai-accelerator-sandbox` in the button link for `YOUR-GITHUB-USERNAME/YOUR-REPO-NAME` after you fork.

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
