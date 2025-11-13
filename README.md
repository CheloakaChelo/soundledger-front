# SoundLedger Front-end
Arquitetura front-end para projeto de TCC que consiste em um sistema baseado em blockchain para direitos autorais em músicas.

Este é o repositório oficial do frontend da plataforma SoundLedger. O projeto é um sistema web desenvolvido em React.js que utiliza tecnologia blockchain para fornecer um monitoramento transparente da distribuição de royalties musicais para artistas, compositores e produtores.

A aplicação se conecta a um backend Spring Boot para autenticação de usuários e gerenciamento de dados.

---

## ✨ Funcionalidades Principais

* **Autenticação de Usuários:** Sistema completo de Cadastro e Login de usuários (Artistas, Produtores, etc.) utilizando **JWT (JSON Web Token)** para segurança.
* **Perfil de Usuário:** Página de perfil que exibe as informações do usuário (nome) e uma lista de suas músicas cadastradas.
* **Dashboard de Royalties:** Exibe um resumo financeiro com:
    * Total de royalties arrecadados (convertidos de ETH para BRL em tempo real).
    * Total de músicas registradas pelo usuário.
    * Total de plays/visualizações das músicas.
    * Tabela detalhada com o saldo em ETH de cada música.
* **Cadastro de Músicas:** Formulário dinâmico para registrar novas músicas, permitindo ao usuário adicionar múltiplos "Detentores de Direitos" (participantes) e seus respectivos *splits* (percentuais).

---

## 🛠️ Tecnologias Utilizadas

* **React.js:** Biblioteca principal para a construção da interface de usuário.
* **React Router DOM:** Para gerenciamento de rotas (Login, Cadastro, Perfil, Dashboard, etc.).
* **Axios:** Cliente HTTP para fazer todas as chamadas à API do backend (Spring Boot).
* **jwt-decode:** Utilizado para extrair informações do payload do JWT (como o ID do usuário e suas *roles*) diretamente no frontend.
* **CSS:** Para estilização dos componentes.

---

# Back-end do sistema
https://github.com/CheloakaChelo/SoundLedger-API.git
