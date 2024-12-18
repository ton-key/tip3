<p align="center">
    <h3 align="center">TIP3</h3>
    <p align="center">Broxus TIP3 (tip3.1, tip3.2) Fungible tokens implementation</p>
<p align="center">
  <a href="https://github.com/venom-blockchain/developer-program">
    <img src="https://raw.githubusercontent.com/venom-blockchain/developer-program/main/vf-dev-program.png" alt="Logo" width="366.8" height="146.4">
  </a>
</p>
<p align="center">
    <a href="https://www.npmjs.com/package/@broxus/tip3">
        <img alt="npm" src="https://img.shields.io/npm/v/@broxus/tip3">
    </a>
</p>

### Firstly

npm install

### Then use Locklift v2 to deploy

1. To deploy tokens via token factory

npx locklift run --config locklift.config.ts --network local --script scripts/0-deploy-token.ts

2. To deploy factory

npx locklift run --config locklift.config.ts --network local --script scripts/1-deploy-factory.ts

### For test Token Factory

npx locklift test -n local
