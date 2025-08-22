🇧🇷 [Português](./LESSON_ONE.md) | 🇺🇸 [English](../LESSON_ONE.md)

# Lição 1: Introdução ao Git e GitHub 👋

## O que é Git? 🤷♂️
Git é um sistema de controle de versão distribuído que ajuda você a rastrear mudanças no seu código. Ele permite que múltiplas pessoas trabalhem no mesmo projeto sem interferir no trabalho umas das outras.

## Por que Usar Git? 🎯
- Rastrear mudanças no seu código ao longo do tempo
- Colaborar com outros sem conflitos
- Manter diferentes versões do seu projeto
- Reverter para versões anteriores se necessário
- Trabalhar offline e sincronizar depois

## Começando 🚀

### Instalação 💻
```bash
# Para Ubuntu/Debian
sudo apt install git

# Para macOS (usando Homebrew)
brew install git

# Para Windows
# Baixe de https://git-scm.com/download/win
```

### Configuração Básica ⚙️
```bash
# Defina seu nome de usuário
git config --global user.name "Seu Nome"

# Defina seu email
git config --global user.email "seu.email@exemplo.com"
```

### Criando Seu Primeiro Repositório 📁
```bash
# Crie um novo diretório
mkdir meu-primeiro-projeto
cd meu-primeiro-projeto

# Inicialize um repositório Git
git init
```

### Entendendo o Fluxo de Trabalho Básico 🔄

1. **Diretório de Trabalho**: Onde você cria, edita, exclui e organiza arquivos
2. **Área de Staging**: Onde você prepara mudanças para um commit
3. **Repositório**: Onde o Git armazena permanentemente mudanças como commits

### Comandos Básicos 📝

```bash
# Verifique o status do seu repositório
git status

# Adicione arquivos à área de staging
git add nomedarquivo.txt   # Adicionar um arquivo específico
git add .                  # Adicionar todos os arquivos

# Faça commit das suas mudanças
git commit -m "Minha primeira mensagem de commit"

# Visualize o histórico de commits
git log
```

## Exercício Prático 🏋️💻
1. Crie um novo repositório
2. Adicione um arquivo README.md com uma breve descrição
3. Faça commit do arquivo
4. Faça mudanças no README.md
5. Faça commit das mudanças
6. Visualize seu histórico de commits

Lembre-se, Git é uma ferramenta poderosa que fica mais fácil com a prática. Não se preocupe se parecer complicado no início—vamos construir suas habilidades passo a passo! 🌱

## Problemas e Suporte 🆘

Em caso de problemas, use a [seção de issues](https://github.com/Douglas019BR/git-sensei/issues) para fazer perguntas ou reportar um problema. Esta é uma boa prática e é usada pela maioria dos repositórios. Também é uma boa prática pesquisar issues existentes antes de criar uma nova, caso alguém tenha feito a mesma pergunta ou similar. Você pode tentar a mesma solução ou responder com um comentário na issue existente.

## O que Vem Depois?

Agora que você conhece os comandos básicos, vamos continuar explorando este mundo fantástico.

- [Segunda lição](./LESSON_TWO.md)
