# Desafio *Codenation*
Esse projeto refere-se a uma tarefa que tive que realizar no desafio da *Codenation*, para poder participar da Aceleração de *Data Science* da mesma. No desafio deveríamos usar as notas de alunos (ciências da natureza, linguagens e códigos, ciências humanas e redação) e informações sociais dos alunos (do ano de 2016) que estavam em dois arquivo : *train.csv* e *test.csv*.

O arquivo *train.csv* tinha todas as features e com esse arquivo iríamos, após ser tratado, treinar um modelo de *Machine Learning* do tipo regressão.

Já no arquivo *test.csv* constava todas as features com exceção da *feature* **NU_NOTA_MT**. Ou seja, após treinarmos o modelo usaríamos as *features* do arquivo de teste para prever as notas de matemática dos alunos.

Após gerarmos as previsões com o modelo de machine learning criaríamos um arquivo com apenas duas colunas que seriam **NU_INSCRICAO** e **NU_NOTA_MT** criamos o arquivo *csv* e para submissão.

# Objetivo do desafio

Usar um ou mais modelos de *machine learning* do tipo regressão para previsão de notas de matemática do ENEM do ano de 2016.

# Etapas

1) Importação das bibliotecas;

2) Importação das bases de dados;

3) Verificação das variáveis;

4) Seleção das variáveis por meio da correlação;

5) Tratamento dos valores faltantes;

6) Aplicação preliminar dos modelos (previsões e análise das previsões);

7) Aplicação dos modelos ao Desafio *Codenation*;

8) Comparação dos resultados dos modelos.

# Bibliotecas usadas

*Matplotlib, Pandas, Seaborn e Scikit-learn.*

# Dados

Arquivos com dados de treino (*train.csv*) e teste (*test.csv*) fornecidos pela *Codenation*.

# Modelos usados e resultados

Foram usados vários modelos de ML do tipo Regressão (11 ao todo) e podem ser observados no script desse repositório. O modelo que obteve o melhor resultado foi a Regressão *Gradient Boosting* com o resultado de **93.64**%.
