# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 24

# Verify the Node.js version:
node -v # Should print "v24.11.1".

# Download and install pnpm:
corepack enable pnpm

# Verify pnpm version:
pnpm -v
# pnpm.io

## Testing locally

```
cd website
pnpm install
pnpm start
```

## How to publish

Push to the default branch, the website will be deployed automatically.

## Algolia Search

If changes should be done to the search index, submit the changes here to the [docsearch-configs repository](https://github.com/algolia/docsearch-configs/blob/master/configs/pnpm.json).
