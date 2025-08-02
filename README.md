# 🎬 Desafio de Projeto: Banco de Dados - Site de Filmes  
**DIO - Trilha .NET - Módulo de Banco de Dados**

## 📚 Descrição

Este projeto foi desenvolvido como parte da trilha **.NET** da [Digital Innovation One (DIO)](https://www.dio.me/). O desafio propõe a aplicação de conhecimentos em **modelagem e consultas SQL** com base em um cenário realista: um **site de filmes** que armazena informações sobre **filmes, atores e gêneros**.

O principal objetivo é executar 12 consultas SQL específicas em um banco de dados relacional previamente estruturado, a fim de responder a perguntas de negócio e gerar **informações relevantes para análise de dados**.

---

## 🧠 Contexto

Você foi designado como responsável pelo **banco de dados** de um site de filmes. O banco contém informações sobre os filmes, seus atores e os gêneros. A estrutura envolve **relacionamentos muitos para muitos**, exigindo habilidade para manipular dados com **JOINs, filtros e agrupamentos**.

---

## 🗂️ Estrutura do Banco de Dados

O banco de dados se chama **Filmes** e possui as seguintes tabelas:

- **Filmes**: Armazena os dados dos filmes (ID, Nome, Ano, Duração, etc).
- **Atores**: Armazena os dados dos atores (ID, PrimeiroNome, UltimoNome, Genero).
- **Generos**: Armazena os diferentes gêneros de filmes (ID, Nome).
- **ElencoFilme**: Relaciona os filmes com os atores, incluindo o papel do ator.
- **FilmesGenero**: Relaciona os filmes com seus respectivos gêneros.

### 🔗 Relacionamentos

- Um **filme pode ter vários gêneros** e um gênero pode pertencer a **vários filmes**.
- Um **filme pode ter vários atores** e um ator pode participar de **vários filmes**.

---

## 🔧 Preparação do Ambiente

Para executar este projeto, você deve:

1. Ter o **SQL Server** instalado.
2. Executar o script `Script Filmes.sql` disponível na pasta `/Scripts` deste repositório.
3. Isso criará o banco de dados `Filmes` com todas as tabelas e dados populados.

---

## 🎯 Objetivos

Realizar as **12 consultas SQL** abaixo utilizando os dados fornecidos no script:

| Nº | Descrição da Consulta |
|----|------------------------|
| 1  | Buscar o **nome e ano dos filmes**. |
| 2  | Buscar o **nome e ano dos filmes**, ordenados por **ano crescente**. |
| 3  | Buscar o filme **"De Volta para o Futuro"**, trazendo nome, ano e duração. |
| 4  | Buscar os filmes lançados em **1997**. |
| 5  | Buscar os filmes lançados **após o ano 2000**. |
| 6  | Buscar os filmes com duração **maior que 100 e menor que 150 minutos**, ordenando pela duração crescente. |
| 7  | Buscar a **quantidade de filmes lançados por ano**, agrupando por ano, e ordenando pela duração em ordem decrescente. |
| 8  | Buscar os **atores do gênero masculino**, retornando `PrimeiroNome` e `UltimoNome`. |
| 9  | Buscar os **atores do gênero feminino**, retornando `PrimeiroNome`, `UltimoNome`, e ordenando por `PrimeiroNome`. |
| 10 | Buscar o **nome do filme e seu gênero**. |
| 11 | Buscar o **nome do filme e o gênero** apenas do tipo **"Mistério"**. |
| 12 | Buscar o **nome do filme e os atores**, retornando `PrimeiroNome`, `UltimoNome` e o `Papel` desempenhado. |

---

## 🛠️ Tecnologias Utilizadas

- **SQL Server**
- **Transact-SQL (T-SQL)**
- Gerenciadores: SQL Server Management Studio (SSMS) ou Azure Data Studio

---

## ✅ Resultado Esperado

Cada uma das consultas deve retornar **exatamente os dados esperados** conforme as imagens e exemplos fornecidos no desafio original da DIO. Certifique-se de que a saída corresponde em colunas, valores e ordenações.

---

## 🏁 Conclusão

Este projeto reforça a importância da **estruturação correta de dados relacionais** e da **manipulação eficiente com SQL**. As habilidades desenvolvidas aqui são fundamentais para qualquer profissional da área de **Back-end, Análise de Dados ou Engenharia de Dados**.

---

## 🤝 Créditos

Desenvolvido como parte do desafio proposto pela [DIO - Digital Innovation One](https://www.dio.me/)  
Instrutores: Equipe DIO & parceiros da trilha .NET
