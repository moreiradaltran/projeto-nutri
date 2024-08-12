# Projeto Nutrição
## Descrição
Este código HTML cria uma página web para um formulário de teste de aceitabilidade da alimentação escolar. O formulário coleta informações sobre a escola, o ano de ensino e a data atual. Após o envio do formulário, o usuário é direcionado para uma seção de feedback onde pode avaliar a alimentação escolar usando uma escala de satisfação com ícones representando diferentes níveis de aprovação.

## Estrutura do Código
### HTML:
O código HTML estrutura a página com um formulário inicial e uma seção de feedback.
O formulário coleta dados sobre a escola, o ano de ensino e a data atual.
A seção de feedback apresenta um conjunto de botões para avaliar a alimentação escolar.

### CSS:
 Define estilos para a página, incluindo layout responsivo, cores, tamanhos e espaçamentos.
 Estiliza o formulário e os elementos de feedback, garantindo uma boa apresentação visual.

### JavaScript:
Manipula o envio do formulário e a exibição da seção de feedback.
Armazena os dados do formulário no localStorage e exibe a seção de feedback após o envio.
Envia os dados coletados para uma API externa usando fetch e axios.

## Funcionalidades
Formulário de Coleta: Permite ao usuário selecionar a escola, o ano de ensino e a data.
Seção de Feedback: Após o envio do formulário, o usuário pode avaliar a alimentação escolar usando ícones.
Armazenamento e Envio de Dados: Os dados são armazenados no localStorage e enviados para APIs externas.

## Instruções de Uso
Abrir o Arquivo: Abra o arquivo HTML em um navegador para visualizar e interagir com a página.
Preencher o Formulário: Selecione sua escola, ano de ensino e data no formulário.
Enviar o Formulário: Clique no botão "Enviar" para visualizar a seção de feedback.
Avaliar: Escolha uma das opções de avaliação para enviar o feedback.

## Dependências
Axios: Utilizado para enviar dados para o SurveyMonkey API.
Fetch API: Utilizado para enviar dados para a API do SheetMonkey.
Personalizações
SurveyMonkey API: Substitua YOUR_SURVEY_ID e YOUR_ACCESS_TOKEN com suas credenciais do SurveyMonkey para integração completa.

## Contribuições
Para contribuir com este projeto, por favor, faça um fork do repositório, faça suas alterações e envie um pull request.

