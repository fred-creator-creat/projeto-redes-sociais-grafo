# Projeto Redes Sociais com Grafos

Este projeto foi desenvolvido como parte do desafio prático de modelagem e implementação de bancos de dados de grafos. O trabalho simula a estrutura de uma rede social para analisar conexões, recomendações e performance.

## 🎓 Idealização e Apoio
Este projeto foi realizado por **Fred Cavalheiro** através da plataforma de ensino **[DIO (Digital Innovation One)](https://www.dio.me/)**, com o apoio e infraestrutura providenciados pela **[Neo4j](https://neo4j.com/)**.

## 📁 Acesso Direto ao Projeto
Para visualizar o código completo, as consultas Cypher e a lógica de implementação, acesse o arquivo principal:
👉 **[Ver Notebook do Projeto (Código Python)](/Projeto_Redes_Sociais_Grafo.ipynb)**

---

## 🛠️ Ecossistema e Ferramentas Utilizadas
O projeto foi construído utilizando as seguintes tecnologias:

* **[Arrows.app](https://arrows.app/)**: Utilizado para a modelagem do diagrama de grafos (Modelo Conceitual).
* **[Neo4j AuraDB](https://neo4j.com/cloud/platform/aura-graph-database/)**: Instância de banco de dados de grafos gerenciada na nuvem.
* **[Google Colab](https://colab.research.google.com/)**: Ambiente de desenvolvimento Python para automação e análise de dados.
* **[Kaggle](https://www.kaggle.com/)**: O ambiente foi configurado com integração via **API** para consumo de datasets, embora o foco final tenha sido a carga personalizada de dados via Cypher.
* **[Python](https://www.python.org/)**: Linguagem principal para integração e scripts.

### 📚 Bibliotecas Python Utilizadas
* **[neo4j](https://pypi.org/project/neo4j/)**: Driver oficial para conexão e execução de queries Cypher.
* **[pyvis](https://pyvis.readthedocs.io/)**: Biblioteca para geração de visualizações interativas de grafos.
* **[IPython](https://ipython.org/)**: Ferramenta para exibição de resultados dinâmicos e mídias no notebook.
* **[kaggle](https://github.com/Kaggle/kaggle-api)**: Biblioteca para integração e automação com a plataforma Kaggle.

---

## 📊 Modelo Conceitual
Abaixo, o diagrama que define as entidades (**User**, **Post**, **Date**) e seus relacionamentos (**FOLLOWS**, **POSTED**, **LIKED**, **ON_DATE**).

![Modelo Conceitual](modelo_conceitual.png)

---

## 🚀 Implementação e Análises Realizadas
O projeto executa análises complexas através da linguagem **Cypher**, focando em:

1.  **Recomendação de Amizade:** Lógica para sugerir amigos baseada em conexões de segundo grau (amigos de amigos).
2.  **Caminho Mais Curto:** Algoritmo para identificar a menor rota de interação entre dois usuários.
3.  **Ranking de Engajamento:** Identificação dos posts com maior número de interações.
4.  **Relatório de Performance:** Uso da cláusula `PROFILE` para validar a eficiência das consultas, alcançando tempos de resposta de aproximadamente 20ms.

### Visualização do Grafo em Produção (AuraDB)
![Visualização Geral](visualizacao_grafo_geral.png)

### Prova de Autoria e Detalhe de Nó
![Detalhe do Usuário](detalhe_no_usuario.png)

---

## 📞 Contato e Conexão
**Fred Cavalheiro**
* 🔄 **Em transição de carreira:** De Vigilante para a área de Tecnologia.
* 🎓 **Técnico em Desenvolvimento de Sistemas** (Formado pelo Senac).
* 📚 **Estudante de:** Machine Learning e Análise de Dados (Python, Neo4j, Power BI e Excel).
* 🔗 **[Meu Perfil no LinkedIn](https://www.linkedin.com/in/fred-cavalheiro/)**

---
*Projeto desenvolvido para o Portfólio de Dados em Grafos.*
