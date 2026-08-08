# Aula 3 - Revisão e Colaboração

## Git e GitHub

O Git é um sistema de controle de versão utilizado para registrar e acompanhar as alterações realizadas em um projeto. Ele permite manter um histórico dos arquivos e recuperar versões anteriores quando necessário.

O GitHub é uma plataforma que utiliza o Git para hospedar repositórios na internet. Ele facilita o armazenamento, compartilhamento e desenvolvimento colaborativo de projetos.

## Processo de trabalho no GitHub

Um processo básico de trabalho com Git e GitHub pode seguir as seguintes etapas:

1. Criar ou clonar um repositório.
2. Criar ou modificar os arquivos do projeto.
3. Verificar as alterações realizadas utilizando `git status`.
4. Adicionar os arquivos para preparação utilizando `git add`.
5. Registrar as alterações utilizando `git commit`.
6. Enviar as alterações para o GitHub utilizando `git push`.
7. Atualizar o projeto local utilizando `git pull` quando houver alterações no repositório remoto.

Um exemplo de sequência de comandos é:

```bash
git status
git add .
git commit -m "Adiciona conteúdo da aula 3"
git push