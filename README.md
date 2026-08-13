## Dominando Git e GitHub
Projeto colaborativo para construir um site de várias páginas usando **Git** (no terminal) e **GitHub** (no navegador), com fluxo de trabalho baseado em **branches** e **Pull Requests** com **revisão obrigatória**.

## Equipe
- - **Tema do site:** Nossos Hobbies Favoritos
- **Participantes:**
  - Bruno Vinicius Alves Azevedo — @brunorisadas (papel: integrador) — página: `paginas/aluno-BRUNOVINICIUS.html`
  - Caio Campelo Rocha — @caiorochacampelo-collab (papel: documentador) — página: `paginas/aluno-CAIOCAMPELO.html`
  - Isabella Araújo de Omena — @isabellaomena (papel: arquiteta) — página: `paginas/aluno-ISABELLAOMENA.html`
  - Lukas Theodoro Fernandes — @lukastheodoro07 (papel: revisor-chefe) — página: `paginas/aluno-LUKASTHEODORO.html`
  - Miguel Henrique Alves de Oliveira — @miguelh19max (papel: integrador) — página: `paginas/aluno-MIGUELHENRIQUE.html`
  - Pietra Rodrigues Guimarães — @pietrarg (papel: documentadora) — página: `paginas/aluno-PIETRARODRIGUES.html`

## Sobre
Aqui você encontra:
- Construir um site em equipe, onde **cada pessoa é dona de uma página sobre seus hobbies favoritos!**
- Juntar o trabalho de todo mundo sem bagunça usando:
  - branches (cada um trabalha separado)
  - Pull Requests (para pedir revisão)
  - aprovação de colega (ninguém aprova o próprio PR)
  - merge na `main` (somente quando aprovado)

## Papéis (responsabilidades)
Além de criar a própria página, cada pessoa assume um papel:

- **Arquiteto(a):** cria o repositório, convida a equipe e protege a branch `main`
- **Revisor(a)-chefe:** garante que todo PR tem revisor e avisa o Integrador quando estiver aprovado
- **Integrador(a):** faz o merge dos PRs aprovados
- **Documentador(a):** escreve este `README.md`
- **Versionador(a) (opcional):** ajuda a publicar e marca a versão final com `git tag`

## Círculo de revisão
Cada pessoa revisa o PR do **colega seguinte** (e é revisada pelo colega anterior).  
Regra: **ninguém aprova o próprio PR** — precisa de pelo menos 2 pessoas no círculo.

## Onde cada coisa é feita
- **CMD/Terminal:** baixar, salvar e enviar arquivos (`git clone`, `add`, `commit`, `push`, `pull`)
- **Navegador (github.com):** colaboração (`Pull Request`, pedir revisão, aprovar, merge)

## Pré-requisitos (uma vez por computador)
1. Instale o Git for Windows: https://git-scm.com/downloads  
   Na opção do PATH, escolha: **“Git from the command line and also from 3rd-party software”**
2. Configure seu nome e e-mail (use o mesmo e-mail da conta GitHub):

## Como abrir / usar
### Ler no GitHub
Abra as pastas acima e siga os READMEs/arquivos de cada parte.

## Estrutura do site
- `index.html` — página inicial do site
- `paginas/` — páginas individuais de cada integrante  
  Ex.: `paginas/aluno-SEUNOME.html`

## Fluxo de trabalho (passo a passo)
### 1) Clonar o repositório (cada pessoa)

### 2) Criar sua branch (nunca trabalhar direto na `main`)

### 3) Criar sua página (no editor)
Crie e salve:
- `paginas/aluno-SEUNOME.html`

### 4) Salvar mudanças no Git

### 5) Enviar sua branch para o GitHub
Na primeira vez, é normal o Git abrir login no navegador.

### 6) Abrir Pull Request e pedir revisão (no navegador)
- Clique em **Compare & pull request** (ou vá em **Pull requests → New pull request**)
- Base: `main` | Compare: `seu-nome`
- Em **Reviewers**, escolha o colega do seu círculo
- Clique em **Create pull request**

### 7) Aprovar PR do colega (cada pessoa)
- Abra o PR do colega
- Aba **Files changed**
- **Review changes → Approve**
- Escreva um comentário (elogio + sugestão)
- **Submit review**

### 8) Merge (só o Integrador(a), quando aprovado)
- No PR aprovado: **Merge pull request → Confirm merge**
- Se o botão estiver cinza, falta aprovação.

### 9) Atualizar sua cópia com o trabalho de todos

## Como abrir o site
### Opção A — Abrir localmente
Abra o arquivo `index.html` no navegador.

### Opção B — Site publicado (GitHub Pages)
O link fica em **Settings → Pages** (depois de publicar).  
**Link do site:**: https://isabellaomena.github.io/DominandoGiteGithub/

## Se algo der errado (atalhos)
- `'git' não é reconhecido` → reinstale o Git escolhendo a opção correta de PATH
- `403 / permission denied` no push → você não aceitou o convite de colaborador
- Botão Merge cinza → falta aprovação no PR
- Abriu editor estranho no terminal no commit → você esqueceu `-m`  
  Saia com `Esc`, digite `:q!` e Enter, e refaça o commit com `-m`
