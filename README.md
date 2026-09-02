# Personal Dashboard — Learning Fork

A personal learning and customization project based on [RowanThistlebrooke/V2-YT](https://github.com/RowanThistlebrooke/V2-YT).

This repository is **not presented as original portfolio work**. The upstream author's copyright and usage restrictions remain in effect; do not redistribute, commercialize, or republish the included upstream code without permission.

## What I explored

- A responsive bento-style dashboard
- Goal and daily-progress tracking
- Health, hydration, finance, and training views
- Shared navigation across self-contained pages
- Browser storage and optional Supabase synchronization
- Mobile safe-area and reduced-width layout handling

## Run locally

The project is made of self-contained HTML, CSS, and JavaScript files. Open `index.html` directly in a browser or serve the folder with a local development server.

## Data and configuration

Most local state is stored in the browser. Some customized pages can synchronize through Supabase.

When adapting the project:

- use only a Supabase publishable key in client code;
- never commit a service-role key;
- enforce Row Level Security for every exposed table;
- keep personal configuration and real user data out of the repository.

## Attribution

Original project and copyright: [Rowan Thistlebrooke](https://github.com/RowanThistlebrooke).

My work in this fork is limited to learning, configuration, and personal modifications. This repository should not be treated as one of my original flagship projects.
