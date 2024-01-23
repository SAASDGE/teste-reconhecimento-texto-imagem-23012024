# Teste de Desenvolvimento (Extração de informações)

Para garantir o eficiente gerenciamento dos créditos de energia provenientes de usinas de energia renovável, a extração precisa e automática de dados das notas fiscais de energia elétrica é fundamental. Além disso, possuir conhecimento aprofundado sobre faturas de energia elétrica é crucial para o sucesso na gestão desses recursos.

Logo, é proposto dois testes como parte da avaliação dos conhecimentos técnicos e teóricos dos candidatos. Essa avaliação tem o objetivo de medir a compreensão do participante no contexto da extração de dados de notas fiscais e no entendimento detalhado de faturas de energia elétrica.

# Teste 1

Em busca pela eficiência na leitura de faturas, a equipe de desenvolvimento propõe a criação de uma rotina que, a partir de faturas de energia elétrica em formato de PDF, seja capaz de extrair importantes informações.

Nesta atividade, você deve editar o arquivo read.py e desenvolver uma rotina capaz de realizar a leitura de uma fatura no formato PDF e retornar um dataframe contendo as seguintes informações:

- O número da instalação
- Mês ao qual a fatura é referente
- Tarifa cheia (com impostos)
- Valor da distribuidora
- Somatório das componentes de energia injetada

Ao desenvolver a atividade deve ser realizada a leitura do arquivo, extração do texto e por fim análise dos dados. Para a extração de textos dos PDFs, é sugerido o uso da biblioteca pdfplumber. Além disso, para a extração de informações do texto é sugerido o uso de expressões regulares a partir da biblioteca re, e com o objetivo de organizar e visualizar as informações é sugerido o uso da biblioteca pandas. 

As informações obtidas devem ser exibidas e estruturadas de acordo com a seguinte tabela, além disso é possível observar o gabarito da atividade.

|                 Campo                |    Valor    | 
|--------------------------------------|-------------|
|              Instalação              |   12385675  |
|                   Mês                |   OUT/2023  |
|      Tarifa cheia (com impostos)     |   0,881145  |
|         Valor da distribuidora       |    219,14   |
|    Somatório de energia injetada     |     1950    |

Para realizar os testes e conferir os valores você deve utilizar o arquivo fatura_cpfl.pdf, disponibilizado no repositório.

# Teste 2

Algumas questões constituem parte integrante dos desafios cotidianos enfrentados pela empresa. Para abordar esses desafios de maneira eficaz, solicita-se que responda detalhadamente por meio de texto, alguns questionamentos. Em um arquivo PDF, envie suas respostas para o e-mail falecom@dg.energy.

- Dado a fatura da cemig disponível no repositório e as informações do descritivo, explique a diferença entre a fatura e uma fatura normal de energia elétrica.
- Elabore uma explicação detalhada sobre o descritivo presente na fatura, com foco nos valores faturados.
- Identifique e explique qual informação é considerada a mais crucial no quadro de Informações Gerais da fatura.
- Identifique o consumo da instalação referente ao mês de julho de 2023.

# Observações

- Demonstrar proficiência no uso do Git e GitHub para a resolução do Teste 1 será considerado um fator altamente valorizado na avaliação do candidato.