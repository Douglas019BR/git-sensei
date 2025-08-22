🇧🇷 [Português](./LESSON_THREE.md) | 🇺🇸 [English](../LESSON_THREE.md)

# Lição 3: Fazendo Fork e Contribuindo para Projetos 🍴

## O que Você Vai Aprender 🎯
Nesta lição, você aprenderá como contribuir para projetos existentes:
- Fazendo fork de repositórios
- Fazendo mudanças
- Criando pull requests

## O que é Fork? 🤔
Fazer fork cria uma cópia pessoal do projeto de outra pessoa. Permite que você experimente livremente com mudanças sem afetar o projeto original.

## Guia Passo a Passo 📝

### 1. Faça Fork de um Repositório 🍴
1. Vá para o repositório do GitHub para o qual você quer contribuir
2. Clique no botão "Fork" no canto superior direito da página
3. Selecione onde fazer fork do repositório (geralmente sua conta pessoal)
4. Aguarde o GitHub criar seu fork

### 2. Clone Seu Fork 📥
```bash
# Substitua USUARIO pelo seu nome de usuário do GitHub
# Substitua REPOSITORIO pelo nome do repositório
git clone https://github.com/USUARIO/REPOSITORIO.git

# Navegue para a pasta do repositório
cd REPOSITORIO
```

### 3. Crie um Branch 🌿
```bash
# Crie um novo branch para suas mudanças
git checkout -b minha-nova-funcionalidade

# Isso é uma abreviação para:
# git branch minha-nova-funcionalidade
# git checkout minha-nova-funcionalidade
```

### 4. Faça Mudanças ✏️
1. Adicione ou modifique arquivos no seu repositório local
2. Crie um novo arquivo ou edite os existentes

### 5. Faça Commit das Suas Mudanças 💾
```bash
# Adicione suas mudanças ao stage
git add .

# Faça commit com uma mensagem descritiva
git commit -m "Adicionar nova funcionalidade: descrição das mudanças"
```

### 6. Envie para Seu Fork 📤
```bash
git push origin minha-nova-funcionalidade
```

### 7. Crie um Pull Request 🔄
1. Vá para seu fork no GitHub
2. Clique no botão "Compare & pull request"
3. Certifique-se de que o repositório base é o original e o repositório head é seu fork
4. Adicione um título e descrição explicando suas mudanças
5. Clique em "Create pull request"

## Melhores Práticas para Pull Requests 🌟
- Mantenha as mudanças focadas e específicas
- Escreva mensagens de commit claras
- Siga as diretrizes de contribuição do projeto
- Seja responsivo ao feedback e esteja preparado para fazer mudanças adicionais

## Exercício Prático 🏋️💻
1. Vá para o repositório [SendScriptWhatsApp](https://github.com/Douglas019BR/SendScriptWhatsApp). Este repo é uma coleção de scripts para enviar mensagens grandes no WhatsApp linha por linha.
2. Faça fork do repositório
3. Adicione um arquivo simples seguindo o modelo dos [arquivos existentes](https://github.com/Douglas019BR/SendScriptWhatsApp/tree/main/scripts)
4. Faça commit do seu arquivo e crie um pull request para o repositório original
5. Interaja com qualquer feedback que receber

Lembre-se, contribuir para projetos de código aberto é uma ótima maneira de melhorar suas habilidades e se juntar à comunidade de desenvolvedores! 🚀

## Problemas Comuns e Soluções 🔧

### Fork Não Aparece
- Atualize a página após fazer fork
- Verifique se o fork foi criado na sua conta

### Conflitos no Pull Request
- Seu branch pode estar atrasado em relação ao branch principal
- Puxe as últimas mudanças do repositório original antes de criar seu PR

### Permissão Negada
- Certifique-se de estar enviando para seu fork, não para o repositório original
- Verifique suas credenciais de autenticação

## Parabéns! 🎉

Você completou o curso Git Sensei! Agora você tem as habilidades fundamentais para:
- Usar Git para controle de versão
- Trabalhar com repositórios do GitHub
- Colaborar com outros desenvolvedores
- Contribuir para projetos de código aberto

Continue praticando essas habilidades, e você se tornará um verdadeiro mestre do Git! 🥋

## Problemas e Suporte 🆘

Em caso de problemas, use a [seção de issues](https://github.com/Douglas019BR/git-sensei/issues) para fazer perguntas ou reportar um problema. Esta é uma boa prática e é usada pela maioria dos repositórios. Também é uma boa prática pesquisar issues existentes antes de criar uma nova, caso alguém tenha feito a mesma pergunta ou similar. Você pode tentar a mesma solução ou responder com um comentário na issue existente.

## O que Vem Depois?

- Explore funcionalidades mais avançadas do Git como `git stash`, `git cherry-pick`, e `git bisect`
- Aprenda sobre fluxos de trabalho do Git como GitFlow ou GitHub Flow
- Pratique contribuindo para projetos reais de código aberto
- Considere aprender sobre integração e implantação contínua (CI/CD)
