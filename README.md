# crate3d.com

The Crate3D website: one static page, served by GitHub Pages.

The contact form posts to a Cloudflare Worker, which sends the message on
through Postmark. The Worker holds the API token; nothing secret lives here.

This repository is public because GitHub Pages requires it on the free plan.
Everything in it is already served publicly at crate3d.com.
