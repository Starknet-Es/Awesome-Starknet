<div align="center">
  <img alt="starknet logo" src="./assets/starknet.png" width="200" >
  <h1 align="center">Awesome StarkNet</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#buildstatus">
      <img alt="build status badge" src="https://github.com/gakonst/awesome-starknet/workflows/Build/badge.svg">
    </a>
    <a href="https://github.com/gakonst/awesome-starknet/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/gakonst/awesome-starknet">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">Una lista increíble de<a href="https://medium.com/starkware/starknet-alpha-is-coming-to-mainnet-b825829eaf32">StarkNet</a> con recursos, librerías, herramientas y mas.</p>
  <p align="center">Por favor revise <a href="CONTRIBUTING.md">directrices de contribución</a> para obtener información sobre el formato y la redacción de pull requests.</p>

</div>

### Contenido

- [Recursos](#recursos)
  - [Oficial](#oficial)
  - [Ecosistema](#ecosistema)
  - [Tutoriales](#tutoriales)
  - [Artículos](#artículos)
  - [Seguridad](#seguridad)
  - [Ejemplos](#ejemplos)
  - [Educacional](#educacional)
  - [Deployando en Starknet Mainnet](#deployando-en-starknet-mainnet)
  - [Plantillas](#plantillas)
  - [Libros](#libros)
  - [Prácticas](#prácticas)
  - [Trabajo](#trabajo)
- [Librerías](#librerías)
- [Herramientas](#herramientas)
  - [General](#general)
  - [Utilidad](#utilidad)
  - [Auditoría](#auditoría)
- [Editor Plugins](#editor-plugins)
  - [Vim](#vim)
  - [Visual Studio Code](#visual-studio-code)
- [Licencias](#licencias)

## Recursos

#### Oficial

- [Documentación de StarkNet y Cairo](https://www.cairo-lang.org/docs/index.html) -
  Documentación oficial.
- [Configuración del entorno](https://www.cairo-lang.org/docs/quickstart.html) -
  Cómo instalar Cairo y StarkNet.
- [Cómo funciona Cairo](https://www.cairo-lang.org/docs/how_cairo_works/index.html) -
  Explicación de bajo nivel de la mecánica de Cairo.
- [Hola StarkNet](https://www.cairo-lang.org/docs/hello_starknet/index.html) -
  Tutorial para escribir y desplegar un contrato.
- [Hola Cairo](https://www.cairo-lang.org/docs/hello_cairo/index.html) -
  Tutoriales para redactar varios contratos sencillos de Cairo.
- [Referencia de Cairo](https://www.cairo-lang.org/docs/reference/index.html) -
  Explicación de la sintaxis de Cairo.
- [Cairo: una arquitectura de CPU Turing-completa y compatible con STARK](https://eprint.iacr.org/2021/1063.pdf) -
  Cairo Whitepaper
- [Una representación algebraica verificada de la ejecución del programa de Cairo](https://arxiv.org/abs/2109.14534) -
  Demostrar la solidez de Cairo utilizando.
  [Aprender a ser asistente de pruebas](<https://en.wikipedia.org/wiki/Lean_(proof_assistant)>)
- [Cairo Playground](https://www.cairo-lang.org/playground/) - Cairo en el navegador
  IDE, ejemplos y rompecabezas.
- [Taller de votación StarkNet](https://starkware.notion.site/starkware/StarkNet-Voting-Workshop-b61ef5f4a62d45af86892cba3158f7e6)-
  Tutorial completo para crear una aplicación de votación.
- [Canal de YouTube](https://www.youtube.com/channel/UCnDWguR8mE2oDBsjhQkgbvg/playlists) - Canal oficial de StarkWare en YouTube.

#### Ecosistema

- [Ecosistema StarkNet](https://starknet-ecosystem.com) -
  Una iniciativa [impulsada por la comunidad](https://github.com/419Labs/starknet-ecosystem.com) para mostrar proyectos y equipos basados en StarkNet.

#### Tutoriales
- [Full-Stack StarkNet](https://github.com/sambarnes/fullstack-starknet) - Tutoriales que introducen un poco de todo en una DApp.
- [Tutoriales interactivos para el desarrollo de StarkNet](https://github.com/onlydustxyz/starklings) - Tutoriales interactivos que enseñan todos los conceptos de Cairo, desde el nivel principiante hasta el avanzado.
- [Pruebas Testing en StarkNet](https://perama-v.github.io/cairo/examples/unit_test/) -
  Usando [`pytest`](https://docs.pytest.org/en/6.2.x/) to test contracts
- [Gestión de las implantaciones de StarkNet mediante Nile⛵️✨](https://medium.com/@martriay/manage-your-starknet-deployments-with-nile-%EF%B8%8F-e849d40546dd)
- [starknet-cairo-101](https://github.com/starknet-edu/starknet-cairo-101) - ITaller interactivo de Cairo utilizando [Voyager](https://voyager.online/) con rompecabezas y fichas como premios.
- [starknet-erc20](https://github.com/starknet-edu/starknet-erc20) - Infórmese sobre el estándar ERC20 y sobre cómo implantar su propio token, y acumule puntos
- [starknet-erc721](https://github.com/starknet-edu/starknet-erc721) - Conozca el estándar ERC721 y cómo implantar su propio NFT.
- [starknet-messaging-bridge](https://github.com/starknet-edu/starknet-messaging-bridge) - Aprende a construir tu propio puente entre Ethereum y StarkNet.
- [starknet-accounts](https://github.com/starknet-edu/starknet-accounts) - Descubra las maravillas de la abstracción contable y cree su propia wallet inteligente.
- [Debugging](https://github.com/starknet-edu/starknet-debug) - Depurar contratos de manera eficaz.

#### Artículos

- [Apostando fuerte - starknet](https://koopxyz.notion.site/going-all-in-starkware-f250983d562c454384384a5408bddf9c)
  Notion de sitio de recursos útiles-
- [Perama's Blog](https://perama-v.github.io/cairo/intro/) - Amplio conjunto de
  recursos educativos StarkNet /  Cairo
- [Lecciones prácticas de StarkNet](https://hackmd.io/@RoboTeddy/BJZFu56wF) -
  Consejos útiles para los nuevos programadores de StarkNet/Cairo.
- [Biblioteca Común de Cairo](https://perama-v.github.io/cairo/cairo-common-library/) -
  Documentación sobre la biblioteca común de El Cairo (equivalente a stdlib).
- [Resumen de los conceptos de Cairo](https://perama-v.github.io/cairo/description/) -
  Visión general de alto nivel de los conceptos encontrados en el ecosistema de  Cairo (Ethereum,
  Contratos Inteligentes, Descentralización, Escalado, L2, Rollups, ZKPs etc.)
- [Abstracción de cuentas](https://perama-v.github.io/cairo/account-abstraction/) -
  Explicación de la abstracción de cuentas de StarkNet
- [Cuentas de Test](https://perama-v.github.io/cairo/examples/test_accounts/) -
  Explicación de la creación de cuentas de prueba.
- [Análisis Static de Amarna](https://blog.trailofbits.com/2022/04/20/amarna-static-analysis-for-cairo-programs/) - Amarna: análisis estático para programas de Cairo.

#### Seguridad

- [Auditoría ChainSecurity DAI Bridge](https://chainsecurity.com/wp-content/uploads/2021/12/ChainSecurity_MakerDAO_StarkNet-DAI-Bridge_audit.pdf) - Auditoría del puente DAI de MakerDAO por ChainSecurity.
- [no-tan-inteligente-cairo](https://github.com/crytic/building-secure-contracts/tree/master/not-so-smart-contracts/cairo) - Ejemplos de vulnerabilidades comunes de los contratos inteligentes de Cairo por Trail of Bits.

#### Ejemplos

- [Cairo con ejemplos](https://perama-v.github.io/cairo/by-example/) - En
  introducción a [Cairo](https://www.cairo-lang.org/) con ejemplos sencillos.
- [Skeleton para StarkNet](https://perama-v.github.io/cairo/examples/building_blocks/skeleton/program_starknet.html)
  - Ejemplo rápido de un programa mínimamente verificable
- [Skeleton para SHARP](https://perama-v.github.io/cairo/examples/building_blocks/skeleton/program_sharp.html)
  - Los programas SHARP difieren de los programas Cairo, esto muestra cómo usar
    SHARP para tus propios despliegues personalizados de Cairo (por ejemplo, si usaras StarkEx)

##### Educacional

- [StarkWare | Escalado de Ethereum, ZK-rollups, Capa 1, ¡y más!](https://youtu.be/aq7EV-4K7Vk) -
  Entrevista con Louis Guthmann, Ecosystem Lead @ StarkWare
- [StarkNet Basecamp](https://github.com/starknet-edu/basecamp) - Descubre cómo funcionan Starks, Cairo y StarkNet, desde cero.

##### Deployando en Starknet Mainnet

- [ZigZagExchange](https://github.com/ZigZagExchange/starknet-contracts) -
  Orderbook DEX
- [physics-puzzle](https://github.com/guiltygyoza/physics-puzzle-starknet) -
  Physics puzzle
- [RYO](https://github.com/dopedao/RYO) - Motor del juego Dope Wars
- [qasr](https://github.com/mortimr/qasr) - ETH <> StarkNet NFT Bridge
- [starknet-dai-bridge](https://github.com/makerdao/starknet-dai-bridge) - ETH
  <> StarkNet DAI Bridge
- [rk4-starknet](https://github.com/guiltygyoza/rk4-starknet) - Runge Kutta 4th
  Método de pedido en StarkNet
- [stardrop](https://github.com/kobigurk/stardrop) - Recompensas anónimas
- [tictactoe](https://github.com/guiltygyoza/tictactoe-on-starknet) - RL Agente
  jugando al tres en raya
- [tiny-dnn-on-starknet](https://github.com/guiltygyoza/tiny-dnn-on-starknet) -
  Red neuronal profunda PoC
- [argent-contracts-starknet](https://github.com/argentlabs/argent-contracts-starknet) -
  Contratos de cuentas de [Argent](https://www.argent.xyz/)
- [briq](https://github.com/briqNFT/briq-protocol) - Protocolo de composición y construcción de NFT
- [Empiric Network](https://github.com/42labs/Empiric) - Oracle proporciona datos descentralizados, transparentes y componibles.

#### Plantillas

- [Contracts Wizard for Cairo](https://wizard.openzeppelin.com/cairo) - Generador interactivo de contratos inteligentes basado en OpenZeppelin Contracts for Cairo. 
- [starknet-hardhat-example](https://github.com/Shard-Labs/starknet-hardhat-example) - Ejemplo de uso del plugin Starknet Hardhat.
  Ejemplo de uso del plugin Starknet Hardhat.
- [starknet-react-example](https://github.com/fracek/starknet-react-example) -
  Conecta tu ReactApp a StarkNet
- [vue-stark-boil](https://github.com/dontpanicdao/vue-stark-boil) - 
  Boilerplate para Argent-X/Vue.js.
- [starknet-scaffold](https://github.com/tarrencev/starknet-scaffold) - Cario scaffold de desarrollo usando nile y pytest

#### Libros

#### Prácricas

#### Trabajo
- [Desarrollador de aplicaciones en Shard labs](https://almanac.io/docs/starknet-dapp-developer-shard-labs-8UMOmydaLJX7jzQAZReYJTcC0o4RtE1m).
- [Desarrollador de código abierto en Open Zeppelin](https://openzeppelin.com/jobs/opening/?gh_jid=4554917003&gh_src=2742d3093us).
- Ingenieros de El Cairo en Immutable](https://discord.com/channels/793094838509764618/898210860030386178/898330663281905725).
- [Chainlink integration team](https://discord.com/channels/793094838509764618/898210860030386178/905842249840074783).
- [Ingeniero de software Blockchain en JellyFi](https://mango-cry-b61.notion.site/Blockchain-software-engineer-9634a0236c454e6ab7679a93478f2f8b).

## Librerías

- [get-starknet](https://github.com/starknet-community-libs/get-starknet) - wallet <-> puente dApp.
- [starknet.js](https://github.com/seanjameshan/starknet.js) - Javascript
  biblioteca
- [starknet.py](https://github.com/software-mansion/starknet.py) - Biblioteca Python
- [starknet-rs](https://github.com/xJonathanLEI/starknet-rs) - Biblioteca Rust
- [starknet-hardhat-plugin](https://github.com/Shard-Labs/starknet-hardhat-plugin) - Complemento para integrar Starknet.
  Un plugin para integrar herramientas Starknet en proyectos Hardhat
- [starknet-jvm](https://github.com/software-mansion/starknet-jvm) - Biblioteca para lenguajes JVM (java, kotlin y otros).
- [cairo-contracts](https://github.com/OpenZeppelin/cairo-contracts) -
  Contratos OpenZeppelin escritos en Cairo.
- [cairomate](https://github.com/a5f9t4/cairomate) - Legos estructurados y fiables para el desarrollo de Starknet. 
- [caigo](https://github.com/dontpanicdao/caigo) - Biblioteca Golang.
- [starknet-react](https://github.com/auclantis/starknet-react) - Biblioteca de ganchos React.

## Herramientas

#### General
- [Braavos](https://chrome.google.com/webstore/detail/braavos-wallet/jnlgamecbpmbajjfhmmmlhejkemejdma) - Billetera de extensión del navegador.
- [argent-x](https://github.com/argentlabs/argent-x) - Monedero de extensión del navegador.
- [cairo_kernel](https://github.com/ankitchiplunkar/cairo-jupyter) - Núcleo Jupyter
  para Cairo.
- [fossil](https://github.com/OilerNetwork/fossil) - Verificación de estado L1 con STARKs.
- [juno](https://github.com/NethermindEth/juno) - Cliente (GoLang).
- [nile](https://github.com/OpenZeppelin/nile) - Herramienta CLI para desarrollar proyectos StarkNet
  proyectos escritos en Cairo por OpenZeppelin
- [protostar](https://docs.swmansion.com/protostar/) - Herramienta CLI para desarrollar y probar contratos en Cairo.
- [starknet-devnet](https://github.com/Shard-Labs/starknet-devnet) - Local
  testnet
- [starkops](https://github.com/seanjameshan/starkops) - CLI de StarkNet
- [voyager](https://voyager.online) - Explorador de bloques.
- [starktx](https://starktx.info/) - Decodificador de transacciones StarkTx.
- [amarna](https://github.com/crytic/amarna) - Analizador estático y linter para el lenguaje de programación Cairo. 
- [tayt](https://github.com/crytic/tayt) - Fuzzer de contratos inteligentes StarkNet.
- [ape-cairo](https://github.com/ApeWorX/ape-cairo) - Plugin compilador para ape para el lenguaje Cairo.
- [ape-starknet](https://github.com/ApeWorX/ape-starknet) - Complemento de Ape para las redes StarkNet.

#### Utilidad

- [warp](https://github.com/NethermindEth/warp) - Transpilador de Solidity a cairo

#### Auditoría

## Editor Plugins

#### Vim

- [cairo.vim](https://github.com/miguelmota/cairo.vim) - (Outdated) vim syntax
  plugin for Cairo

#### Visual Studio Code

- [Cairo VS Code](https://www.cairo-lang.org/docs/quickstart.html#visual-studio-code-setup) -
  Soporte de sintaxis VS Code para Cairo (requiere instalación manual)
- [Cairo language support](https://marketplace.visualstudio.com/items?itemName=ericglau.cairo-ls) -
  Asistencia de código y resaltado de errores de compilación en VS Code.

---

## Licencia

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

En la medida en que la ley lo permita,
[Georgios Konstantopoulos](https://github.com/gakonst) ha renunciado a todos los derechos de autor
y derechos conexos o afines a esta obra.