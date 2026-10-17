# Whack Whack Collections

Static pages for curated artwork collections by Jeff Wilson.

## Netlify setup

Connect this repository to Netlify, select the `main` production branch, leave the build command empty, and use `public` as the publish directory. The publish directory is also set in `netlify.toml`.

The starter landing page is `public/index.html`. There are no build dependencies.

## Collection publishing

Collection edits and generated previews remain in the local Art Business app. The app's future **Publish** action will copy a selected saved preview into this repository and push it to GitHub. A push to the connected production branch will trigger Netlify deployment.

The publishing integration is not connected yet. This repository currently contains only a starter landing page, with no collection presentations or business data.
