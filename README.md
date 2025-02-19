# example-path-repro

Bug repro for create-next-app --example-path discussion.

A script has been added to make it easier to test, this script runs the command `cd src && npx create-next-app@latest --example-path ./repro`. 

## Steps

1. Run `pnpm test [app-name]`
2. See if it copies the existing config in `/src/repro`
