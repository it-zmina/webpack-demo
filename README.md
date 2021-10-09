#webpack-demo

_Template for adding webpack bundler_

## Step 1 -- Add webpack

1. Clone to your local machine: `git clone https://github.com/it-zmina/webpack-demo.git`
2. Check that example working.
3. Init npm project manager (create `package.json` file): `npm init -y`
4. Install webpack bundler as dev dependency: `npm install webpack webpack-cli --save-dev`
5. Move `index.html` file to the `dist` folder.
6. Add `loadsh` module locally: `npm install --save lodash`
7. Remove `main` and add `private` fields as shown at the next picture: ![doc/step1-1.png](doc/step1-1.png)
8. Add import section for `loadsh` module: ![doc/step1-2.png](doc/step1-2.png)
9. Remove remote module and rename main script (entry point): ![doc/step1-3.png](doc/step1-3.png)
10. Add scripts for convenience: ![doc/step1-4.png](doc/step1-4.png)

## Step 2 -- Add webpack configuration

1. Add `webpack.config.js` file to the project root folder: ![doc/step2-1.png](doc/step2-1.png)
2. Update `scripts` section at the `package.json`: ![doc/step2-2.png](doc/step2-2.png)

