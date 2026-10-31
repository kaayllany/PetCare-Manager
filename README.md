<div align="center">

# 🐾 PetCare Manager

**Tela de gerenciamento de usuários para um sistema de clínica veterinária, desenvolvida com React**

![React](https://img.shields.io/badge/React-2F855A?style=for-the-badge&logo=react&logoColor=white)
&nbsp;&nbsp;
![JavaScript](https://img.shields.io/badge/JavaScript-2F855A?style=for-the-badge&logo=javascript&logoColor=white)
&nbsp;&nbsp;
![Figma](https://img.shields.io/badge/HTML5-2F855A?style=for-the-badge&logo=html5&logoColor=white)
&nbsp;&nbsp;
![CSS3](https://img.shields.io/badge/CSS3-2F855A?style=for-the-badge&logo=css3&logoColor=white)
&nbsp;&nbsp;

[Sobre](#-sobre-o-projeto) •
[Funcionalidades](#-funcionalidades) •
[Tecnologias](#-tecnologias-utilizadas) •
[Como executar](#-como-executar) •
[Preview](#-preview) •
[Acesso por função](#-acesso-por-função) •
[Roadmap](#-próximos-passos) •
[Autora](#-autora)

</div>

---

## 📖 Sobre o projeto

O **PetCare Manager** é um projeto acadêmico que simula parte de um sistema para clínicas veterinárias. Esta primeira etapa foca na **tela de gerenciamento de usuários**, onde é possível visualizar e administrar quem utiliza o sistema (como recepcionistas, veterinários e administradores).

### 🎯 Objetivos

- Praticar **componentização** com React
- Trabalhar **estado** (`useState`) e **renderização de listas**
- Construir uma interface organizada e fácil de usar
- Criar a base para as próximas telas do sistema (pets, tutores e consultas)

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 👥 **Listagem** | Exibe todos os usuários cadastrados |
| ➕ **Cadastro** | Permite adicionar novos usuários |
| ✏️ **Edição** | Atualiza os dados de um usuário existente |
| 🗑️ **Remoção** | Exclui usuários da lista |

## 🛠️ Tecnologias utilizadas

| Tecnologia | Uso no projeto |
|---|---|
| **React** | Construção da interface em componentes reutilizáveis |
| **JavaScript (ES6+)** | Lógica da aplicação e manipulação de estado |
| **HTML5** | Estrutura das páginas |
| **CSS3** | Estilização e layout |
| **Node.js / npm** | Ambiente de execução e gerenciamento de dependências |

## 🚀 Como executar

**Pré-requisito:** ter o [Node.js](https://nodejs.org/) instalado (versão LTS recomendada).

```bash
# 1. Clone o repositório
git clone https://github.com/kaayllany/petcare-manager.git

# 2. Acesse a pasta do projeto
cd petcare-manager

# 3. Instale as dependências
npm install

# 4. Inicie a aplicação
npm start
```

A aplicação abrirá automaticamente em **http://localhost:3000**.

## 📸 Preview

<!-- Salve os prints na pasta assets/ e ajuste os nomes dos arquivos abaixo -->

<div align="center">

![Tela de usuários](assets/preview.png)

*Tela de gerenciamento de usuários*

</div>

## 🔐 Acesso por função

Protótipos interativos do sistema, um para cada perfil de usuário. Clique no link abaixo para ver o acesso e as credenciais de login de cada função.

- [Gerente](./gerente.md)
- [Recepcionista](./recepcionista.md)
- [Veterinário](./veterinario.md)
- [Auxiliar Veterinário](./auxiliar-veterinario.md)
- [Caixa/Financeiro](./caixa-financeiro.md)
- [Especialista de Higiene](./especialista-higiene.md)

## 📂 Estrutura do projeto

<!-- Ajuste para refletir a estrutura real do seu projeto -->

```
petcare-manager/
├── public/
├── src/
│   ├── components/     # Componentes reutilizáveis
│   ├── App.js
│   └── index.js
├── assets/             # Imagens do README
├── package.json
└── README.md
```

## 🗺️ Próximos passos

- [ ] Integrar com banco de dados / API
- [ ] Tela de cadastro de pets e tutores
- [ ] Agendamento de consultas
- [ ] Autenticação de usuários

## 💡 Aprendizados

- Divisão da interface em componentes menores e reutilizáveis
- Uso de estado para atualizar a tela em tempo real
- Renderização dinâmica de listas com `map()`
- Organização de um projeto React do zero

## 📫 Autora

<div align="center">

**Kaylany Thayna**
Estudante de Análise e Desenvolvimento de Sistemas · UNICID

[![LinkedIn](https://img.shields.io/badge/LinkedIn-2F855A?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaylany-thayna)
&nbsp;&nbsp;
[![E-mail](https://img.shields.io/badge/E--mail-2F855A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kaylanythayna@hotmail.com)

</div>





