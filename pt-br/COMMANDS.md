🇧🇷 [Português](./COMMANDS.md) | 🇺🇸 [English](../COMMANDS.md)

# Comandos do Git

Pense nestes comandos como feitiços mágicos que você pode usar para controlar o histórico do seu projeto.

## As Três Áreas

Antes de aprendermos os comandos, você precisa saber sobre as três áreas secretas onde seu trabalho vive:

1. **O Diretório de Trabalho:** Este é seu playground! É onde você cria e edita seus arquivos. (local)
2. **A Área de Staging:** É como uma sala de espera. Antes de salvar seu trabalho, você o coloca na área de staging para prepará-lo. (local antes de ser enviado)
3. **O Repositório (ou Repo):** Este é o baú do tesouro onde você armazena todas as versões salvas do seu projeto. (remoto)

---

## Comandos Básicos

### `git init`

- **O que faz:** Este é o primeiro feitiço que você lança. Ele cria um novo baú do tesouro vazio (repositório) na pasta do seu projeto.
- **Como usar:** `git init`

### `git diff`

- **O que faz:** Este feitiço mostra a diferença entre os arquivos que você modificou e os arquivos originais. Isso mostra as mudanças que você fez.
- **Como usar:**
  - `git diff <nome_do_arquivo>` (para ver a diferença em um arquivo)
  - `git diff` (para mostrar todas as diferenças no seu novo trabalho)

### `git add`

- **O que faz:** Este feitiço move seu trabalho do seu playground (Diretório de Trabalho) para a sala de espera (Área de Staging).
- **Como usar:**
  - `git add <nome_do_arquivo>` (para adicionar um arquivo)
  - `git add .` (para adicionar todo seu novo trabalho) Cuidado com isso—não é uma boa prática adicionar todos os arquivos de uma vez porque você pode adicionar alguns arquivos que mudou sem querer e não vai revisar essas mudanças antes de adicionar ao stage. Não é proibido, mas use com cuidado.

### `git commit`

- **O que faz:** Este é o feitiço mais importante! Ele pega tudo na sala de espera (Área de Staging) e salva como uma nova versão no seu baú do tesouro (Repositório). Você também deixa uma mensagem para lembrar o que mudou. O commit criará um checkpoint no histórico de versões!
- **Como usar:** `git commit -m "Sua mensagem descritiva aqui"`
- **Exemplo:** `git commit -m "feat-1234 Criar um middleware para tratamento de erros"`

### `git status`

- **O que faz:** Este feitiço te diz o que está acontecendo no seu projeto. Ele mostra quais arquivos são novos, quais foram alterados, e quais estão prontos para serem salvos.
- **Como usar:** `git status`

### `git log`

- **O que faz:** Este feitiço mostra todas as versões que você salvou no seu baú do tesouro (Repositório). É como olhar uma linha do tempo do seu projeto. É como um histórico de commits.
- **Como usar:** `git log`

---

## Comandos Intermediários

### `git branch`

- **O que faz:** Imagine que seu projeto é uma árvore. Um branch é um novo caminho que você pode tomar para testar novas ideias sem alterar o tronco principal da árvore. Você pode fazer o que quiser no seu branch—não se preocupe! Contanto que você não envie essas mudanças para branches oficiais (dev, main, master... cada projeto tem os seus), o código é só seu.
- **Como usar:**
  - `git branch` (para ver todos os branches)
  - `git branch <nome_do_branch>` (para criar um novo branch)

### `git checkout`

- **O que faz:** Este feitiço permite que você alterne entre diferentes branches ou versões do seu projeto.
- **Como usar:** `git checkout <nome_do_branch>`

### `git merge`

- **O que faz:** Depois que você trabalhou em um branch e está feliz com suas mudanças, você pode usar este feitiço para combinar seu branch de volta ao tronco principal da árvore. Eu realmente recomendo fazer o merge no console (GitHub ou GitLab) porque você pode revisar as mudanças e (agora) usar agentes de IA Generativa para revisar suas mudanças também.
- **Como usar:** `git merge <nome_do_branch>`

---

## Comandos Avançados (para quando você for um mago do Git!)

### `git pull`

- **O que faz:** Se você está trabalhando com amigos no mesmo projeto, este feitiço busca as últimas mudanças de um baú do tesouro remoto (como no GitHub) e as mescla no seu projeto local.
- **Como usar:** `git pull`

### `git push`

- **O que faz:** Este feitiço envia suas mudanças salvas do seu baú do tesouro local para um baú do tesouro remoto (como no GitHub) para que seus amigos possam ver seu trabalho.
- **Como usar:** `git push`

### `git rebase`

- **O que faz:** Este é um feitiço poderoso que permite reescrever o histórico do seu projeto. É como voltar no tempo e mudar a ordem dos eventos. Use este com cuidado!
- **Como usar:** `git rebase <nome_do_branch>`

### `git clone`

- **O que faz:** Este feitiço faz uma cópia de um baú do tesouro remoto (como do GitHub) no seu próprio computador.
- **Como usar:** `git clone <url_do_repositorio>`

## O que Vem Depois?

Agora que você conhece os comandos básicos, vamos aprender sobre alguns conceitos mais avançados que farão de você um mestre do Git!

- [Conceitos Avançados do Git](./ADVANCED_CONCEPTS.md)
