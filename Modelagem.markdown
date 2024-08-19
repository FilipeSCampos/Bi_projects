### Grupo: Grupo 2

## Participantes: Ana Luiza, Beatriz Vencio, Filipe Sampaio, Diogo Demetrius

### Contextualização:

**Base Escolhida:** Convênios Governamentais (SICONV).  
**Problema:** O objetivo é analisar a execução dos convênios governamentais para identificar padrões de cumprimento de prazos, execução financeira e situação contratual, essencialmente ver se o comportamento do governo mudou em relação a catástrofes climáticas ao longo dos anos, COVID19 inclusa.  
**Como os Dados Ajudam:** A análise permitirá identificar quais convênios apresentam maiores dificuldades na execução, atrasos ou problemas financeiros, ajudando na tomada de decisões para futuras contratações e alocação de recursos.

### Dimensões e Atributos:

**Dimensão: Convênio**  
- `NR_CONVENIO`: Identificador único do convênio.  
- `ID_PROPOSTA`: Identificador da proposta associada ao convênio.

**Dimensão: Tempo**  
- `DIA`, `MES`, `ANO`: Data relacionada aos eventos do convênio.  
- `DIA_ASSIN_CONV`, `DIA_PUBL_CONV`, `DIA_INIC_VIGENC_CONV`, `DIA_FIM_VIGENC_CONV`, `DIA_FIM_VIGENC_ORIGINAL_CONV`: Datas específicas dos eventos do convênio.

**Dimensão: Situação**  
- `SIT_CONVENIO`: Situação atual do convênio.  
- `SUBSITUACAO_CONV`: Detalhamento adicional da situação.  
- `SITUACAO_PUBLICACAO`: Situação da publicação do convênio.

### Fatos e Atributos:

**Fato: Financeiros**  
- `VL_GLOBAL_CONV`: Valor global do convênio.  
- `VL_REPASSE_CONV`: Valor do repasse previsto no convênio.  
- `VL_CONTRAPARTIDA_CONV`: Valor da contrapartida.  
- `VL_EMPENHADO_CONV`: Valor empenhado.  
- `VL_DESEMBOLSADO_CONV`: Valor desembolsado.  
- `VL_SALDO_REMAN_TESOURO`, `VL_SALDO_REMAN_CONVENENTE`: Saldos remanescentes.  
- `VALOR_GLOBAL_ORIGINAL_CONV`: Valor global original do convênio.
