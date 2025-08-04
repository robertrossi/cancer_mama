🧬 Conjunto de Dados sobre Câncer de Mama
📄 Descrição
O conjunto de dados sobre câncer de mama hospedado no Kaggle é um recurso valioso para pesquisadores, cientistas de dados e entusiastas de aprendizado de máquina que buscam desenvolver modelos preditivos para o diagnóstico do câncer de mama. Projetado para tarefas de classificação binária (benigno ou maligno), ele contém medidas extraídas de imagens digitalizadas de aspirados por agulha fina (PAAF) de massas mamárias.

Este dataset é amplamente utilizado em pesquisas de patologia computacional e aprendizado de máquina aplicado à saúde.

🔍 Visão Geral
Origem: Breast Cancer Wisconsin (Diagnostic) Data Set

Tarefa: Classificação binária (diagnóstico: maligno M ou benigno B)

Fonte: Universidade de Wisconsin, disponibilizado no Kaggle

Aplicações: Pesquisa médica, desenvolvimento de modelos de ML, ensino de ciência de dados

Link: Acesse no Kaggle

🧾 Estrutura do Conjunto de Dados
Instâncias: 569 amostras (linhas)

Atributos: 32 colunas

1 coluna de ID

1 coluna de diagnóstico (variável alvo)

30 características numéricas extraídas das imagens

🎯 Variável Alvo
diagnóstico:

M = Maligno (cancerígeno)

B = Benigno (não cancerígeno)

🔬 Características
As 30 colunas de características representam medições estatísticas dos núcleos celulares, divididas em três grupos:

Média (ex: radius_mean, texture_mean)

Erro Padrão (ex: radius_se, area_se)

Pior Valor (ex: radius_worst, smoothness_worst)

Cada grupo contém medições como:

Raio (distância média do centro ao perímetro)

Textura (desvio padrão da intensidade)

Perímetro

Área

Suavidade (variações locais)

Compacidade

Concavidade

Pontos côncavos

Simetria

Dimensão fractal

🧾 Exemplo de Instância
ID	Diagnóstico	Raio Médio	Textura Média	Perímetro Médio	Área Média	Suavidade Média	...
842302	M	17.99	10.38	122.80	1001.0	0.11840	...

📝 Interpretação: Esta amostra (ID 842302) representa um tumor maligno com raio médio de 17.99, textura média de 10.38, e assim por diante.

🌟 Destaques
✅ Classes equilibradas: 357 benignos e 212 malignos

✅ Sem valores ausentes: Dados limpos e prontos para uso

✅ Alta dimensionalidade: 30 recursos numéricos que permitem modelagens avançadas

✅ Impacto real: Utilizado para melhorar o diagnóstico precoce de câncer de mama

✅ Acesso gratuito: Disponível no Kaggle

💡 Casos de Uso
🔬 Modelagem Preditiva: Treinamento de classificadores (ex: Random Forest, SVM, Redes Neurais)

🔍 Engenharia de Atributos: Análise de correlações entre características

📊 Visualização de Dados: Criação de gráficos e mapas de calor para entendimento das variáveis

🧪 Pesquisa Médica: Estudo da morfologia celular para diagnóstico

🎓 Ensino: Ideal para exercícios de ciência de dados (pré-processamento, validação cruzada, etc.)