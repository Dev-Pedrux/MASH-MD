# MASH-MD

Bot Baileys WhatsApp desenvolvido em Node.js com ES Modules por Dev Pedrux.

---

## Criador

**Dev Pedrux** — 

Estudo programação com foco em desenvolvimento de bots, sites e servidores Linux.
amo Hoodtrap, meu objetivo é me tornar
um desenvolvedor completo, e o MASH-MD é prova de que está no caminho certo.

O bot nasceu de uma motivação simples: eu sempre vi outros devs com seus próprios bots e
quis ter o meu. eu também criei a MASH API's, minha própria
infraestrutura de API que alimenta o bot inteiro.

WhatsApp: +55 73 8861-0011
GitHub: github.com/pedro-bots
API: blueninha.shop

---

## Estrutura do meu Bot 

```
MASH-MD/
├── index.js
├── package.json
├── lib/
│   ├── config.js          configurações gerais do bot
│   ├── commands.js        loader e executor de comandos
│   └── storage.js         banco de dados local
├── data/
│   └── menus/
│       ├── dono.js
│       ├── adm.js
│       └── membro.js
├── src/
│   ├── services/
│   │   ├── youtube.js     download YouTube
│   │   ├── tiktok.js      download TikTok
│   │   ├── pinterest.js   download Pinterest
│   │   └── logos.js       geração de logotipos
│   └── commands/
│       ├── member/        comandos para todos
│       ├── admin/         comandos para admins
│       └── owner/         comandos só do dono
└── sessao/                sessão do WhatsApp (gerado automaticamente)
```

---

## como instalar

```bash
git clone https://github.com/pedro-bots/MASH-MD
cd MASH-MD
npm install
npm start
```

---

## minha config.js

Edite `lib/config.js`:

```js
export default {
  nomebot: 'MASH-MD',
  prefixo: '.',
  dono: 'SEU_NUMERO',
  donoLid: 'SEU_LID',
  api_url: 'https://blueninha.shop'
}
```

Use o comando `.lid` no grupo para descobrir seu LID.

---

## 📄 Licença

Copyright © 2025 Dev Pedrux. Todos os direitos reservados.

Este software é de uso privado. É proibido copiar, distribuir, vazar ou republicar este código sem autorização prévia por escrito do autor. O descumprimento sujeita o infrator às penalidades previstas na Lei nº 9.610/1998 e no Art. 184 do Código Penal Brasileiro.

Contato: +55 73 8861-0011
