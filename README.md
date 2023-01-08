# nostr-expo-starter

Minimum viable Expo app that works with Nostr

## Recreate it like this

- `npx create-expo-app {appname}`
- `npm i --save text-encoding-polyfill nostr-tools`
- `npx expo install expo-random`
- Copy the patch in `patches/` folder - see [arc#17](https://github.com/ArcadeLabsInc/arc/pull/17) for context
- Add `"postinstall": "npx patch-package"` to package.json
- `npm i` to apply patch
- `npm run start`

Then you can use [nostr-tools](https://github.com/nbd-wtf/nostr-tools). See [plebchat](https://github.com/ArcadeLabsInc/plebchat) for demo.
