# 🌳 Respirômetro
### Sistema de Georeferenciamento de Árvores Urbanas

> Projeto Final — Curso Full Stack | Coude Escola de Programação  
> Desenvolvido em equipe de 3 pessoas · 2024

---

## 💡 Sobre o Projeto

O **Respirômetro** é um sistema web colaborativo para mapeamento e monitoramento de árvores urbanas, com o objetivo de melhorar a qualidade do ar nas cidades.

A ideia surgiu de uma pesquisa simples: **o ideal é que existam 3 árvores para cada habitante de uma cidade**. Com base nisso, o sistema permite que qualquer cidadão cadastre árvores próximas a ele, contribuindo para que gestores e a própria comunidade possam visualizar quais bairros têm déficit de arborização — e agir para melhorar isso.

---

## 🖥️ Telas do Sistema

### Dashboard Principal
![Dashboard](./screenshots/dashboard.jpeg)
*Visão geral com total de árvores cadastradas, índice de qualidade do ar, usuários ativos, ranking de contribuidores e mapa interativo.*

### Mapa de Localização das Árvores
![Mapa](./screenshots/mapa.jpeg)
*Cada árvore cadastrada aparece georreferenciada no mapa em tempo real usando Leaflet + OpenStreetMap.*

### Painel de Árvores Cadastradas
![Painel de Árvores](./screenshots/painel-arvores.jpeg)
*Listagem completa com nome, espécie, coordenadas (latitude/longitude), status de saúde e data de cadastro.*

### Painel de Gerenciamento
![Gerenciamento](./screenshots/painel-gerenciamento.jpeg)
*Área do usuário logado com opções de cadastrar nova árvore, ver suas contribuições e gerenciar o perfil.*

---

## ⚙️ Funcionalidades

- ✅ Cadastro e autenticação de usuários
- ✅ Cadastro de árvores com **captura automática de geolocalização** do dispositivo
- ✅ Mapa interativo com todas as árvores cadastradas (Leaflet + OpenStreetMap)
- ✅ Dashboard público com índice de qualidade do ar calculado dinamicamente
- ✅ Ranking dos top 5 usuários com mais contribuições
- ✅ Painel administrativo com listagem, filtros e detalhes por árvore
- ✅ Controle de status de saúde de cada exemplar (saudável, doente, seco)
- ✅ API REST com rotas GET e POST para consumo dos dados

---

## 🛠️ Tecnologias Utilizadas

| Camada | Tecnologia |
|--------|-----------|
| Back-end | PHP (MVC) + Composer |
| Front-end | HTML5, CSS3, JavaScript |
| Banco de Dados | MySQL |
| Mapa | Leaflet.js + OpenStreetMap |
| Arquitetura | MVC com API REST |
| Versionamento | Git + GitHub |

---

## 👥 Divisão da Equipe

| Desenvolvedor | Responsabilidade |
|---------------|-----------------|
| **Marcos Wellerson** | Back-end completo: arquitetura MVC, API REST, autenticação, lógica de negócio e integração com banco de dados |
| Colega 1 | Front-end: interfaces, componentes visuais e integração com a API |
| Colega 2 | Banco de dados: modelagem relacional, queries e estrutura do bd_respirometro.sql |

---

## 📁 Estrutura do Projeto

```
respirometro/
├── api/
│   ├── get/          # Endpoints de leitura
│   └── post/         # Endpoints de escrita
├── assets/
│   ├── img/
│   ├── cabecalho.css
│   └── login-cadastro.css
├── painel/           # Área logada do usuário
├── public/           # Arquivos públicos
├── src/
│   ├── Componentes/  # Componentes reutilizáveis
│   ├── Controller/   # Controllers MVC
│   ├── Model/        # Models MVC
│   └── recursos/
├── Uploads/
├── vendor/           # Dependências Composer
├── composer.json
├── bd_respirometro.sql
└── index.php
```

---

## 🔒 Sobre o Repositório

O código-fonte deste projeto pertence à instituição de ensino **Coude Escola de Programação**, onde foi desenvolvido como projeto final de curso. Por isso, o repositório está disponível apenas como portfólio visual.

---

## 👨‍💻 Desenvolvedor Back-end

**Marcos Wellerson da S. Brandão**  
🔗 [linkedin.com/in/marcos-brandaodev](https://linkedin.com/in/marcos-brandaodev)  
💻 [github.com/Marcos-Brandao](https://github.com/Marcos-Brandao)
