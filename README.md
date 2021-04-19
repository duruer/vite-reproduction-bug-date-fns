# Reproduce of Date-fns bug in Svelte Kit / Vite

Just run the project. In first run of server, it will give same error in each page visit. But after second time running
the server will not throw the errors.

Also if you close server, delete `.svelte` and `node_modules` then run the server again. It will throw same error again
each page visit.

## Run

If you're seeing this, you've probably already done this step. Congrats!

```bash
# install dependencies via yarn
yarn

# run via yarn
yarn dev
```
