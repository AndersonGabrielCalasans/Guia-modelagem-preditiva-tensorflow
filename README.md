#  **Guia de Modelagem Preditiva com Linguagem Python e TensorFlow**

Esse projeto foi disponibilizado pela [**Data Science Academy**](https://www.datascienceacademy.com.br/), no curso de **Python Fundamentos Para Análise de Dados 3.0**, com o objetivo de mostrar um guia de modelagem preditiva utilizando Python e TensorFlow, o principal framework para construção de modelos de Machine Learning e Deep Learning e para construir aplicações comerciais de Inteligência Artificial.

Nele nós vamos criar um modelo preditivo para prever a mediana dos preços de habitações em Boston, Massachusetts, com base em 506 habitações observadas no dataset **The Boston Housing Dataset**, utilizando um modelo de regressão linear simples.

## **Carregando os Dados**

Os dados utilizados neste projeto foram disponibilizados no Dataset **The Boston Housing Dataset**, que são dados públicos coletados pela U.S Census Servic de preço de habitações da região de Boston, na cidade de Massachusetts.

O link contendo todas as informações do Dataset é [este aqui](https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html).

O Dataset importado tem um problema, ele não possui nome nas colunas para corrigir esse problema, irei criar uma lista com o nome das colunas, de acordo com a nomenclatura da documentação original, segue a descrição de cada uma delas:

 - **CRIM** - taxa de criminalidade per capta da cidade
 - **ZN** - proporção de terrenos residenciais zoneados para lotes acima de 25.000 sq.ft(pé quadrado, medida proporcional a 0,093m²).
 - **INDUS** - proporção de acres de negócios não varejistas (grandes empresas) por cidade.
 - **CHAS** - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
 - **NOX** - concentração de óxidos nítricos (partes por 10 milhões)
 - **RM** - número médio de cômodos por domicílio
 - **AGE** -proporção de unidades ocupadas pelos proprietários construídas antes de 1940
 - **DIS** - distâncias ponderadas para cinco centros comerciais de Boston
 - **RAD** - índice de acessibilidade às rodovias radiais
 - **TAX** - taxa de imposto de propriedade de valor total por 10.000(dólares)
 - **PTRATIO** - relação aluno-professor por cidade
 - **B** - 1000(Bk - 0,63)^2 onde Bk é a proporção de negros por cidade 
 - **LSTAT** - % de menores de idade da população
 - **MEDV** - Valor médio das casas ocupadas pelos proprietários em $ 1.000 dólares.

## **Criando a Modelagem Preditiva de Regressão Linear Simples**

No **modelo de regressão linear simples** é um modelo de aprendizado supervisionado, no qual, desejamos modelar a **relação** entre uma **variável dependente(y)** e uma **variável independente(x)**.

Para esse estudo, iremos adotar como variáveis de **entrada** e **saída**, repectivamente, as variáveis **RM**, que representa o número médio de cômodos por domicílio e a variável **MEDV**, que é o valor da mediana das casas ocupadas pelos proprietários em $ 1.000 dólares.

Com isso iremos atender ao objetivo de prever o valor da mediana das casas ocupadas por proprietários com base no número de quartos.

Vamos criar um plot mostrando a relação atual entre as variáveis.

Basicamente temos $MEDV=f(RM)$ e queremos estimar a função $f()$ usando regressão linear.

## Conclusão

Como o objetivo do projeto era apenas demonstrar como é feita de modo geral e introdutório, não entramos em detalhes em relação ao tratamento dos dados para que o modelo seja otimizado, contudo o objetivo foi atingido e cccom esse projeto pude ter um panorama geral de como é realizado uma ativiidade de machine learning e me dou por satisfeito com o resultado obtido.

## Autor

Gabriel Calasans
