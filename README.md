# 📌 Fluxograma – Anexar Documentos no TASY (GED)

Este repositório descreve, de forma **simples, visual e objetiva**, o **fluxo que o usuário deve seguir para digitalizar e anexar documentos**  
(**BO, Folha de Sala e Termos**) no sistema **TASY**, utilizando a **Gestão Eletrônica de Documentos (GED)**.

---

## 🎯 Objetivo
Padronizar o processo de **digitalização e anexação de documentos**, facilitando o entendimento dos usuários e reduzindo erros durante a execução da atividade.

---

## 🧭 Fluxograma do Processo

```mermaid
flowchart TD
    A[Início] --> B[Colocar documentos na parte superior da impressora]
    B --> C[Abrir o aplicativo "X" na Área de Trabalho]
    C --> D[Clicar em "Digitalizar"]
    D --> E{Todos os documentos\nforam digitalizados?}
    E -- Não --> D
    E -- Sim --> F[Clicar em "Salvar PDF"]
    F --> G[Definir nome do arquivo e salvar]
    G --> H[Fechar o aplicativo "X"]
    H --> I[Abrir o sistema TASY]
    I --> J[Na árvore do PEP, acessar\nGestão Eletrônica de Documentos - GED]
    J --> K[Sistema direciona automaticamente\npara o PEP/GED]
    K --> L[Clicar no botão "Adicionar"]
    L --> M[Clicar em "Selecionar Arquivo"]
    M --> N[Selecionar o PDF salvo anteriormente]
    N --> O[Salvar]
    O --> P[Documento anexado com sucesso]
