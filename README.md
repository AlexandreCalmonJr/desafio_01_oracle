Análise de Desempenho - Alura Store

1. O Propósito da Análise Realizada

Este projeto foi desenvolvido para atender a uma necessidade de negócio do e-commerce "Alura Store". O proprietário, Sr. João, precisa vender uma de suas quatro lojas para levantar capital e investir num novo empreendimento. O propósito desta análise de dados é identificar, de forma objetiva e quantitativa, qual das lojas apresenta o desempenho mais fraco, fornecendo uma recomendação estratégica e embasada para a decisão de venda.

2. Estrutura do Projeto e Organização dos Arquivos
O repositório está organizado da seguinte forma para facilitar a compreensão e a reprodutibilidade da análise:

.
├── 📂 base-de-dados-challenge-1/
│   ├── loja_1.csv
│   ├── loja_2.csv
│   ├── loja_3.csv
│   └── loja_4.csv
│
├── 📜 LojasSrJoão.ipynb
│
└── 📜 README.md

dados/: Pasta contendo os quatro ficheiros .csv originais, cada um representando os dados de vendas de uma loja. (Nota: No notebook, estes dados foram carregados diretamente via URL para simplificar a execução).

AluraStoreBr.ipynb: O coração do projeto. Este Jupyter Notebook contém todo o código Python utilizado para a análise, desde a importação e limpeza dos dados até à geração dos gráficos e tabelas de resultados.

README.md: Este ficheiro, que fornece uma documentação completa sobre o projeto.

1. Resumo dos Resultados
A análise final, utilizando os dados mais recentes, revelou um cenário de grande equilíbrio operacional entre as quatro lojas. A tabela abaixo resume os principais indicadores.

| Métrica          | Loja 1         | Loja 2         | Loja 3         | Loja 4         |
|------------------|----------------|----------------|----------------|----------------|
| **Faturamento**  | R$ 1.534.509,12 | R$ 1.488.459,06 | R$ 1.464.025,03 | R$ 1.384.497,58 |
| **Avaliação Média** | 3.98           | 4.04           | 4.05           | 4.00           |
| **Frete Médio**   | R$ 34,69       | R$ 33,62       | R$ 33,07       | R$ 31,28       |
| **Total de Vendas** | 2.359          | 2.359          | 2.359          | 2.358          |

2. Exemplos de Gráficos e Insights Obtidos
As visualizações de dados foram fundamentais para comparar o desempenho das lojas de forma clara e direta.

Insight de Faturamento

O gráfico de faturamento mostrou que, apesar de as vendas serem próximas, a Loja 4 possui a menor receita entre as quatro, tornando-se o principal ponto de atenção financeiro.

Insight de Satisfação do Cliente

O gráfico de avaliações demonstrou que todas as lojas têm uma excelente reputação, com notas médias muito altas e próximas de 4.0. Isso indica que a qualidade do serviço é consistente em toda a rede.

3. Conclusão e Recomendação Final
Dado o equilíbrio operacional entre todas as unidades, o faturamento tornou-se o principal critério para a decisão.

Recomendação: Vender a Loja 4.

Justificativa: Num cenário em que todas as operações são saudáveis e de baixo risco, a decisão mais estratégica é desinvestir no ativo que, atualmente, gera o menor retorno financeiro. A venda da Loja 4 libertará o capital necessário para os novos projetos do Sr. João, mantendo as três lojas de maior faturamento na rede.

4. Instruções para Executar o Notebook
Para reproduzir esta análise, siga os passos abaixo:

Clone este repositório:

git clone https://docs.github.com/articles/referencing-and-citing-content

Abra o ficheiro LojasSrJoão.ipynb num ambiente que suporte Jupyter Notebooks, como o Google Colab ou o Jupyter Lab local.

Certifique-se de que tem as bibliotecas pandas e matplotlib instaladas no seu ambiente:

pip install pandas matplotlib

Execute as células do notebook sequencialmente para ver todo o processo de análise, desde o carregamento dos dados até à geração dos gráficos e do relatório final.