# 🏨 Projeto Outsystem – Aplicação de Hotel

Projeto desenvolvido no **bootcamp da DIO** utilizando a plataforma **OutSystems**, com foco em criação rápida de aplicações web, modelagem visual de dados e boas práticas de UX.

Este repositório contém os ficheiros `.oml` do módulo da aplicação, bem como imagens de apoio ao modelo conceitual e à interface.

---

## 📌 Objetivo do Projeto

Construir uma aplicação de **gestão de reservas de hotel** em OutSystems, praticando:

- Modelagem de dados (conceitual e lógica)
- Criação de interfaces Web responsivas
- Implementação de fluxos de negócio (reservas, hóspedes, quartos)
- Boas práticas de organização de módulos OutSystems

---

## 📂 Estrutura do Repositório

- `Hotel.oml`  
  Módulo inicial de teste  da aplicação de hotel em OutSystems.

- `HotelRafa.oml`  
  Versão final do módulo .

- `conceitual.png`  
  Diagrama conceitual do domínio (Entidades: Hóspede, Quarto, Reserva, etc.).

- `icone.png`  
  Ícone utilizado na aplicação (branding do módulo ou da app).

---

## 🧱 Funcionalidades Principais (esperadas)

> Obs.: A depender da versão do módulo que você abrir, os nomes das telas/entidades podem variar, mas o fluxo geral é semelhante.

- **Gestão de Hóspedes**
  - Cadastro, edição e listagem de hóspedes
  - Visualização de detalhes de cada hóspede

- **Gestão de Quartos**
  - Cadastro de quartos (número, tipo, status)
  - Controle de disponibilidade

- **Reservas**
  - Criação de reservas associando hóspede e quarto
  - Período de check-in e check-out
  - Listagem e consulta de reservas existentes

- **Interface Web**
  - Páginas responsivas construídas com os padrões OutSystems
  - Navegação simples e intuitiva para o usuário final

---

## 🚀 Como Abrir o Projeto (OutSystems)

1. **Instale/acesse o OutSystems Service Studio**
   - Faça login na sua conta OutSystems.

2. **Importe o módulo**
   - Abra o **Service Studio**
   - Vá em: `File` → `Open` → `From File...`
   - Selecione o ficheiro desejado:
      - `HotelRafa.oml`

3. **Publique e execute**
   - Clique em **1-Click Publish**
   - Após publicar, abra a aplicação no browser usando o link gerado pelo OutSystems (ou clicando em **Open in Browser** no Service Studio).

---

## 🧩 Requisitos

- Conta/ambiente OutSystems (Pessoal, Cloud ou o ambiente fornecido pela DIO)
- OutSystems **Service Studio** instalado
- Acesso à internet para publicar e testar a aplicação

---

## 🗺️ Modelo Conceitual

O diagrama em `conceitual.png` representa as principais entidades do domínio, por exemplo:

- `Hóspede` – dados pessoais do cliente
- `Quarto` – número, tipo, capacidade, status
- `Reserva` – ligação entre Hóspede e Quarto, datas de entrada/saída

Use esse diagrama como referência para compreender o desenho da base de dados e a lógica das telas.

---

## 🎯 Aprendizados e Tecnologias

- **Plataforma:** OutSystems  
- **Tipo de App:** Web  
- **Conceitos praticados:**
  - Modelagem de dados
  - CRUD (Create, Read, Update, Delete)
  - Navegação entre telas
  - Padrões de UI OutSystems
  - Publicação e debug de módulos

---

## 📸 Screenshots

As imagens incluídas neste repositório (`hotel.png`, `icone.png`) podem ser usadas para documentação, apresentação ou portfólio:

- ![tela principal](./conceitual.png)
 exemplo de tela principal / fluxo da aplicação
- ![icone](./icone.png)
 
 ícone da aplicação (pode ser usado no tema/branding)

---

## 📧 Contato

Caso queira trocar ideia sobre o projeto, melhorias ou dúvidas:

- Autor: **@shakarpg**
- GitHub: [github.com/shakarpg](https://github.com/shakarpg)

---

> Sinta-se à vontade para abrir *issues* ou fazer *fork* deste repositório para criar sua própria versão da aplicação de hotel no OutSystems.
