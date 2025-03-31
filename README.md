# ICJ_Painel_Fomento_2008_2024
Consolidação dos dados da Iniciação Científica Júnior (ICJ) extraídos do Painel de Fomento do CNPq - 2008 a 2024

# Painel de Fomento - Iniciação Científica Júnior (ICJ) - CNPq (2008–2024)

Este repositório reúne os procedimentos realizados para consolidar os dados da Iniciação Científica Júnior (ICJ) disponibilizados pelo CNPq por meio do Painel de Fomento em CT&I. O objetivo é organizar em um único banco os dados brutos dos anos de 2008 a 2024.

## 📂 Estrutura

- `notebooks/`: Notebook do Google Colab com o código de importação, limpeza e junção dos arquivos.
- `docs/`: Documentação detalhada dos procedimentos, conforme normas ABNT.
- `dados/`: Diretório sugerido para os arquivos ICJ_2008.xlsx a ICJ_2024.xlsx (não incluídos neste repositório).

## ⚙️ Etapas Realizadas

1. Importação das bibliotecas necessárias (`pandas` e `google.colab.files`)
2. Upload dos arquivos `.xlsx` com nome padrão `ICJ_<ano>.xlsx`
3. Função personalizada para:
   - Ignorar a primeira linha (vazia)
   - Usar a segunda linha como cabeçalho
   - Adicionar coluna com o ano correspondente
4. Consolidação de todos os anos em um único DataFrame (`df_total`)
5. Validação da estrutura do banco unificado (`head()` e `info()`)

> ⚠️ Este repositório registra apenas as etapas de consolidação dos dados. As análises exploratórias e estatísticas serão documentadas separadamente.

## 👤 Autor

Tiago Ribeiro dos Anjos  
tiago15anjos@gmail.com
