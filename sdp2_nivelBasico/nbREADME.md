
```markdown

SQL Data Processing Projects

1. Objetivo
Este repositório reúne projetos práticos de SQL para estudantes de Ciência de Dados, organizados em níveis progressivos (básico, intermediário e avançado).  
O foco é desenvolver habilidades sólidas em **processamento de dados estruturados**, evoluindo do nível básico até consultas avançadas e otimização.

---

2. Estrutura do Repositório

```plaintext
sql-data-processing-projects/
│
├── README.md                # Documento principal com instruções e referências
├── docs/                    # Documentação adicional (tutoriais, guias, artigos)
│   └── referencias.md
│
├── nivel-1-basico/          # Projetos introdutórios
│   ├── projeto-1-cadastro-alunos/
│   │   ├── schema.sql
│   │   ├── inserts.sql
│   │   └── queries.sql
│   ├── projeto-2-biblioteca/
│   ├── projeto-3-loja-virtual/
│   ├── projeto-4-funcionarios/
│   └── projeto-5-cursos/
│
├── nivel-2-intermediario/   # Projetos intermediários
│   ├── projeto-1-locadora-filmes/
│   ├── projeto-2-pizzaria/
│   ├── projeto-3-transporte/
│   ├── projeto-4-companhia-aerea/
│   ├── projeto-5-ecommerce/
│   └── projeto-6-comunicacao-interna/
│
├── nivel-3-avancado/        # Projetos avançados
│   ├── projeto-1-emissoes-carbono/
│   ├── projeto-2-saude-mental-estudantes/
│   ├── projeto-3-dashboard-vendas/
│   └── projeto-4-analise-financeira/
│
└── utils/                   # Scripts auxiliares
    ├── conexao-postgres.sql
    └── conexao-mysql.sql
```

---

3.Níveis de Conhecimento

🔹 Nível 1 – Básico

- Criação de tabelas (DDL)  
- Inserção e atualização de dados (DML)  
- Consultas simples (`SELECT`, `WHERE`)  
- Ordenação (`ORDER BY`)  
- Funções agregadas (`COUNT`, `SUM`, `AVG`, `MIN`, `MAX`)  
- Agrupamento (`GROUP BY`, `HAVING`)  

**Projetos:**  

1. Cadastro de Alunos  
2. Biblioteca  
3. Loja Virtual  
4. Funcionários  
5. Cursos  

---

🔹 Nível 2 – Intermediário

- Junções (`INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`)
- Subconsultas (`IN`, `EXISTS`)  
- Normalização e integridade referencial  
- Views e CTEs  
- Funções de janela (`ROW_NUMBER`, `RANK`, `OVER`)  

**Projetos:**  

1. Locadora de Filmes  
2. Pizzaria  
3. Transporte  
4. Companhia Aérea  
5. E-commerce  
6. Comunicação Interna  

---

🔹 Nível 3 – Avançado

- Stored Procedures e Triggers  
- Otimização de consultas (`EXPLAIN`, índices avançados)  
- Particionamento de tabelas  
- Transações e controle de concorrência  
- Integração com Python/R para Data Science  

**Projetos:**

1. Emissões de Carbono  
2. Saúde Mental de Estudantes  
3. Dashboard de Vendas  
4. Análise Financeira  

---

4.Como Executar os Projetos

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/sql-data-processing-projects.git
   ```

2. Acesse a pasta do projeto desejado:

   ```bash
   cd sql-data-processing-projects/nivel-1-basico/projeto-1-cadastro-alunos
   ```

3. Execute os scripts em um banco de dados (PostgreSQL ou MySQL recomendados):

   ```bash
   psql -U usuario -d banco < schema.sql
   psql -U usuario -d banco < inserts.sql
   psql -U usuario -d banco < queries.sql
   ```

---

5.Referências

Livros

- Elmasri & Navathe – *Fundamentals of Database Systems*  
- Silberschatz, Korth & Sudarshan – *Database System Concepts*  

Tutoriais Online

- [DataCamp – Projetos SQL](https://www.datacamp.com)  
- [LearnSQL – Exercícios práticos](https://learnsql.com)  

Exemplos no GitHub

- SQL_BancodeDados – CoimbraDouglas [(github.com in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fgithub.com%2FCoimbraDouglas%2FSQL_BancodeDados")

---
Conclusão

Este repositório foi estruturado para apoiar estudantes de Ciência de Dados no aprendizado progressivo de SQL.  
Cada projeto traz desafios práticos que consolidam conceitos fundamentais e avançados, preparando o aluno para aplicações reais em análise de dados.

```
---
