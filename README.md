<!-- Perfil do GitHub · Caiosmp -->

<div align="center">

<img src="./assets/caio-header.svg" width="100%" alt="Caio Sampaio — Desenvolvedor, Engenharia de Software. Interesses: backend e aplicações web, bots e automações, segurança de software." />

<br />

<a href="https://www.linkedin.com/in/caio-sampaio-tx10"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-161B22?style=for-the-badge&logo=linkedin&logoColor=8ED7CA" /></a>
<a href="mailto:caiosampaio.044@gmail.com"><img alt="E-mail" src="https://img.shields.io/badge/E--mail-161B22?style=for-the-badge&logo=gmail&logoColor=8ED7CA" /></a>
<a href="https://www.instagram.com/caioo_smp/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-161B22?style=for-the-badge&logo=instagram&logoColor=8ED7CA" /></a>

</div>

<br />

## Sobre

Comecei com projetos menores e fui pegando gosto por entender o que acontece por trás de uma aplicação: a organização do código, a persistência dos dados, as permissões e as integrações.

Já desenvolvi **bots para Discord**, sistemas de cadastro e **automações que tiram tarefas repetitivas do caminho**. Hoje meu foco está em **backend, aplicações web e segurança de software**.

<br />

## Projetos

<a href="https://www.linkedin.com/in/caio-sampaio-tx10">
  <img src="./assets/marketplace.svg" width="100%" alt="Marketplace: plataforma de e-commerce multi-tenant em NestJS, Next.js, React, TypeScript, Prisma e PostgreSQL. Repositório privado; código e demonstração sob pedido." />
</a>

<table>
  <tr>
    <th width="33%" align="left">Multi-tenant</th>
    <th width="33%" align="left">Segurança</th>
    <th width="34%" align="left">Pagamentos e operação</th>
  </tr>
  <tr>
    <td valign="top">
      <sub>
      Cada loja com catálogo, equipe, clientes e pagamentos isolados<br /><br />
      Subdomínio próprio e domínio personalizado com verificação por TXT e HTTPS automático<br /><br />
      Nome, cores, domínio e produtos são configuração, não código
      </sub>
    </td>
    <td valign="top">
      <sub>
      Refresh token rotativo com detecção de reuso<br /><br />
      2FA por e-mail com limite de tentativas e confirmação de senha em ações sensíveis<br /><br />
      Cargos OWNER, MANAGER e STAFF, exceções por pessoa e auditoria do painel<br /><br />
      CPF nunca salvo em texto puro
      </sub>
    </td>
    <td valign="top">
      <sub>
      Pix via Mercado Pago e cartão via Stripe Connect<br /><br />
      Webhooks com validação de assinatura e idempotência<br /><br />
      Reembolso total ou parcial, expiração de pedidos e nota fiscal via NFe.io<br /><br />
      Importação por CSV, entrega de produtos digitais e backup com dados mascarados
      </sub>
    </td>
  </tr>
</table>

<details>
  <summary><b>Decisões de projeto e stack completa</b></summary>
  <br />

- **Lojista e comprador são contas completamente separadas.**
- **Pedidos guardam uma cópia do que foi comprado**, então alterar um produto não muda o histórico de vendas.
- **Permissões sem cache, por enquanto.**
- **Proteção em camadas nos endpoints públicos.**
- **Variáveis de ambiente validadas com Zod** na inicialização da API.

| Camada | Tecnologias |
|:--|:--|
| Backend | NestJS 11 · TypeScript · Prisma 7 · PostgreSQL (Supabase) |
| Frontend | Next.js 16 · React 19 |
| Infra | Vercel · Supabase Storage · Resend · Cloudflare Turnstile |
| Pagamentos e fiscal | Mercado Pago · Stripe Connect · NFe.io |
| Testes | Jest · Vitest |

</details>

<br />

