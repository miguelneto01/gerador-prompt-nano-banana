<h1 align="center">🍌 Gerador de Prompt para Nano Banana</h1>

<p align="center">
  Suba uma foto de referência e receba um <b>prompt detalhado</b> pronto para colar no Nano Banana (Gemini),
  preservando o seu rosto. <b>100% no navegador — sem API, sem chave, sem servidor.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/100%25-no%20navegador-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/sem%20API-sem%20chave-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" />
</p>

---

## ✨ O que é

Uma ferramenta web que **lê uma imagem de referência** (cena, pose, estilo) e gera um **prompt detalhado**
para você usar no **Nano Banana** junto da sua própria selfie. O modelo recria a cena mantendo o seu rosto.

## 🔒 Como funciona (e por que é privado)

A leitura da imagem roda **inteiramente no seu navegador**, usando um modelo de visão via
[Transformers.js](https://huggingface.co/docs/transformers.js). Ou seja:

- **Sua foto nunca sai do seu dispositivo** — nada é enviado a um servidor.
- **Não precisa de chave de API** nem de conta.
- Na **primeira vez**, o navegador baixa o modelo (alguns MB); depois fica em cache e funciona até offline.

## 🚀 Como usar

1. Abra a página (link do GitHub Pages abaixo).
2. Suba uma **foto de referência** (o visual que você quer imitar).
3. Escolha um **estilo** e, se quiser, adicione ajustes.
4. Clique em **Gerar prompt** e **copie** o resultado.
5. No Nano Banana, envie **a sua selfie** + o prompt copiado.

## 🌐 Acessar

> Ative o **GitHub Pages** nas configurações do repositório (Settings → Pages → Branch `main`).
> O link fica assim: `https://SEU-USUARIO.github.io/gerador-prompt-nano-banana/`

## 🧩 Stack

- HTML + CSS + JavaScript puro (sem build, sem dependências de servidor)
- [Transformers.js](https://github.com/xenova/transformers.js) para visão no navegador

## ⚠️ Uso responsável

Use apenas com **fotos suas ou de pessoas que autorizaram**. Não recrie o rosto de terceiros sem consentimento.

## 📄 Licença

[MIT](LICENSE) © Miguel Neto
