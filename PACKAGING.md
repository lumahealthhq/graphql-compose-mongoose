# How to Package for Luma

1. Install `yarn`
2. Use node `v11.15.0` `(npm v6.7.0)`
3. Run the following script to install then build
```bash
yarn;
yarn build
git add --force lib es node8 mjs
git commit -m '<commit msg>'
git tag -a <new tag (refer to latest tag releases in repo) -m 'commit message'
git push -u origin <tag name>
```
