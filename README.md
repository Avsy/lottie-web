Use of eval in "node_modules/lottie-web/build/player/lottie.js" is strongly discouraged as it poses security risks and may cause issues with minification.

Issue: main@HEAD Failed during 'site building' stage: Build script ended with non-zero exit code: 2

```bash
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
```
https://qanswer.space/questions/issue-mainhead-failed-during-site-building-stage-build-script-ended-with-non-zero-exit-code-2