<div align="center">
  <a href="https://github.com/Caiosmp/Validador-de-Comprovante"><img width="49%" alt="Validador de Comprovante" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Caiosmp&repo=Validador-de-Comprovante&locale=pt-br&bg_color=0D1117&title_color=8ED7CA&text_color=9CAAB4&icon_color=F2C46D&border_color=30363D" /></a>
  <a href="https://github.com/Caiosmp/BotFeedback"><img width="49%" alt="BotFeedback" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Caiosmp&repo=BotFeedback&locale=pt-br&bg_color=0D1117&title_color=8ED7CA&text_color=9CAAB4&icon_color=F2C46D&border_color=30363D" /></a>
  <a href="https://github.com/Caiosmp/Sasc"><img width="49%" alt="Sasc" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Caiosmp&repo=Sasc&locale=pt-br&bg_color=0D1117&title_color=8ED7CA&text_color=9CAAB4&icon_color=F2C46D&border_color=30363D" /></a>
  <a href="https://github.com/Caiosmp/2FA"><img width="49%" alt="2FA" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Caiosmp&repo=2FA&locale=pt-br&bg_color=0D1117&title_color=8ED7CA&text_color=9CAAB4&icon_color=F2C46D&border_color=30363D" /></a>
</div>

> [!NOTE]
> Também colaboro no [**Nexo**](https://github.com/DevGuijas/Nexo), um aplicativo de suporte e diagnóstico para Windows, com issues, pull requests e revisão de código em equipe.

<br />

## Stack

<table>
  <tr>
    <td width="50%" valign="top">
      <sub><b>LINGUAGENS</b></sub><br /><br />
      <img src="https://skillicons.dev/icons?i=ts,js,java,python,html,css" alt="TypeScript, JavaScript, Java, Python, HTML e CSS" />
    </td>
    <td width="50%" valign="top">
      <sub><b>FRAMEWORKS</b></sub><br /><br />
      <img src="https://skillicons.dev/icons?i=nestjs,nextjs,react,spring" alt="NestJS, Next.js, React e Spring Boot" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <sub><b>DADOS</b></sub><br /><br />
      <img src="https://skillicons.dev/icons?i=postgres,prisma,supabase" alt="PostgreSQL, Prisma e Supabase" />
    </td>
    <td width="50%" valign="top">
      <sub><b>FERRAMENTAS</b></sub><br /><br />
      <img src="https://skillicons.dev/icons?i=docker,vercel,git,vscode,postman,figma,jest,vitest&perline=8" alt="Docker, Vercel, Git, VS Code, Postman, Figma, Jest e Vitest" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <sub><b>IA NO DIA A DIA</b></sub><br /><br />
      <img src="./assets/stack-ia.svg" alt="Claude, Cursor, Codex, Gemini e DeepSeek" />
    </td>
    <td width="50%" valign="top">
      <sub><b>GESTÃO</b></sub><br /><br />
      <img src="./assets/stack-gestao.svg" alt="Jira e Trello" />
    </td>
  </tr>
</table>

<br />

## Em números

<sub>Atualizado automaticamente a partir da minha atividade no GitHub.</sub>

<div align="center">
  <img width="49%" alt="Estatísticas do GitHub" src="https://denvercoder1-github-readme-stats.vercel.app/api?username=Caiosmp&locale=pt-br&show_icons=true&include_all_commits=true&count_private=true&hide=stars&rank_icon=github&hide_border=true&bg_color=0D1117&title_color=8ED7CA&text_color=C9D1D9&icon_color=F2C46D" />
  <img width="49%" alt="Linguagens mais usadas" src="https://denvercoder1-github-readme-stats.vercel.app/api/top-langs/?username=Caiosmp&locale=pt-br&layout=compact&langs_count=6&hide=scss,css,html&exclude_repo=DucatiSite-Prova,markdown-badges,readme-templates,Caiosmp&hide_border=true&bg_color=0D1117&title_color=8ED7CA&text_color=C9D1D9" />
  <br /><br />
  <img alt="Sequência de contribuições" src="https://streak-stats.demolab.com?user=Caiosmp&locale=pt_BR&hide_border=true&background=0D1117&ring=8ED7CA&fire=F2C46D&currStreakNum=F3F6F8&sideNums=F3F6F8&currStreakLabel=8ED7CA&sideLabels=9CAAB4&dates=6E7681&stroke=30363D" />
</div>

<details>
  <summary><b>Ver gráfico de atividade dos últimos 30 dias</b></summary>
  <br />
  <img width="100%" alt="Gráfico de atividade" src="https://github-readme-activity-graph.vercel.app/graph?username=Caiosmp&bg_color=0D1117&color=9CAAB4&line=8ED7CA&point=F2C46D&area=true&area_color=8ED7CA&hide_border=true&custom_title=Atividade%20recente" />
</details>
