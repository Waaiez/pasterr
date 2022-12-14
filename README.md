# Pasterr

<!-- pastebin url -->

This is a project similar to [Github Gists](https://gist.github.com/), [Hastebin](https://hastebin.com) and [Pastebin](https://pastebin.com) created using [SvelteKit](https://kit.svelte.dev/).

## Technologies used:

[![SvelteKit](https://img.shields.io/badge/-SvelteKit-ff3e00?style=for-the-badge&logo=svelte&logoColor=white)](https://kit.svelte.dev/)
[![Svelte](https://img.shields.io/badge/-Svelte-ff3e00?style=for-the-badge&logo=svelte&logoColor=white)](https://svelte.dev/)
[![Skeleton.dev](https://img.shields.io/badge/-Skeleton%20UI-ff3e00?style=for-the-badge&logo=svelte&logoColor=white)](https://skeleton.dev/)
[![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-ff3e00?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vercel](https://img.shields.io/badge/-Vercel-ff3e00?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)
[![Prisma](https://img.shields.io/badge/-Prisma-ff3e00?style=for-the-badge&logo=prisma&logoColor=white)](https://www.prisma.io/)
![CockroachLabs](https://img.shields.io/badge/CockroachDB-ff3e00?style=for-the-badge&logo=Cockroach%20Labs&logoColor=white)

## Features:

- [x] Create A Paste
- [x] View A Paste
- [x] View A Paste As Raw (Plain Text)
- [x] Copy A Paste
- [x] Duplicate & Edit Existing Pastes
- [x] Paste View Count
- [x] Language Support (Syntax Highlighting)
- [x] Latest Pastes Page
- [x] Paste Visibility (Public/Private)

## Future Plans:

- media uploads
- Allow pastes to be password protected
- Allow pastes to have timer to delete after a certain amount of time
- Allowing pastes to be viewed once before being deleted

- og:image for sharing on social media
  - https://github.com/etherCorps/sveltekit-og

## Things to think about:

- Do I want accounts?
  - Do I want to allow users to edit their pastes?
    - Do I want to allow users to delete their pastes?
- Possibly allow user to choose slug length / custom slug
- View count logic is probably wrong, do research

## Considerations:

- No rate limiting
- Prisma apparently uses prepared statements, but I'm not sure if that's enough to prevent SQL injection attacks
- To improve perceived performance, move the loading of paste data to an onMount function and show skeleton cards to indicate loading

## TODO:

- Look at TODO comments
- Think more about og:images
  - Might not be feasible trying to pull data from db on the fly

## Attribution:

Favicon is using the <a target="_blank" href="https://icons8.com/icon/49462/paste">Paste</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
