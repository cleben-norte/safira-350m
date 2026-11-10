# Safira 350M

**Em planejamento · IA aplicada à análise de dados**

A Safira é um projeto de assistente em português para responder a perguntas sobre vendas e margens. O objetivo é treinar um modelo de linguagem do zero, com pesos inicialmente aleatórios, e avaliar se ele consegue consultar dados e fundamentar as respostas.

## Primeira versão

- **Modelo:** referência densa com meta de aproximadamente 350 milhões de parâmetros. O tamanho final depende dos resultados do piloto.
- **Ferramentas:** consultas SQL somente leitura sobre dados sintéticos, cálculo de variações e recuperação de documentos com definições dos indicadores (RAG).
- **Avaliação:** perguntas separadas do treino, com respostas de referência. Medir acerto numérico, escolha da ferramenta, fundamentação, latência e memória. Incluir perguntas ambíguas e casos com dados ausentes.

## Marcos

- [x] Documentar o escopo e os critérios de avaliação.
- [ ] Definir as ferramentas e preparar a base sintética de vendas.
- [ ] Executar um treino piloto e registrar configuração, custo computacional e sinais de aprendizado.
- [ ] Integrar as ferramentas e avaliar o conjunto de perguntas.
- [ ] Publicar instruções de reprodução, resultados medidos e uma demonstração quando validada.

Esta publicação inicial contém o plano do projeto. O código, os pesos e os resultados experimentais serão publicados conforme o desenvolvimento.

Projeto de [Cleben do Norte Neto](https://github.com/cleben-norte).
