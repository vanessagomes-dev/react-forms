# 📅 Formulário de Eventos em React com Validação Avançada

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)
![Yup](https://img.shields.io/badge/Yup-0A0A0A?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)

---

## 💡 Sobre o Projeto

Este projeto é uma demonstração de como criar um **formulário robusto, performático e tipado** em **React**, com foco no **gerenciamento eficiente de estado** via **React Hook Form** e na **validação de esquema de dados** com **Yup**.

---

## ✨ Destaques da Implementação

- **Gerenciamento Otimizado:** Uso do `useForm` do React Hook Form para gerenciar o estado e submissão, evitando re-renders desnecessários.  
- **Validação Declarativa:** Regras de validação claras e tipadas através de um schema do **Yup**.  
- **Integração Perfeita:** Conexão do schema via `yupResolver` (do pacote `@hookform/resolvers`).  
- **Controle Centralizado:** Utilização de `Controller` para inputs complexos (select, textarea etc.), mantendo a coerência do gerenciamento.  
- **Feedback ao Usuário:** Mensagens de erro exibidas dinamicamente abaixo dos campos (`errors.campo?.message`).  

---

## ⚙️ Estrutura do Formulário

O formulário foi projetado para **cadastro de eventos** e inclui os seguintes campos — todos obrigatórios segundo o schema de validação:

| Campo         | Tipo HTML        | Nome no useForm |
|----------------|------------------|-----------------|
| Nome do Evento | `input type="text"` | `name` |
| Data           | `input type="date"` | `date` |
| Assunto        | `select`            | `subject` |
| Descrição      | `textarea`          | `description` |

A função `onSubmit(data)` é responsável por receber o objeto **tipado e validado** após a submissão e **exibi-lo no console**.

---
💡 Futuras Melhorias

🎨 Estilização Profissional: Aplicar Material UI, Chakra UI ou Tailwind CSS.

🌐 Envio para API: Implementar envio de dados simulando uma requisição.

⏳ Indicadores de Loading: Exibir estado de carregamento no botão “Salvar”.

🧪 Testes Unitários: Utilizar @testing-library/react para validar comportamento e erros.

♻️ Reutilização de Componentes: Criar componentes genéricos (<InputField>, <SelectField>) para melhor manutenção do código.
yarn install
````
| Tecnologia              | Descrição                                                     |
| ----------------------- | ------------------------------------------------------------- |
| **React**               | Biblioteca para criação de interfaces reativas e declarativas |
| **TypeScript**          | Superset do JavaScript com tipagem estática                   |
| **Vite**                | Build tool rápida e moderna                                   |
| **React Hook Form**     | Gerenciamento de formulários performático                     |
| **Yup**                 | Biblioteca de validação de esquemas de dados                  |
| **@hookform/resolvers** | Integração direta entre React Hook Form e Yup                 |
````
---
👩‍💻 Desenvolvido por Vanessa Gomes
💼 Projeto focado em boas práticas de formulários e validação em React.
