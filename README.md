# 🚀 Projeto: Integração Azure Data Factory + Azure DevOps

## 📘 Visão Geral

Este projeto demonstra como integrar o **Azure Data Factory** ao **Azure DevOps**, permitindo o **versionamento automático de pipelines**, controle de mudanças e **backups de artefatos de dados**. Essa integração traz organização, rastreabilidade e prepara o ambiente para futuras automações de CI/CD.

---

## 🎯 Objetivos

- Conectar o Azure Data Factory a um repositório Git no Azure DevOps  
- Versionar pipelines e artefatos automaticamente  
- Trabalhar com controle de versões e histórico de alterações  
- Visualizar arquivos diretamente no repositório Git  
- Adotar boas práticas de colaboração e governança

---

## 🛠️ Etapas do Projeto

### 1. Criar Organização e Projeto no Azure DevOps

- Acesse [dev.azure.com](https://dev.azure.com)
- Crie sua organização e um novo projeto

📸 *Imagem da criação do projeto no DevOps*

---

### 2. Configurar Repositório Git

- Acesse "Repos" no projeto DevOps
- Crie ou use um repositório Git existente
- Defina a branch principal (ex: `main`)

📸 *Imagem da tela de repositório no Azure DevOps*

---

### 3. Conectar o Azure Data Factory ao Git

- Crie um novo recurso Azure Data Factory
- Durante a criação ou posteriormente, selecione a opção "Configurar Git"
- Escolha Azure DevOps, organização, projeto, repositório e branch (`adf_publish` por exemplo)

📸 *Imagem da configuração Git no ADF*

---

### 4. Salvar e Publicar Pipelines

- No ADF Studio, edite ou crie pipelines
- Clique em **Salvar** (vai para o Git)
- Clique em **Publicar** (envia para a branch de publicação)

📸 *Imagem do botão de salvar/publicar no ADF*

---

### 5. Visualizar Arquivos Versionados no Git

- Acesse o DevOps > Repos
- Visualize os arquivos JSON (pipelines, datasets, linked services)
- Acompanhe os commits e alterações

📸 *Imagem dos arquivos no repositório Git*

---

## ✅ Resultados

- Pipelines versionados automaticamente
- Histórico de alterações completo
- Organização e governança para o time de dados
- Base pronta para futuras automações com CI/CD

---

## 📌 Recursos Úteis

- [Documentação Oficial - Azure Data Factory + Git](https://learn.microsoft.com/pt-br/azure/data-factory/source-control)  
- [Azure DevOps](https://dev.azure.com/)  
- [Microsoft Learn - Data Factory](https://learn.microsoft.com/pt-br/training/modules/introduction-data-factory/)  

---
