# ENEM_CategorizacaoQuestoes_GERAL
Repositório central do projeto de categorização das questões do ENEM

1) Pré-tratamento das imagens: FINALIZADO  
Deixar uma questão por imagem  
https://github.com/AlexandreNP9/ENEM_CategorizacaoQuestoes_PreTratamento  

2) Extração do Contéudo por OCR: EM DESENVOLVIMENTO  
API de OCR, imagem para .txt  
https://github.com/AlexandreNP9/ENEM_CategorizacaoQuestoes_ExtracaoConteudo  

3) Análise LLM: A DESENVOLVER  
Análise da questão textual, gabarito e alternativas para construção de base de dados  
https://github.com/AlexandreNP9/ENEM_CategorizacaoQuestoes_AnaliseLLM  

4) Interface CRUD: A DESENVOLVER  
Interface pesquisável das questões por filtro  
https://github.com/AlexandreNP9/ENEM_CategorizacaoQuestoes_Interface  

# O QUE É?
Este projeto busca criar um banco de dados estruturado com questões do ENEM, categorizadas por:  
Conteúdo da questão (descritor)  
Habilidades avaliadas  
Metadados (ano, caderno, etc.)  
Gabarito e justificativa das alternativas

Matriz disponível em https://download.inep.gov.br/download/enem/matriz_referencia.pdf

Futuramente, também pretendo associar os descritores e habilidades à BNCC.

# COMO FUNCIONA?
1. Pré-processamento das questões  
Separação das imagens por questão.  
Organização dos dados básicos.  

2. Extração de texto  
Uso da API do Google Lens para OCR (reconhecimento de caracteres).  

3. Classificação semântica e banco de dados  
Envio do enunciado e gabarito para uma LLM, identificando o conteúdo principal, habilidade associada, metadados e justificativas das altertanivas  

4. Construção de interface  
Possibilitando consultas como:  
Todas as questões de Trigonometria  
Todas as questões de História do Brasil  

# STATUS DO PROJETO
Semi-automático: diversos processos já foram automatizados via código, mas ainda existem etapas que precisam ser realizadas manualmente.  
Em desenvolvimento 🚧  
