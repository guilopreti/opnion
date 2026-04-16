# Opnion! 📰💡

> _"Site de criação e postagem de notícias e artigos, com objetivo de compartilhar ideias e buscar informações com mais facilidade e segurança."_

Bem-vindo(a) ao repositório do **Opnion!** Este é um portal colaborativo onde usuários podem publicar, descobrir e até revisar notícias e artigos sobre diversos temas, como Tecnologia e Mundo.

Acesse em: https://opnion.vercel.app/

## 🚀 Funcionalidades

O projeto oferece uma jornada completa para os leitores e escritores:

- **Feed de Notícias:** Explore artigos em destaque ou separados por categorias.
- **Autenticação:** Crie sua conta e faça login com segurança.
- **Criação de Artigos:** Escreva novas postagens e compartilhe sua opinião.
- **Revisão de Artigos:** Sistema de aprovação para garantir a qualidade das postagens no fórum.
- **Gerenciamento de Perfil:** Atualize suas informações pessoais e sua imagem de perfil.
- **Busca Dinâmica:** Encontre posts específicos rapidamente na página principal.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias e conceitos do ecossistema front-end:

- **[React.js](https://reactjs.org/)** - Biblioteca principal de UI.
- **[Styled-Components](https://styled-components.com/)** - Estilização baseada em componentes (CSS in JS).
- **React Router Dom** - Para roteamento e navegação entre páginas.
- **Context API** - Para o gerenciamento global de estados (Usuários, Autenticação, Posts, Loading).
- **Axios** - Integração de API.
- **[JSON-Server](https://github.com/typicode/json-server)** - Simulando uma REST API para o back-end (hospedada no _Render_).

## ⚠️ Sobre a API (Aviso Importante)

A base de dados e a API que alimentam os artigos deste site são providas por um servidor próprio (`json-server`) hospedado no **Render** (no plano gratuito).

Devido à política desse tipo de hospedagem, **o servidor entra em estado de hibernação (sleep) após um tempo sem acessos**.
Isso significa que:

- Ao abrir o site pela primeira vez em muito tempo, os dados podem **demorar até 1 minuto ou mais** para aparecer e carregar completamente.
- Para melhorar essa experiência, foi implementado um **Loading State** que visa avisar o usuário de forma amigável sempre que ocorrer uma demora na resposta do servidor.

Tenha um pouquinho de paciência e as notícias aparecerão! :)

## 📦 Como rodar este projeto?

Siga os passos abaixo para executar a versão local do Front-End na sua máquina.

1. **Clone este repositório**

   ```bash
   git clone https://github.com/SEU_USUARIO/opnion.git
   ```

2. **Acesse a pasta do projeto**

   ```bash
   cd opnion
   ```

3. **Instale as dependências**

   ```bash
   npm install
   # ou yarn install
   ```

4. **Inicie a aplicação front-end**
   ```bash
   npm start
   # ou yarn start
   ```
   A aplicação estará disponível em `http://localhost:3000`.

---
