# Atividades Ponderadas
## Módulo 7 - SAP
### Ana Carolina Cremonezi Martire

<br>

#### Semana 3 - Regras de Negócio e DMN

&emsp;&emsp;De acordo com a Allura, "Uma regra (de negócio) define uma diretriz para cada contexto específico de um negócio, sobre qual deve ser o resultado esperado para cada ação ou decisão." Ela traduz uma necessidade do negócio em regras lógicas, fazendo com que o desenvolvimento de uma empresa se alinhe com essas necessidades.

&emsp;&emsp;Seguindo essa definição, cada integrante do grupo G2² desenvolveu 5 diferentes Regras de Negócio que se encaixam no projeto do Inteli. As regras que eu desenvolvi foram as seguintes:

<br>
<div align="center">
<sub>Tabela 1 - Regras de Negócio - Time Financeiro</sub>

| Número | Descrição | Critérios de Aplicação | Ações | Responsável |
| ------ | ------ | ------ | ------ | ------ |
**FI001** | Pedido de transação for recebido de saída de caixa. | Ter um pedido de transação recebido. | Verificar se há orçamento disponível para a área solicitante. | Equipe Financeira. | 
**FI002** | Pedido de transação for recebido de entrada de caixa. | Ter um pedido de transação recebido. | Verificar se a transação ocorreu. | Equipe Financeira. |
**FI003** | Falta de orçamento na área que pediu uma transação. | Não ter orçamento. | Informar a área que o pedido foi recusado. | Equipe Financeira. |
**FI004** | Tansação de entrada de caixa efetuada. | Ter um pedido de transação efetuado. | Atualizar o caixa com a transação. | Equipe Financeira. |
**FI005** |  Transação for uma entrada de caixa não efetuada. | Ter um pedido de transação não efetuado. | Adicionar a previsão ao caixa. | Equipe Financeira. |

<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>

<br>

&emsp;&emsp;Após ter pensado e criado a tabela de Regras de Negócio acima, foi necessário desenvolver um diagrama DMN (Decision Model Notation).

<div align="center">
<sub>Figura 1 - Diagrama DMN</sub>
<img src="../assets/imagens/DMN_M7_S3.png" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>
<br>


&emsp;&emsp;Dentro das Decisões 1, 3, 4, 5 e 6 há uma "*decision table*", onde estão inseridas as Regras de Negócio já estipuladas. Elas podem ser vistas nas imagens a seguir.
<br>
<br>

<div align="center">
<sub>Figura 2 - Diagrama DMN - Decision Table 1</sub>
<img src="../assets/imagens/DMN_Decisao1.png" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>
<br>

&emsp;&emsp;Na figura acima, pode-se ver a tabela de decisão da decisão 1. Ela tem relação direta com a Regra de Negócio de nomenclatura FI001.

<br>
<br>

<div align="center">
<sub>Figura 3 - Diagrama DMN - Decision Table 3</sub>
<img src="../assets/imagens/DMN_Decisao3.png" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>
<br>

&emsp;&emsp;Na figura apresentada acima, é possível observar a tabela de decisão referente à decisão 3, que está diretamente relacionada à Regra de Negócio de nomenclatura FI002.

<br>
<br>

<div align="center">
<sub>Figura 4 - Diagrama DMN - Decision Table 4</sub>
<img src="../assets/imagens/DMN_Decisao4.png" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>
<br>

&emsp;&emsp;A imagem acima refere-se à tabela de decisão correspondente à decisão 4, que está diretamente vinculada à Regra de Negócio FI003.

<br>
<br>

<div align="center">
<sub>Figura 5 - Diagrama DMN - Decision Table 5</sub>
<img src="../assets/imagens/DMN_Decisao5.png" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>
<br>

&emsp;&emsp;Na figura 5, pode-se visualizar a tabela de decisão da decisão 5: atualizar o caixa da transação. Ela tem relação direta com a Regra de Negócio de nomenclatura FI004.

<br>
<br>

<div align="center">
<sub>Figura 6 - Diagrama DMN - Decision Table 6</sub>
<img src="../assets/imagens/DMN_Decisao6.png" width="100%" >
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>
<br>

&emsp;&emsp;Por fim, na figura acima, está a tabela de decisão da decisão 6, cuja qual tem relação direta com a Regra de Negócio de nome FI005.