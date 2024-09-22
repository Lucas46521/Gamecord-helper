# **GAMECORD PTBR**

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/818900078077018162/1042159279597166682/banner.png" alt="gamecord ptbr" />
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/discord-gamecord">
    <img src="https://img.shields.io/npm/dt/discord-gamecord-ptbr?style=for-the-badge" alt="npm" />
  </a>

  <a href="https://discord.gg/invite/GaczkwfgV9">
    <img src="https://img.shields.io/discord/800631529351938089?color=5865F2&label=Aniket&style=for-the-badge" alt="Discord Server" />
  </a>
</p>

> **Discord Gamecord Ptbr é um fork brasileiro para a package: Discord Gamecord que é uma poderosa package com uma coleção de minigames para o seu bot do discord :)**


## **⚙️ Instalação** 
**Para instalar a package gamecord ptbr use o comando abaixo no console:**
```
npm i discord-gamecord-ptbr@latest
```


## **✨ Características**

- Fácil de usar.
- Amigável para iniciantes.
- Jogos de Comandos Slash.
- Todas as mensagens exceto erros em ptbr.


## **📚 Usage**
```js
const { Snake } = require('discord-gamecord-ptbr');

const Game = new Snake({
  message: message,
  isSlashGame: false,
  embed: {
    title: 'Jogo da Cobrinha',
    overTitle: 'Fim de Jogo',
    color: '#5865F2'
  },
  emojis: {
    board: '⬛',
    food: '🍎',
    up: '⬆️', 
    down: '⬇️',
    left: '⬅️',
    right: '➡️',
  },
  stopButton: 'Parar',
  timeoutTime: 60000,
  snake: { head: '🟢', body: '🟩', tail: '🟢', over: '💀' },
  foods: ['🍎', '🍇', '🍊', '🫐', '🥕', '🥝', '🌽'],
  playerOnlyMessage: 'Somente {player} pode usar esses botões.'
});

Game.startGame();
Game.on('gameOver', result => {
  console.log(result);  // =>  { result... }
});
```


## **📷 Preview**
<img src="https://cdn.discordapp.com/attachments/818900078077018162/1042159356780757072/Preview.png">

## **❔ Support**
<a href="https://discord.gg/invite/GaczkwfgV9"><img src="https://invidget.switchblade.xyz/GaczkwfgV9" alt="Discord"></a>
