# ENEM_CategorizacaoQuestoes_GERAL
Repositório central do projeto de categorização das questões do ENEM  

O objetivo deste projeto é construir um banco de dados estruturado contendo as questões do ENEM, enriquecidas com metadados e classificações semânticas geradas por modelos de linguagem (LLMs), finalmente permitindo consultas por conteúdo, habilidade, ano e diversos outros critérios.  

# ETAPAS
1) Tratamento das imagens: FINALIZADO  
A partir do caderno do ENEM em PDF, exportar para PNG e separar uma questão por imagem, com nome organizado  
https://github.com/AlexandreNP9/TratamentoImagens_CategorizacaoQuestoesENEM  

2) Extração do Contéudo por OCR: EM DESENVOLVIMENTO  
A partir das imagens da fase anterior, utilizar API de OCR para extrair o texto e descrição de figuras das imagens das questões, tudo para .txt  
https://github.com/AlexandreNP9/ExtracaoConteudo_CategorizacaoQuestoesENEM  

3) Análise LLM: A DESENVOLVER  
Análise do .txt da fase anterior, feita por LLM, baseada na matriz de referência do exame e gabarito, resultando em um JSON por questão.  
https://github.com/AlexandreNP9/AnaliseLLM_CategorizacaoQuestoesENEM  

4) Banco de Dados: A DESENVOLVER  
Alimentação do BD centralizado, a partir dos JSONs do passo anterior.  
https://github.com/AlexandreNP9/AlimentacaoBD_CategorizacaoQuestoesENEM  

5) Interface CRUD: A DESENVOLVER  
Interface pesquisável das questões por filtro  
https://github.com/AlexandreNP9/Interface_CategorizacaoQuestoesENEM  

# OUTROS
Provas anteiores  
https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/enem/provas-e-gabaritos  

Matriz do ENEM  
https://download.inep.gov.br/download/enem/matriz_referencia.pdf  

Futuramente, também pretendo associar os descritores e habilidades à BNCC.