### Hi there 👋

Hi. I live in Japan :japan: :shinto_shrine: :sushi: and I practice martial arts :octocat:. I love Rust! :crab:  
I usually create repos for my own benefit :avocado:, but I hope you will find them helpful to you as well! :seedling: :flamingo:

**[perlin-experiment-2](https://github.com/minagawah/perlin-experiment-2)**  
Another attempt in using Perlin noise. Last time, only the noise calculation was done in WASM, and canvas animations were done in JS. This time, everything is done in WASM. To better serve as an introductory WASM sample app, I made the codes as simple as possible.  
Highlights: (1) Spawns a child process for animation, (2) Event listener for browser resize event, and (2) `debounce` to limit executions when resize happens.  
:pushpin: `Rust` &middot; `wasm-pack` &middot; `wasm-bindgen` &middot; `js-sys` &middot; `web-sys` &middot; `wasm-pack-plugin`  
[:eyes: View Demo](https://tokyo800.jp/mina/perlin-experiment-2/)  

**[jsdoc-for-type-safety](https://github.com/minagawah/jsdoc-for-type-safety)**  
Use JSDoc comments, and run a type-check using TypeScript.  
:pushpin: `JSDoc` &middot; `TypeSript` &middot; `type-safety`

**[simple-i18n-solution](https://github.com/minagawah/simple-i18n-solution)**  
A simplified version of what I have for my website for i18n localization.  
:pushpin: `i18n` &middot; `NodeJS` &middot; `Javascript`

**[very-simple-wasm-2023](https://github.com/minagawah/very-simple-wasm-2023)**  
A sample WASM app using `wasm-pack-plugin` prepared as a learning material.  
:pushpin: `Rust` &middot; `wasm-pack` &middot; `wasm-bindgen` &middot; `js-sys` &middot; `web-sys` &middot; `wasm-pack-plugin`

**[widgets-react-vs-solidjs](https://github.com/minagawah/widgets-react-vs-solidjs)**  
Comparing widgets implemented with React vs SolidJS.  
This is more about using Emotion CSS and Tailwind CSS for React and SolidJS apps.  
:pushpin: `Web Components` &middot; `SolidJS` &middot; `React` &middot; `Emotion & Tailwind`  
[:eyes: View Demo](https://tokyo800.jp/mina/widgets-react-vs-solidjs/)  

**[latest-ts-setup-2022](https://github.com/minagawah/latest-ts-setup-2022)**  
Let me have a boiler plate for Babel + TypeScript.  
:pushpin: `Babel` &middot; `TypeScript` &middot; `React` &middot; `Emotion & Tailwind`

**[flight-pack](https://github.com/minagawah/flight-pack)**  
A demo app using wasm-pack-plugin, drawing flight information on Google Map.  
:pushpin: `Rust` &middot; `wasm-pack` &middot; `wasm-bindgen` &middot; `js-sys` &middot; `web-sys` &middot; `wasm-pack-plugin`  
[:eyes: View Demo](https://tokyo800.jp/mina/flight/)  

**[sowngwala](https://github.com/minagawah/sowngwala)**  
A library for calculating sun's position.  
_"sowng"_ stands for "sun" in
[Belter language](https://expanse.fandom.com/wiki/Belter_Creole) (from sci-fi movie "The Expanse").  
_"wala"_ for _"one who is professional at"_.  
:pushpin: `Rust`

**[mikaboshi](https://github.com/minagawah/mikaboshi)**  
A Rust library for 風水 (风水) (Feng-Shui) providing basic Chinese astrological concepts such as 八卦 (Ba-Gua), 干支 (Gan-Zhi), 九星 (Jiu-Xing), 二十四节气 (Er-Shi-Si Jie-Qi), 二十四山向 (Er-Shi-Si Shan-Xiang), 生死衰旺 (Sheng-Si Shuai-Wang), etc. When bundled into a WASM (WebAssembly) app, you could associate the library with your Javascript apps as well.    
:pushpin: `Rust`

**[perlin-experiment](https://github.com/minagawah/perlin-experiment)**  
This WASM app creates canvas elements for 2 divs, and runs animations.
The WASM app is one, but handles 2 canvas elements.
You may pass configs at initial startup.
Clicking the upper canvas, you may toggle among 3 visualization modes.
If you are only interested in Perlin Noise,
see my JS project `perlin-noise-world-map` (which is quite old) which auto-generates geographic landscapes
([source](https://github.com/minagawah/perlin-noise-worldmap)
or [demo](http://tokyo800.jp/minagawah/perlin-noise-worldmap/)).
Or, see `rust-perlin-wasm-test-2` (which is even much older) for particles moving in organic manner
([source](https://github.com/minagawah/rust-perlin-wasm-test-2)
or [demo](http://tokyo800.jp/minagawah/rust-perlin-wasm-test-2/)).  
:pushpin: `Rust` &middot; `wasm-pack` &middot; `wasm-bindgen` &middot; `js-sys` &middot; `web-sys` &middot; `Perlin Noise`  
[:eyes: View Demo](http://tokyo800.jp/mina/perlin-experiment/)  

**[react-widget-airport](https://github.com/minagawah/react-widget-airport)**  
Bundling a React app into UMD library, embedded into another app.
You can pass arguments at initial startup,
or you can dynamically send/receive messages using SharedWorker.  
:pushpin: `React` &middot; `UMD library` &middot; `SharedWorker`  
[:eyes: View Demo](http://tokyo800.jp/mina/react-widget-airport/)  

**[react-widget-setup-2021](https://github.com/minagawah/react-widget-setup-2021)**  
Just like the above `react-widget-airport`, but much simpler!  
:pushpin: `React` &middot; `UMD library` &middot; `SharedWorker`  
[:eyes: View Demo](http://tokyo800.jp/mina/react-widget-setup-2021/)  

**[service-worker-experiment](https://github.com/minagawah/service-worker-experiment)**  
Worker is a powerful tool, but when implementing the related Web APIs, it can easily drive you into a rabbit hole.  
With this sample app, I am attempting to demonstrate how you can implement related APIs.  
:pushpin: `Serrvice Worker` &middot; `Client API` &middot; `Cache API` &middot; `Vue 2`  
[:eyes: View Demo](https://tokyo800.sakura.ne.jp/mina/sw/)  

**[solid-setup-2021](https://github.com/minagawah/solid-setup-2021)**  
A template for Solid.js projects. Always nice to have Tailwind.
Basically, this is for my own use...  
:pushpin: `Solid.js` &middot; `Tailwind CSS`

**[yew-setup-2021](https://github.com/minagawah/yew-setup-2021)**  
A template for `yew` projects. This is basically for my own use.  
:pushpin: `yew` &middot; `Rust` &middot; `wasm-pack-plugin`  
[:eyes: View Demo](http://tokyo800.jp/mina/yew-setup-2021/)  

**[wasm-pack-react-markdown-example](https://github.com/minagawah/wasm-pack-react-markdown-example)**  
A React app using WASM for converting markdown contents into HTML.  
:pushpin: `Rust` &middot; `wasm-pack` &middot; `wasm-bindgen` &middot; `React` &middot; `CRA` &middot; `markdown`

**[reveal-yourself](https://github.com/minagawah/reveal-yourself)**  
An example using Github Actions to automate cargo build for multiple binaries.  
:pushpin: `Github Actions` &middot; `rust`

**[csp-nonce-for-emotion.md](https://gist.github.com/minagawah/bc56b1dae8e3a967788c255a1032d1ae)**  
Tricks to insert "nonce" for style tags in your HTML when using `csp-html-webpack-plugin` and `emotion`.  
:pushpin: `csp-html-webpack-plugin` &middot; `emotion`

**[mapbox-gl-js-v2-experiment](https://github.com/minagawah/mapbox-gl-js-v2-experiment)**  
Mapbox GL JS v2 experiment. Using no React.  
:pushpin: `Mapbox GL JS v2` &middot; `Tailwind CSS` &middot; `ramda`  
[:eyes: View Demo](http://tokyo800.jp/mina/mapbox-gl-js-v2-experiment/)  

**[mini-actix-react-example](https://github.com/minagawah/mini-actix-react-example)**  
[actix-web](https://actix.rs/) is an amazing, fast Rust web framework.
Although I have more complicated configurations for my own website, ideas are about the same.  
:pushpin: `Rust` &middot; `actix-web` &middot; `heroku-buildpack-rust` &middot; `CORS`

**[webpack-webcomponent-example](https://github.com/minagawah/webpack-webcomponent-example)**  
While this is old, it presents 3 basic examples of how you can implement web components.  
:pushpin: `Web Components`  
[:eyes: View Demo](http://tokyo800.jp/minagawah/webpack-webcomponent-example/)  

<!--
**minagawah/minagawah** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
