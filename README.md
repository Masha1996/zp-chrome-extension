# Zeropool Chrome Extension

Chrome extension that allow to make anonymous transaction using Zeropool smart contract.

## Development

- Clone repository with submodules:
`
git clone git@github.com:zeropoolnetwork/zp-chrome-extension.git --recurse-submodules
`

- Build circuits: `./build-txcircuits.sh`, Notes: 
  - *`txcircuit` build doesn't work with node `v12.14.0`, build is tested with node version
 `v11.15.0`.*
  - Build might take time

 - Build chrome extension:
    - `npm run extension:build`

 - Build & watch:
   - `npm run extension:watch`
   - You may use `npm start` ,in case you want to work only on UI part
   


