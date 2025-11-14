# 🔴🟡 Projeto OutSystems – Site Pokémon com PokeAPI

Aplicação web desenvolvida em **OutSystems** consumindo a API pública **[PokeAPI](https://pokeapi.co/)** para exibir e explorar informações sobre **Pokémon**.  
O projeto demonstra na prática desenvolvimento low-code, integração com APIs REST e criação de interfaces web responsivas.

Este repositório contém o arquivo `.oml` do módulo da aplicação.

---

## 📌 Objetivo do Projeto

Criar um **site de Pokémon** em OutSystems que consome dados da **PokeAPI**, com foco em:

- Consumo de APIs REST (PokeAPI)
- Modelagem de dados para armazenar/organizar as respostas da API
- Construção de telas responsivas para listagem e detalhes de Pokémon
- Implementação de filtros, busca e paginação
- Boas práticas de estruturação de módulos OutSystems

---

## 📂 Estrutura do Repositório

- `Pokemon Project.oml`  
  Módulo principal da aplicação Pokémon em OutSystems (telas, integrações, entidades, lógica).

> Para abrir o projeto é necessário utilizar o **OutSystems Service Studio**.

---

## 🧱 Funcionalidades Principais

- **Listagem de Pokémon**
  - Lista de Pokémon obtida dinamicamente da PokeAPI
  - Paginação ou carregamento incremental (por página/offset)
  - Exibição de informações básicas (nome, número, imagem, tipos)

- **Detalhes do Pokémon**
  - Tela com detalhes completos do Pokémon selecionado:
    - Tipos
    - Altura, peso, stats
    - Imagens/sprites
  - Dados carregados em tempo real via PokeAPI

- **Busca e Filtros**
  - Busca por nome ou número do Pokémon
  - Possíveis filtros por tipo (Fire, Water, Grass, etc.)

- **Interface Web Responsiva**
  - Layout adaptado para desktop e mobile
  - Uso de padrões de UI do OutSystems para uma experiência fluida

---

## 🌐 Integração com a PokeAPI

O projeto se integra à API pública [PokeAPI](https://pokeapi.co/).

### Endpoints típicos utilizados (exemplo)

- `GET https://pokeapi.co/api/v2/pokemon?offset={offset}&limit={limit}`  
  Para obter uma lista paginada de Pokémon.

- `GET https://pokeapi.co/api/v2/pokemon/{id or name}`  
  Para obter os detalhes de um Pokémon específico.

### Exemplo de configuração de REST API no OutSystems (pseudo-configuração)

```text
Base URL: https://pokeapi.co/api/v2

Method: GET
Endpoint: /pokemon
Inputs: offset (Query), limit (Query)
Outputs: Lista de resultados e URL para próxima página

🚀 Como Abrir e Executar o Projeto (OutSystems)
Instale/acesse o OutSystems Service Studio
Baixe o Service Studio e faça login com a sua conta OutSystems.
Importe o módulo
Abra o Service Studio
Vá em: File → Open → From File...
Selecione o arquivo:
Pokemon Project.oml
Configure (se necessário)
Verifique se o ambiente tem acesso à internet para chamar a PokeAPI.
Ajuste eventuais configurações de timeout ou proxies (se a sua infra exigir).
Publique e execute
Clique em 1-Click Publish
Após publicar, clique em Open in Browser ou acesse o link da aplicação gerado pelo OutSystems.
🧩 Requisitos
Conta/ambiente OutSystems (Pessoal, Cloud ou corporativo)
OutSystems Service Studio instalado
Acesso à internet para consumir a PokeAPI
Navegador web atualizado para acessar o site
🗺️ Modelo Conceitual (exemplo)
Um modelo conceitual típico para este projeto pode incluir entidades como:

Pokemon – dados principais do Pokémon (nome, número, imagem, etc.)
PokemonType – tipos do Pokémon (Fire, Water, Grass, etc.)
PokemonStat – atributos (HP, Attack, Defense, Speed, etc.)
As entidades podem ser:

Somente temporárias (apenas para armazenar a resposta da API na tela), ou
Persistentes (caso você queira cache/local storage de Pokémon no banco do OutSystems).
🎯 Aprendizados e Tecnologias
Plataforma: OutSystems
Tipo de App: Web
Tecnologias e conceitos:
OutSystems (low-code)
Consumo de APIs REST
Tratamento de JSON
Modelagem de dados
UI responsiva
Publicação e debug de módulos
📧 Contato
Se quiser trocar ideias sobre o projeto, melhorias ou dúvidas:

Autor: shakarpg
GitHub: https://github.com/shakarpg 
