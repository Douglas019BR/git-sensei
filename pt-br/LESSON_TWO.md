🇺🇸 [English](../LESSON_TWO.md) | 🇧🇷 [Português](./LESSON_TWO.md)

# Lição 2: Trabalhando com Repositórios Remotos 🌐

## O que Você Vai Aprender 🎯
Nesta lição, você aprenderá como:
- Conectar seu repositório local ao GitHub
- Fazer push e pull de mudanças
- Clonar repositórios existentes

## GitHub: Git na Nuvem ☁️
GitHub é uma plataforma que hospeda repositórios Git online, facilitando:
- Fazer backup do seu código
- Colaborar com outros
- Compartilhar seus projetos com o mundo
- Contribuir para software de código aberto

## Criando uma Conta no GitHub 📝
1. Vá para [github.com](https://github.com)
2. Cadastre-se para uma conta gratuita
3. Verifique seu endereço de email

## Criando um Novo Repositório no GitHub 🆕
1. Clique no ícone "+" no canto superior direito
2. Selecione "New repository"
3. Nomeie seu repositório
4. Adicione uma descrição opcional
5. Escolha público ou privado
6. Clique em "Create repository"

## Conectando Seu Repositório Local ao GitHub 🔗
Use o repositório local criado na lição um.

```bash
# Adicione um remote
git remote add origin https://github.com/USUARIO/REPOSITORIO.git

# Verifique se o remote foi adicionado
git remote -v
```

## Enviando Seu Código para o GitHub 📤

```bash
# Envie seus commits para o GitHub
git push -u origin main

# Após o primeiro push, você pode simplesmente usar:
git push
```

## Clonando um Repositório Existente 📥
Explore projetos do GitHub como você explora redes sociais. Pesquise por temas, pessoas, tecnologias, leia o README.md dos projetos, deixe sua curiosidade te guiar. Escolha um projeto para clonar—qualquer projeto.

```bash
# Clone um repositório do GitHub
git clone https://github.com/USUARIO/REPOSITORIO.git

# Isso cria um novo diretório com o nome do repositório
```

## Puxando Mudanças do GitHub 🔄

```bash
# Obtenha mudanças do GitHub
git pull origin main
```

## Trabalhando com Branches 🌿

```bash
# Crie um novo branch
git branch feature-branch

# Mude para o branch
git checkout feature-branch

# Ou crie e mude em um comando
git checkout -b feature-branch

# Envie o branch para o GitHub
git push -u origin feature-branch
```

## Exercício Prático 🏋️♀️
1. Crie um novo repositório no GitHub
2. Conecte seu repositório local da Lição 1
3. Envie seu código para o GitHub
4. Faça mudanças no GitHub (edite um arquivo diretamente no site)
5. Puxe as mudanças para seu repositório local
6. Crie um novo branch, faça mudanças, e envie para o GitHub

## Problemas Comuns e Soluções 🔧

### Falha na Autenticação
- Certifique-se de estar usando o nome de usuário e senha corretos
- Considere usar chaves SSH ou um token de acesso pessoal para mais segurança

### Push Rejeitado
- Seu repositório local pode estar atrasado em relação ao remoto
- Tente puxar mudanças primeiro com `git pull`

Lembre-se, GitHub torna a colaboração possível e fornece um backup do seu código. É uma ferramenta essencial para desenvolvedores modernos! 🚀

## O que Vem Depois?

Agora que você conhece o GitHub, vamos aprender sobre como contribuir para um projeto.

- [Terceira lição](./LESSON_THREE.md)
