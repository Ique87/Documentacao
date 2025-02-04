# OS 10801
|PASSO|DESCRICAO|STATUS|
|:---:|---------|------|
|1|Telas/Relatorios/Atualiza��es|Realizado/Liberado|
|2|Exporta��es|Realizado/Liberado|
|3|Importa��es|Em Andamento|
|4|Auditorias|N�o Realizado|
||||

## Scripts 1415 e 1416
---
## Principais altera��es no Guia Pr�tico da EFD-ICMS/IPI � vers�o 3.1.0
---
### 1. Descontinua��o dos c�digos 04 e 05 da tabela 4.1.2 � Tabela Situa��o de Documentos a partir de 31/12/2022.
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|1.1|Incluir verifica��o nas auditorias de NF�s|Passo 4|
---
### 2. Inclus�o dos registros 0221, C855, C857, C895, C897, D700, D730, D731, D735, D737, D750, D760 e D761
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|2.1|0221 - Somente para 2024 - ser� criada nova Os;|----------|
|2.2|C855, C857, C895, C897 - novas tabelas SF_C855 e SF_C857;|----------|
|2.2.1|Criar novas telas|Realizado/Liberado|
||Criar Ids Arquivo|Realizado/Liberado|
||Exporta��o|Realizado/Liberado|
||Verificar procedures de gera��es de dados na exporta��o de Speds;|Realizado/Liberado|
||Importa��o TMP|Realizado|
||Importa��o Layouts|Em Andamento|
|2.3|D700, D730, D731, D735, D737, D750, D760 e D761 - novos campos nas tabelas AC_C700_ENTRADA e AC_C700_SAIDA;|----------|
|2.3.1|Criar novo id_modelo_documento para c�digo 62;|Realizado/Liberado|
|2.3.2|Alterar telas de notas fiscais|Realizado/Liberado|
||Incluir novos campos|Realizado/Liberado|
||Criar Ids Arquivo|Realizado/Liberado|
||Exporta��o|Realizado/Liberado|
||Verificar procedures de gera��es de dados na exporta��o de Speds;|Realizado/Liberado|
||Importa��o TMP|Realizado|
||Importa��o Layouts|Em Andamento|
---
#### 3. Inclus�o da exce��o n� 2 na valida��o do registro C800
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|3.1|Tratar na importa��o de dados||
---
#### 4. Altera��o da regra de valida��o do campo 06 do registro C170
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|4.1|Verificar valida��o na auditoria para incluir a excess�o: exceto se o campo 07 - TIPO_ITEM do registro 0200 for igual a 07 (Material de Uso e Consumo);||
---
#### 5. Altera��o da regra de valida��o do campo 09 do registro C800
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|5.1|Verificar valida��o na auditoria para incluir a excess�o: A partir de Jan/2023, o destinat�rio n�o dever� ser informado.|----------|
||Layout|Realizado/Liberado|
||Auditoria|Passo 4|
---
#### 6. Altera��o da regra de valida��o do campo 02 dos registros C181, C330, C380, C430, C480, C815 e C880
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|6.1|Verificar valida��es nas auditorias conforme listadas no guia pr�tico|Passo 4|
---
#### 7. Altera��o da regra de valida��o do campo 06 do registro C185 
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|7.1|Verificar valida��es nas auditorias conforme listadas no guia pr�tico|Passo 4|
---
#### 8. Altera��o do tamanho do campo 02 (15 para 60 caracteres) do registro C111 
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|8.1|Alterar Tela|Realizado/Liberado| 
||Relat�rios|Realizado/Liberado|
||Trigger|Realizado/Liberado| 
||Exporta��o|Realizado/Liberado|
||Layouts Importa��o|Em Andamento| 
---
#### 9. Altera��o do tamanho do campo 03 (15 para 60 caracteres) dos registros E112, E230, E312 e 1922
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|9.1|Alterar Tela|Realizado/Liberado| 
||Relat�rios|Realizado/Liberado|
||Trigger|Realizado/Liberado| 
||Exporta��o|Realizado/Liberado|
||Layouts Importa��o|Em Andamento| 
---
#### 10. Altera��o do tamanho do campo 06 (15 para 60 caracteres) dos registros E116, E250, E316 e 1926
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|10.1|Alterar Tela|Realizado/Liberado| 
||Relat�rios|Realizado/Liberado|
||Trigger|Realizado/Liberado| 
||Exporta��o|Realizado/Liberado|
||Layouts Importa��o|Em Andamento| 
---
#### 11. Inclus�o de uma nova op��o de indicador para o campo 02 do registro K010.
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|11.1|Novo parametro IN_PARAMETRO_EMPRESA.DM_BLOCOK_TP_LAYOUT|----------| 
||Telas|Realizado/Liberado|
||Trigger|Realizado/Liberado| 
||Exporta��o |Realizado/Liberado|
||Layouts Importa��o|Em Andamento| 
||Auditorias|Passo 4|
---
## Principais altera��es no Guia Pr�tico da EFD-ICMS/IPI � vers�o 3.1.1
---
#### 1. Corre��o da orienta��o de preenchimento do campo 05 do registro C190 � retirada do termo FCP
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|1.1|Verificar view e layouts de exporta��o|Sem altera��o|
---
#### 2. Inclus�o dos registros C597, C857, C897 e D737 na regra de obrigatoriedade do registro 1900
|ITEM|DESCRICAO|STATUS|
|----|---------|------|
|2.1|Alterar procedure de gera��o SP_GERA_SF_1900, verificar layouts de exporta��o.|Realizado/Liberado|
---
## OBSERVA��ES
---
    Por favor aplicar a altera��o indicada abaixo, verificar se precisa colocar a mesma regra no 
    arquivo do sped fiscal. Utilizar a OS 10801. Email Flavia/Gabriel
---