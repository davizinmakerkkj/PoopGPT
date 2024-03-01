# 💩 PoopGPT - Script Injector para ChatGPT 💩
Uma simples extensão para burlar totalmente os filtros de proteção do ChatGPT - OpenAI

## 📔 Sobre
Por bastante tempo, vi pela internet prompts de Bypass / Jailbreak que não funcionavam sendo divulgados. Exemplos deles são o famoso [DAN](https://github.com/0xk1h0/ChatGPT_DAN) ou aqueles [DevMode](https://github.com/0xk1h0/ChatGPT_DAN). Grande parte das pessoas acreditam fielmente que esse é o máximo de capacidade que o ChatGPT pode atingir, mas é aí que eles estão enganados. PoopGPT veio pra mudar a visão sobre bypassers de IA's

-  **Praticidade**: Você não precisará mais ter que ficar colando o mesmo prompt de bypass no começo das frases para que ele continue o assunto do modo desejado. Com PoopGPT, você simplesmente escreve o que bem entender e ele vai ser forçado a responder, independente do que for.
-  **Interface**: PoopGPT é apresentado por uma interface agradável e intuitiva.
-  **Modos**: PoopGPT oferece diversos modos de chat e está frequentemente adicionando modulos novos.
-  **Administração**: PoopGPT é testado diariamente para acompanhar os patchs de proteção impostos pela [OpenAI](https://openai.com/).
-  **Atualização em Tempo Real**: Você não precisa ter que ficar pegando um código novo ou baixando algo novo a cada atualização para usar o PoopGPT. Você pode simplesmente guardar o script atual e usar ele sempre, que ele vai se atualizando automaticamente sem precisar de nenhuma ação do usuário.

## ℹ️ Inject Por Bookmark
Copie o código do script, vá em **Adicionar favorito** do seu navegador, no campo de **URL**, você vai escrever `javascript:`, depois colar o script do PoopGPT na frente e salvar. Assim, quando você clicar no favorito lá em cima, vai rodar o MOD!

## 💉 Como injetar

#### 💻 Pelo Navegador de PC
Para injetar o MOD pelo navegador de PC, você só vai precisar abrir o [ChatGPT](https://chat.openai.com), clicar **F12** ou **CTRL + SHIFT + i** que são atalhos para abrir o DevTools, clicar na parte de **Console** (ou **Terminal** para alguns), colar o código inteiro abaixo e apertar enter!


```bash
var scriptUrl='https://raw.githubusercontent.com/davizinmakerkkj/PoopGPT/main/PoopGPT.txt';fetch(scriptUrl).then(response=>response.text()).then(script=>{var scriptElement=document.createElement('script');scriptElement.innerHTML=script;document.head.appendChild(scriptElement);}).catch(error=>{console.error('Ocorreu um erro ao carregar o script:',error);});
```

#### 📲 Pelo Navegador de Android
Para injetar o MOD pelo navegador do Android, você só vai precisar abrir o [ChatGPT](https://chat.openai.com) pelo navegador [KiwiBrowser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser&hl=pt_BR&gl=US), clicar nos 3 pontos do canto superior direito, descer tudo, clicar em "**Abrir DevTools**", clique no botão de abas e clique no "**DevTools - chat.openai.com/?mod[...]**", depois é só clicar na aba de **Console**, colar o código inteiro acima e apertar enter!

<!--
Eles querem te ver bem, só não melhor que eles

## 🏮 Salves

### ***[Sam](https://discord.com/users/1039768154672472125) e [Basset](https://discord.com/users/667215731280052224) - #NullZ***
--->

## 🛂 Responsabilidade

- 1. ``Ao utilizar este script, você concorda em assumir total responsabilidade por suas ações. Você reconhece que o uso inadequado ou ilegal deste script pode resultar em consequências legais, danos ou prejuízos para terceiros.``

- 2. ``Você concorda em utilizar este script apenas para fins legítimos e éticos, respeitando todas as leis, regulamentos e diretrizes aplicáveis. Você não deve usá-lo para disseminar conteúdo ofensivo, prejudicial, difamatório, ilegal, discriminatório ou que viole os direitos de terceiros.``

- 3. ``Ao utilizar este script, você reconhece que ele é fornecido "como está", sem garantias de qualquer tipo, expressas ou implícitas. Você assume todos os riscos associados ao uso deste script e renuncia a qualquer reivindicação contra o desenvolvedor ou a OpenAI por danos resultantes do seu uso.``

- 4. ``Você concorda em não utilizar este script para contornar ou comprometer a segurança de sistemas, redes ou serviços protegidos. Não é permitido realizar ataques de negação de serviço, invasões de privacidade, exploração de vulnerabilidades ou qualquer atividade maliciosa.``

- 5. ``O desenvolvedor deste script não se responsabiliza por quaisquer danos, perdas ou responsabilidades decorrentes do seu uso. Você concorda em isentar o desenvolvedor e a OpenAI de qualquer responsabilidade relacionada ao uso deste script.``

## 📜 Nota
Não tenho nenhuma relação com a OpenAI. Isto foi escrito para fins educacionais. Use a seu critério.
