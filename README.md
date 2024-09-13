# just-electron
//electron
mkdir my-electron-app && cd my-electron-app
npm init
npm install --save-dev electron

npm install --save-dev @electron-forge/cli
npx electron-forge import
npm run make


npm init electron-app@latest my-app
npm init electron-app@latest my-app -- --template=webpack