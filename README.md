# GCS - Atividade 4

Repositório criado para a atividade de **Gerência de Configuração de Software (GCS).  

---

## Estrutura do Projeto

- **Versão 1** → Arquivo `app.js` com um simples `console.log("Olá Mundo");`  
- **Versão 2** → Função `dizerOla(nome)` para saudar diferentes usuários.  
- **Versão 3** → Modularização do código em `saudacao.js`, exportando funções e importando no `app.js`.  
- **Feature Branch** → Criada a branch `feature-nova`, adicionando a função `bomDia(nome)`.

---

##Arquivos Principais

- `app.js` → Arquivo principal que executa o programa.  
- `saudacao.js` → Módulo responsável pelas funções de saudação.  

---

## Fluxo de Desenvolvimento

1. Inicialização do repositório e **commit da versão 1**.  
2. Evolução para a **versão 2** (função `dizerOla`).  
3. Evolução para a **versão 3** (modularização com `saudacao.js`).  
4. Criação de **branch de feature** (`feature-nova`) para incluir novas funcionalidades.  

---

## Comandos Git Utilizados

```bash
# Iniciar repositório
git init

# Adicionar remoto
git remote add origin https://github.com/zSkiver/GCS.git

# Adicionar e commitar alterações
git add .
git commit -m "Mensagem do commit"

# Enviar para o GitHub
git push origin main

# Criar e trocar para uma branch
git checkout -b feature-nova
