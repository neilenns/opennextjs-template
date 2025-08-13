# opennextjs project template

This template is designed to be used as the base for new GitHub repos that want an opennextjs site that deploys to Cloudflare via GitHub actions.

After creating the repo, clone it into a VSCode dev container. Then:

- Change the package name in `package.json`
- Edit `wrangler.jsonc` and configure the deployment environments
- Create GitHub environments for `dev` and `prod`
- Set the following environment variables in each environment:
  - `CLOUDFLARE_ACCOUNT_ID`
  - `CLOUDFLARE_API_TOKEN`
  - `DEPLOY_ENV` (`dev` or `prod`)
