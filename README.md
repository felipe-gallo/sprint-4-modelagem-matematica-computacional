# Challenge Sprint IV - Modelagem Matemática e Computacional

Atividade da FIAP no contexto da GoodWe: energia solar, produto escalar e sistemas lineares aplicados ao carregamento de veículos elétricos.

## Executar no Google Colab

[Abrir notebook no Colab](https://colab.research.google.com/github/felipe-gallo/sprint-4-modelagem-matematica-computacional/blob/main/Challenge_Sprint_IV.ipynb)

No Colab, selecione **Ambiente de execução > Executar tudo**. A única biblioteca utilizada é o NumPy, disponível no ambiente. Todos os dados estão no notebook; não é necessário enviar uma base externa.

O notebook foi executado no Google Colab, com as cinco células de código concluídas e todas as verificações aprovadas.

## Arquivos

- `Challenge_Sprint_IV.ipynb`: implementação dos itens 1(c) e 2(c), explicações, resultados e conferências.
- `Sprint_4_modelagem-matematica-computacional.pdf`: guia com a resolução detalhada dos itens manuscritos e o link deste repositório.
- `requirements.txt`: dependência para execução local, se desejado.

## Resultados

- Energia adquirida da rede: **(12, 12, 3, 6, 10) kWh**, na ordem dos cinco intervalos do enunciado.
- Total adquirido da rede: **43 kWh**.
- Custo total, calculado com `np.dot`: **R$ 24,65**.
- Solução do sistema com `np.linalg.solve`: **2 veículos a 7 kW, 3 a 11 kW e 1 a 22 kW**.
- Conferência: **6 veículos**, dos quais **4 a 11 ou 22 kW**, e **69 kW** de potência total.

## Integrantes

- ARTHUR MAZIVIERO FARIA - RM 573928
- JUN UEHARA - RM 570537
- FELIPE DE SOUZA GALLO - RM 569680
- ROBERSON REGUERO LUIZ JUNIOR - RM 573031
- TOMMASO CONCEIÇÃO NAGLIATTI - RM 572147
- MATHEUS MARTINS LACERDA - RM 570843

## Entrega solicitada

Anexar dois arquivos: **o manuscrito digitalizado** com os itens 1(a), 1(b), 2(a) e 2(b), e **o notebook `.ipynb`** com os itens 1(c) e 2(c). O PDF é um guia para copiar as resoluções à mão. O link do GitHub não substitui os arquivos exigidos pelo enunciado.

Fonte dos dados: enunciado do Challenge Sprint IV - Modelagem Matemática e Computacional.