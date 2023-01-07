# nostr-expo-starter

Minimum viable Expo app that works with Nostr

## Recreate it like this

- `npx create-expo-app {appname}`
- `npm i --save text-encoding-polyfill nostr-tools`
- `npx expo install expo-random`
- Add `"postinstall": "npx patch-package"` to package.json
- `npm i` to apply patch
- `npm run start`
