# Libertad Technology — site

Site da **Libertad Technology** · *Desenvolvendo aplicações inteligentes*.

Sites, agendamento online, cardápio digital e painel de gestão para barbearias, salões, lancherias, pizzarias e prestadores de serviço.

## O que tem no site

- Abertura animada com o símbolo da marca
- Fundo vivo com partículas que reagem ao mouse e aurora em movimento
- Título com palavra que troca sozinha (site próprio, agenda online, cardápio digital, painel de gestão)
- Celular 3D que inclina com o mouse e mostra notificações ao vivo
- Cartões com luz que segue o cursor e inclinação 3D
- Botões que pulsam e brilham, botões magnéticos e cursor personalizado
- **3 demos em tela cheia** (abrem com transição circular a partir do clique):
  - Agenda da barbearia: serviço, profissional, dia e horário, com confete na confirmação
  - Cardápio da lancheria: monta o pedido e mostra como ele chega no WhatsApp
  - Painel do dono: indicadores e gráfico animados
- "Monte o seu projeto": o visitante escolhe o que quer e envia tudo pronto pelo WhatsApp
- Linha do tempo que se preenche ao rolar, perguntas frequentes e WhatsApp flutuante
- Funciona no celular, respeita quem prefere menos animação e tem navegação por teclado

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `libertad-site`), **público**.
2. Envie o arquivo `index.html` (e este `README.md`) para o repositório: botão **Add file › Upload files**.
3. Vá em **Settings › Pages**.
4. Em **Source**, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e clique em **Save**.
5. Em 1 ou 2 minutos o site fica no ar em `https://SEU-USUARIO.github.io/libertad-site/`.

### Domínio próprio (opcional)

Em **Settings › Pages › Custom domain**, digite o domínio (ex.: `libertad.com.br`) e configure o DNS no registro do domínio conforme o GitHub indicar.

## Personalizar

- **Número do WhatsApp:** no fim do `index.html`, procure `var WA = '5554996928531';`.
- **Mensagens do WhatsApp:** cada botão tem o texto no atributo `data-wa="..."`.
- **Cores:** no começo do CSS, em `:root` (`--amarelo`, `--laranja`, `--laranja2`, `--bg`).
