# MASH-MD

Bot Baileys WhatsApp desenvolvido em Node.js com ES Modules por Dev Pedrux.

---
Dono: Pedrux
WhatsApp: +55 73 8861-0011
GitHub: github.com/Dev-Pedrux
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
git clone https://github.com/Dev-Pedrux/MASH-MD
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
