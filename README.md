# GIT E Java

## Ao criar Repositório no GitHub usando o Bash

echo "# TESTE" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/ricardo-engenharia/nomeDoRepositorioCriado.git

git push -u origin main

## …or push an existing repository from the command line

git remote add origin https://github.com/ricardo-engenharia/nomeDoRepositorioCriado.git

git branch -M main

git push -u origin main


## Liks para instalar JDK e outros 
[Como instalar no Windows e Linux](https://giters.com/cami-la/curso-dio-dominando-ides-java)


# Atalhos do IntelliJ Idea
[Atalhos URL](http://www.basef.com.br/index.php/Atalhos_do_IntelliJ_Idea)

### Geral

Alt + 1: Focar aba de projetos

Alt + Shift + Insert: Alterna entre modo de seleção de linha/coluna

Ctrl + Shift + F12: Expandir a tela

Na aba de projetos

Alt + Insert: Para criar um novo arquivo

Templates de código

psvm: Criar método main

sout: System.out.println()

Ctrl + Alt + C: Cria constante (precisa estar sobre código que permite atribuição)

Ctrl + Alt + F: Cria field - propriedade da classe (precisa estar sobre código que permite atribuição)

Ctrl + Alt + V: Cria variável (precisa estar sobre código que permite atribuição)

Ctrl + Alt + T: Templates de IF, for, while, etc (precisa selecionar o código antes)

Ctrl + J: Exibe todos os templates disponíveis

Na aba de código

Ctrl + Y: Apaga a linha inteira

Ctrl + D: Duplicar linha atual

Alt + Shift + Setas: Mover linha atual

Ctrl + Shift + Setas: Mover linha atual mantendo contexto

Ctrl + Shift + A: Find Action - mostra todas as ações da IDE em uma lista

Ctrl + N: Busca rápida de classes

Ctrl + Shift + N: Busca rápida de arquivos

Ctrl + B: Inspecionar elemento - go to class, method, declaration, etc

Ctrl + Alt + L: Reformatar código

Ctrl + Alt + M: Extrair método - transforma código selecionado em método

Shift + F6: Renomeia classe, variável, método, etc

Ctrl + Shift + F6: Usar referência de outra classe

Shift & Shift: Search everywhere

Ctrl + Shift + F: Busca por conteúdo de arquivo

Alt + Enter: Intention actions

Alt + Insert: Generate shortcut

Ctrl + F12: Mostra a estrutura do arquivo - por exemplo, exibe métodos de uma classe

Alt + F7: Find usages - mostra a lista de quem está chamando o método, usando a variável, etc

Ctrl + G: Ir para linha

Ctrl + H: Mostrar hierarquia da classe (classes pais)

Alt + Home: Ir para a barra de navegação

Ctrl + P: Mostrar parâmetros do método

Ctrl + Q: Documentação rápida

Ctrl + / ou Ctrl + Shift + /: Comentar código

Ctrl + Shift + Alt + T: Métodos de refatoração

Ctrl + Alt + O: Reajustar imports da classe (remove imports não utilizados)
