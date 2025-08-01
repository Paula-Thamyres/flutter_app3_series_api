# 📱 app_series_flutter_api

Aplicativo criado com **Flutter** que consome uma **API de séries**, exibindo uma grade com informações detalhadas. O app permite favoritar títulos, alternar entre telas e gerenciar estados de forma eficiente e completa.

Desenvolvido por [Paula-Thamyres](https://github.com/Paula-Thamyres)

---

## 🧱 Estrutura do Projeto

### `lib/models/serie_model.dart`

Define a estrutura de dados da série por meio da **classe `SerieModel`**, contendo os principais atributos:

- `id`
- `titulo`
- `imagem`
- Outros campos vindos da API

A classe utiliza um **factory constructor** para mapear automaticamente os dados JSON para objetos Dart.

---

## 🛠️ Ferramentas e Recursos Utilizados

- 🎯 **Dart** — Linguagem principal para estruturação lógica e manipulação dos dados da aplicação  
- 🐦 **Flutter** — Framework para construção da interface gráfica e experiência multiplataforma  
- 📡 **HTTP (package)** — Utilizado para realizar requisições REST e consumir dados da API de séries  
- ⚙️ **Gerenciamento de Estado** — Aplicado inicialmente com `setState`, com melhorias sendo feitas com `Provider`  
- 🧩 **Componentes Personalizados** — Diversos widgets construídos para modularização e reutilização da interface  
- 💾 **SQLite** — Banco de dados local integrado para armazenar e manipular favoritos com persistência offline

---

## 🗃️ Funcionalidades Recentes

- 🗂️ **CRUD com SQLite**  
  Implementado banco de dados local para gerenciamento de séries favoritas. Permite:
  - 🔍 Inserir
  - ✏️ Atualizar
  - 🗑️ Remover
  - 📄 Listar

- 📊 **Ordenação Inteligente**  
  Na tela de favoritos, o usuário pode selecionar a forma de visualização da lista:
  - 🔤 **Ordem Alfabética**
  - ⭐ **Ordenação por Nota**

Esses filtros melhoram a experiência de navegação e controle das séries armazenadas localmente.

---

## 💡 Observações Finais

Este projeto está em constante evolução. A refatoração com `Provider` segue em progresso para aprimorar o controle de estado global da aplicação.

Fique à vontade para contribuir, sugerir melhorias ou relatar problemas.  
Confira mais projetos no meu perfil: [github.com/Paula-Thamyres](https://github.com/Paula-Thamyres)

---
