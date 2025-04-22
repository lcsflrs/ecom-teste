# 🧪 Teste Técnico – Estágio em Engenharia de Software

## 🎯 Objetivo
Consumir a [API do The Movie DB (TMDb)](https://developer.themoviedb.org/docs/getting-started), processar os dados dos **250 filmes mais bem avaliados**, gerar métricas e disponibilizá-las de forma organizada.

---

## ✅ Regras Gerais

- Você pode usar qualquer linguagem ou framework.
- O uso de IA (como ChatGPT, GitHub Copilot, etc.) é **permitido**, desde que:
  - Seja informado no README.
  - Os **links ou prints** das conversas sejam incluídos na entrega.
- As **features abaixo são opcionais** e possuem uma pontuação.  
  Escolha as que você considera mais valiosas e organize seu tempo com base nisso.
- Seu planejamento será avaliado junto com a entrega.
- Entregue via repositório (GitHub, GitLab, etc).

---

## 📦 API para usar

- **Top Rated Movies:**  
  https://developer.themoviedb.org/reference/movie-top-rated-list

- **Trending Movies:**  
  https://developer.themoviedb.org/reference/trending-movies

---

## 📊 Features (Pontuação)

### 1. Conectar-se com a API da TMDb – **(Obrigatório)**
- Autenticar-se e buscar os 250 filmes top-rated (paginar manualmente se necessário)

### 2. Média de Nota por Gênero – _5 pontos_
- Calcular e exibir a **nota média** dos filmes para cada gênero (ex: Ação: 7.9, Drama: 8.2...)

### 3. Quantidade de Filmes por Gênero – _3 pontos_
- Mostrar quantos filmes de cada gênero existem nos 250 top-rated

### 4. Quantidade de Filmes por Ano – _4 pontos_
- Mostrar a distribuição dos filmes por ano de lançamento, **ordenado cronologicamente**

### 5. Quantos e quais desses filmes estão entre os Trending nos últimos 6 meses – _5 pontos_
- Obter os filmes em alta (trending-movies)
- Verificar **quantos dos top 250 aparecem nos trendings**
- Exibir essa quantidade e listar os nomes

---

## 🎁 Bônus

- **Cache ou persistência local dos dados** – _+3 pontos_
- **Geração de visualização (gráficos, tabelas, etc.) via frontend opcional** – _+3 pontos_
- **README bem escrito com decisões técnicas** – _+2 pontos_
- **Testes automatizados (unitários ou e2e)** – _+2 pontos_

---

## 📬 Entrega

Envie:
- Link do repositório com o código-fonte
- Links ou prints de conversas com IA, se utilizadas

---

## 💡 Dica

Você está sendo avaliado tanto pela qualidade do que entrega quanto pela sua **capacidade de priorizar e planejar**. Foque no que você acredita entregar mais valor no tempo que você tiver disponível.

Boa sorte 🚀
