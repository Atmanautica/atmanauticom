# Atmanauticom

A monorepo for:
- the headless Sanity CMS where we keep 'em integrated
- the static Next.js client that displays our posts and pages and work

## To run locally

```
git clone git@github.com:Atmanautica/atmanauticom.git
cd atmanauticom
git submodule sync
yarn
cd studio && yarn
cd ../web && yarn
cd .. && yarn dev
```
