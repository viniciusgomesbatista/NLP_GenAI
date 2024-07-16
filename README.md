# Projeto de Análise de Sentimento e Emoção em Pesquisa NPS

Este projeto tem como objetivo realizar uma análise detalhada dos dados de pesquisa NPS (Net Promoter Score) utilizando técnicas avançadas de Processamento de Linguagem Natural (NLP). O projeto envolve várias etapas, desde a análise de sentimento até a visualização dos resultados.

## Índice

- [Descrição do Projeto](#descrição-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Etapas do Projeto](#etapas-do-projeto)
  - [Análise de Sentimento com TextBlob](#análise-de-sentimento-com-textblob)
  - [Análise de Sentimento com VADER](#análise-de-sentimento-com-vader)
  - [Análise de Sentimento e Emoção com BERT e Modelos de Transformadores](#análise-de-sentimento-e-emoção-com-bert-e-modelos-de-transformadores)
  - [Visualização com Word Cloud](#visualização-com-word-cloud)
- [Próximos Passos](#próximos-passos)
- [Como Contribuir](#como-contribuir)
- [Licença](#licença)

## Descrição do Projeto

O projeto visa analisar os dados de pesquisa NPS para extrair insights valiosos sobre a percepção dos clientes. Utilizando diversas bibliotecas e modelos de NLP, realizamos a análise de sentimento e emoção para entender melhor o feedback dos clientes.

## Tecnologias Utilizadas

- **Python**: Linguagem principal utilizada no projeto.
- **TextBlob**: Biblioteca usada para análise de sentimento.
- **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: Ferramenta utilizada para análise de sentimento.
- **BERT e Modelos de Transformadores**: Utilizados para análise avançada de sentimento e emoção.
- **Word Cloud**: Ferramenta para visualização de palavras mais frequentes nos comentários.

## Etapas do Projeto

### Análise de Sentimento com TextBlob

Utilizamos a biblioteca [TextBlob](https://textblob.readthedocs.io/en/dev/) para realizar a análise de sentimento inicial nos dados de pesquisa NPS. O TextBlob é fácil de usar e fornece polaridade (sentimento positivo ou negativo) e subjetividade (objetividade ou subjetividade) dos textos.

### Análise de Sentimento com VADER

Para uma análise de sentimento mais precisa em textos curtos, como comentários de pesquisa NPS, utilizamos a ferramenta [VADER](https://github.com/cjhutto/vaderSentiment). O VADER é especializado em capturar nuances de sentimento em textos de redes sociais e é eficaz para analisar feedback de clientes.

### Análise de Sentimento e Emoção com BERT e Modelos de Transformadores

Para uma análise mais avançada, utilizamos modelos de transformadores como [BERT](https://github.com/google-research/bert). Esses modelos permitem uma análise profunda de sentimentos e emoções nos comentários, capturando contextos complexos e sentimentos subjacentes.

### Visualização com Word Cloud

Utilizamos a biblioteca [Word Cloud](https://github.com/amueller/word_cloud) para criar visualizações das palavras mais frequentes nos comentários de NPS. Isso nos ajuda a identificar rapidamente os temas mais comuns e importantes mencionados pelos clientes.

## Próximos Passos

- Implementar uma interface gráfica para facilitar a interação com o sistema.
- Explorar outras técnicas de NLP, como análise de tópicos e resumo automático de textos.
- Integrar o sistema com dashboards interativos para visualização dos resultados.

## Como Contribuir

Contribuições são bem-vindas! Se você deseja contribuir com este projeto, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para a sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Faça o push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
