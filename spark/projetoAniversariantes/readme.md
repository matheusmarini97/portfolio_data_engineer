# 🎓 Projeto: Organização de Aniversários dos Alunos com Apache Spark

## 📖 Descrição
Este projeto foi desenvolvido no contexto de uma **escola**, a **Faculdade Adventista do Paraná**.  
A partir de um relatório extraído do sistema interno, foi realizada uma transformação dos dados utilizando **Apache Spark**.  

O objetivo é organizar os aniversários dos alunos de forma estruturada, extraindo apenas o **mês de nascimento**, e em seguida **ordenando** os registros por:
1. Mês do aniversário  
2. Curso  
3. Ano do curso  
4. Nome do aluno  

Esse processo gera uma tabela organizada, facilitando consultas e relatórios acadêmicos.

Além disso, os dados foram utilizados para **calcular quantos alunos de cada turma fazem aniversário em cada mês**, permitindo gerar estatísticas úteis para eventos e planejamentos escolares.  

⚠️ **Observação:**  
- Por motivos de **segurança e privacidade**, os **dados originais dos alunos não foram disponibilizados** neste repositório. Apenas o **código** de transformação está incluído.

- Como o projeto foi desenvolvido para **uso pontual e interno**, **não foram implementadas validações no código** (como tratamento de valores nulos, formatos inconsistentes ou erros de entrada). O foco foi apenas atender à demanda do momento.  

- O **Apache Spark foi executado em modo local (sem cluster)**, uma vez que o volume de dados era **relativamente pequeno** e não justificava a criação de um cluster distribuído.  
---

## ⚙️ Tecnologias Utilizadas
- [Apache Spark](https://spark.apache.org/) – Framework para processamento distribuído
- [Jupyter Lab](https://jupyter.org/install) – Framework para processamento distribuído
- [PySpark](https://spark.apache.org/docs/latest/api/python/) – API Python do Spark
- [Python 3.11.2](https://www.python.org/) – Linguagem principal do PySpark
- [Java 17](https://www.java.com/pt-BR/) – JVM para execução do Spark
- [Linux Debian 12 - Bookworm](https://www.debian.org/releases/bookworm/) – Sistema operacional
- [Oracle virtual box](https://www.virtualbox.org/) – Virtualizador

---