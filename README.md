Use of eval in "node_modules/lottie-web/build/player/lottie.js" is strongly discouraged as it poses security risks and may cause issues with minification.

Issue: main@HEAD Failed during 'site building' stage: Build script ended with non-zero exit code: 2

11:29:48 AM: build-image version: 3d3c7e8b4321e2c1a54a2c4584fb46ba742b1630 (focal)
11:29:48 AM: buildbot version: 72ed9578274f76ae72cdce4c5312615aeecc32fb
11:29:49 AM: Building without cache
11:29:49 AM: Starting to prepare the repo for build
11:29:49 AM: No cached dependencies found. Cloning fresh repo
11:29:49 AM: git clone --filter=blob:none https://github.com/Essama-Official/Fictum.Web
11:29:49 AM: Preparing Git Reference refs/heads/main
11:29:52 AM: Starting to install dependencies
11:29:52 AM: Python version set to 3.8
11:29:52 AM: Attempting Ruby version 2.7.2, read from environment
11:29:53 AM: Using Ruby version 2.7.2
11:29:53 AM: Started restoring cached go cache
11:29:53 AM: Finished restoring cached go cache
11:29:54 AM: go version go1.19.13 linux/amd64
11:29:55 AM: Using PHP version 8.0
11:29:57 AM: v18.20.2 is already installed.
11:29:57 AM: Now using node v18.20.2 (npm v10.5.0)
11:29:57 AM: Enabling Node.js Corepack
11:29:57 AM: Started restoring cached build plugins
11:29:57 AM: Finished restoring cached build plugins
11:29:57 AM: Started restoring cached corepack dependencies
11:29:57 AM: Finished restoring cached corepack dependencies
11:29:57 AM: No npm workspaces detected
11:29:57 AM: Started restoring cached node modules
11:29:57 AM: Finished restoring cached node modules
11:29:57 AM: Installing npm packages using npm version 10.5.0
11:29:58 AM: npm WARN ancient lockfile
11:29:58 AM: npm WARN ancient lockfile The package-lock.json file was created with an old version of npm,
11:29:58 AM: npm WARN ancient lockfile so supplemental metadata must be fetched from the registry.
11:29:58 AM: npm WARN ancient lockfile
11:29:58 AM: npm WARN ancient lockfile This is a one-time fix-up, please be patient...
11:29:58 AM: npm WARN ancient lockfile
11:30:01 AM: added 23 packages, and audited 24 packages in 3s
11:30:01 AM: 5 packages are looking for funding
11:30:01 AM:   run `npm fund` for details
11:30:01 AM: found 0 vulnerabilities
11:30:01 AM: npm notice
11:30:01 AM: npm notice New minor version of npm available! 10.5.0 -> 10.7.0
11:30:01 AM: npm notice Changelog: <https://github.com/npm/cli/releases/tag/v10.7.0>
11:30:01 AM: npm notice Run `npm install -g <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="751b05183544455b425b45">[email protected]</a>` to update!
11:30:01 AM: npm notice
11:30:01 AM: npm packages installed
11:30:01 AM: Successfully installed dependencies
11:30:01 AM: Starting build script
11:30:02 AM: Detected 1 framework(s)
11:30:02 AM: "vite" at version "5.2.11"
11:30:02 AM: Section completed: initializing
Upon running npm run build, there were no errors encountered:

vite v5.2.10 building for production...
transforming (66) node_modules\axios\lib\axios.js
src/images/categoriesback.png referenced in C:/Users/0infi/source/repos/Projects/Projects/Fictum.Web/src/views/CategoriesPage.vue?vue&type=style&index=0&scoped=219f2274&lang.css didn't resolve at build time, it will remain unchanged to be resolved at runtime
node_modules/lottie-web/build/player/lottie.js (17010:32): Use of eval in "node_modules/lottie-web/build/player/lottie.js" is strongly discouraged as it poses security risks and may cause issues with minification.
✓ 197 modules transformed.
dist/index.html                                       0.59 kB │ gzip:   0.35 kB
dist/assets/google-play-badge-BAXiFmDF.png            4.90 kB
dist/assets/youtube-B2-ob9Jb.png                      8.54 kB
dist/assets/download-on-the-app-store-DEgUYCrT.svg    8.85 kB │ gzip:   3.72 kB
dist/assets/linkedin-DgLzhU7_.png                    11.48 kB
dist/assets/fictumimage-cAnU0aOI.svg                 13.00 kB │ gzip:   4.06 kB
dist/assets/facebook-ejnf6rkB.png                    16.04 kB
dist/assets/google-Bp_336oh.png                      20.87 kB
dist/assets/twitter-CPWSm0NQ.png                     23.63 kB
dist/assets/tik-tok-C3xTsDPx.png                     23.80 kB
dist/assets/threads-BfxrDhYb.png                     25.52 kB
dist/assets/apple_logo-veUP97vU.png                  57.02 kB
dist/assets/instagram-VUFQ3l_n.png                   60.38 kB
dist/assets/index-D9yWPND-.css                      262.04 kB │ gzip:  34.54 kB
dist/assets/index-DJlyPodN.js                       976.53 kB │ gzip: 271.67 kB

(!) Some chunks are larger than 500 kB after minification. Consider:
- Using dynamic import() to code-split the application
- Use build.rollupOptions.output.manualChunks to improve chunking: https://rollupjs.org/configuration-options/#output-manualchunks
- Adjust chunk size limit for this warning via build.chunkSizeWarningLimit.
✓ built in 10.03s
package.json :

{
  "name": "vue-project",
  "version": "0.0.0",
  "private": true,
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "@capacitor/core": "^5.7.4",
    "axios": "^1.6.8",
    "bootstrap": "^5.3.3",
    "chart.js": "^4.4.2",
    "js-sha512": "^0.9.0",
    "twilio": "^5.0.4",
    "vue": "^3.3.11",
    "vue-chartjs": "^5.3.0",
    "vue-router": "^4.2.5",
    "vue3-lottie": "^3.3.0",
    "vuex": "^4.1.0"
  },
  "devDependencies": {
    "@vitejs/plugin-vue": "^4.5.2",
    "vite": "^5.0.10"
  }
}
I attempted the following steps to address a specific issue:

npm install vue-lottie@latest --save
npm install --legacy-peer-deps
This method was also tried within the same context of the question: "Go to Site Settings > Build & Deploy > Continuous Deployment. Go to Build Settings > Edit Settings. Edit your Build Command to CI= npm run build etc...". Additionally, I used CI with the value false and NPM_FLAGS with the value --legacy-peer-deps.
