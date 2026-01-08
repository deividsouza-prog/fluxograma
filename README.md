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
    A[Inicio] --> B[Colocar documentos na impressora]
    B --> C[Abrir aplicativo X no computador]
    C --> D[Clicar em Digitalizar]
    D --> E{Documentos digitalizados?}
    E -- Nao --> D
    E -- Sim --> F[Salvar em PDF]
    F --> G[Definir nome do arquivo]
    G --> H[Fechar aplicativo X]
    H --> I[Abrir sistema TASY]
    I --> J[Acessar GED na arvore do PEP]
    J --> K[Abrir tela do PEP GED]
    K --> L[Clicar em Adicionar]
    L --> M[Selecionar arquivo PDF]
    M --> N[Salvar documento]
    N --> O[Documento anexado]
