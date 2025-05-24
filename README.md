# DIO-CognitiveSearchAzureAI

# Microsoft Azure AI Fundamentals</div>
## Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados


- A Pesquisa de IA do Azure fornece recuperação de informações seguras em escala sobre o conteúdo de propriedade do usuário nas aplicações de pesquisa tradicionais e generativos.
- A recuperação de informações é fundamental para qualquer aplicação que apresenta texto e vetores.
- Os cenários comuns incluem pesquisa de catálogos ou documentos, exploração de dados e aplicações de chat sobre os dados de aterramento proprietários.
- Document Intelligence é um dos âmbitos onde a aplicação de IA se faz muito útil e eficaz. Envolve a utilização de multíplos meios de processamento de documentos, possibilitando a extração de suas informações de forma mais eficiente ao permitir o entendimento de suas informações. Dessas ferramentas, vale citar o OCR (Optical Character Recognition) que é capaz de identificar texto em imagens de documentos digitalizados (facilitando a pesquisa destes textos dentro de uma base de dados) extrair frases-chave e dados de forma automática e até mesmo análisar sentimentos.


## A Pesquisa

***

Azure AI Search: gerencia a indexação e pesquisa dos documentos (também fornece um assistente para realizar queries no Index recém criado, retornandos os resultados em JSON).

Azure AI Services: provem funcionalidades de IA necessárias para enriquecer os dados dos documentos com insights.

Storage account: armazena os documentos (em blob containers).


O procedimento de Document Intelligence requer: o uso dos três recursos Azure acima; a criação de um container de armazenamento (no qual deverá ser feito upload de arquivos para o mesmo).

Uma vez que os arquivos estão no container, através de um assistente presente no portal Azure, é possível utilizar o Azure AI Search para criar um index e começar a extrair insights dos arquivos após selecionar as skills requisitadas para enriquecer a extração de informações dos arquivos (cabe selecionar as que melhor se enquadrarem para o arquivo a ser análisado). Nos resultados, é possível filtrar as frases-chave, pesquisar partes que carregam algum sentimento, dentre outros diversos cenarios nos quais a análise pode revelar insights valiosos para quem os detém.


***
