# Chess-3D
I developed a small chess game using Three.js and Webpack for bundling. All 3D models were crafted in Blender. The game features a straightforward AI system that utilizes the minimax algorithm with alpha-beta pruning. To prevent the main thread from being blocked and to ensure smooth application performance, the AI runs in a separate Web Worker instance.




Ensure that you have **hardware acceleration** switched on. 

The guides for different browsers are available here:
[Chrome](https://help.clickup.com/hc/en-us/articles/6327835447191-Enable-hardware-acceleration-in-Google-Chrome) | [Firefox](https://support.mozilla.org/en-US/kb/performance-settings) | [Opera](https://windowsreport.com/opera-browser-hardware-acceleration/)

Game available on: https://chess-3d-mja9.vercel.app/

## Useful commands

```
// run the application on development mode
npm run start:dev

// build application for development
npm run build:dev

// build application for production
npm run build:prod

// run the application in production mode
npm run start
```
