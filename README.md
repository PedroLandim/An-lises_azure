# Desafio DIO: Análise de Fala e Linguagem Natural com Azure

Este repositório documenta minha prática com os serviços Azure Speech Studio e Azure Language Studio, como parte do desafio proposto pela DIO. O objetivo foi aplicar os conceitos aprendidos em um ambiente prático, explorando ferramentas de inteligência artificial voltadas para reconhecimento de fala e análise de linguagem natural.

## Objetivos do Desafio

- Aplicar conceitos de IA voltados para fala e linguagem
- Utilizar ferramentas cognitivas do Azure em testes reais
- Documentar os processos realizados de forma clara
- Consolidar os aprendizados em um repositório organizado

## Tecnologias Utilizadas

- Azure Portal
- Azure Speech Studio
- Azure Language Studio
- Git e GitHub
- Markdown

## Atividades Realizadas

### Speech Studio

- Criação do recurso Serviço de Fala no Azure
- Testes com transcrição de áudio (speech to text)
- Testes com conversão de texto em fala (text to speech)
- Gravações com retorno em tempo real
- Tradução automática de áudio (fala PT-BR para texto EN)

### Language Studio

- Criação do recurso Serviço de Linguagem no Azure
- Análise de sentimentos em inglês e português
- Extração de frases-chave em conteúdo não estruturado
- Reconhecimento de entidades nomeadas
- Testes com classificação personalizada e serviço de perguntas e respostas

## Resultados Obtidos

Durante a prática, explorei os seguintes cenários e obtive os seguintes resultados:

1. **Transcrição de Áudio (Speech to Text)**  
   Áudio gravado com a frase:  
   _"Superfantástico o balão mágico, o mundo fica bem mais divertido."_  
   Transcrição correta feita pelo sistema.  
   Imagem: `images/audio_gravado.png`

2. **Análise de Sentimentos e Opinião (em Inglês)**  
   Frase analisada:  
   _"Although the service was fast, I found it poorly done and I wouldn’t hire them again."_  
   Resultado: sentimento **negativo**, com destaque positivo para "fast".  
   Imagem: `images/opiniao em ingles.png`

3. **Análise de Sentimentos e Opinião (em Português)**  
   Frase analisada:  
   _"Todas as letras do meu teclado funcionam bem, só o 'o' que não funciona às vezes."_  
   Resultado: sentimento **negativo** com 59% de confiança.  
   Imagem: `images/opiniao em português.png`

4. **Transcrição em Tempo Real**  
   Frase falada com rapidez e clareza:  
   _"Teste, teste, testando aqui, irei fazer uma transcrição em tempo real, irei falar o mais rápido possível. O rato roeu a roupa do rei de Roma e a rainha roeu o resto."_  
   Transcrição foi reconhecida corretamente.  
   Imagem: `images/real_time.png`

5. **Tradução de Fala (PT-BR para EN)**  
   Áudio com fala em português foi traduzido para inglês:  
   _"O rato roeu a roupa do rei de Roma e a rainha roeu o resto."_  
   Resultado da tradução:  
   _"The rat gnawed the clothes of the king of Rome and the queen gnawed the rest."_  
   Imagem: `images/traduzido-PT-EN.png`