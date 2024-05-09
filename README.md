# 🤖 ChatBot integrado com o Google Gemini ✨

## Esse ChatBot foi programado em Python e se conecta com o Google Gemini através de uma API para responder às suas perguntas.

## Instruções básicas de uso:

## 1 - Antes de rodar o programa vá ao passo número 2 e insira sua API Key do Google.
Para consegui-la vá até [Google Ai Studio](https://aistudio.google.com/app/apikey), faça login na sua conta do Google e crie sua API KEY.
Após criá-la basta colar ela no lugar do texto "INSIRA AQUI SUA API KEY DO GEMINI" (Mantenha ela entre aspas, para o programa entender que é uma STRING)

⚠️ ATENÇÃO: NÃO COMPARTILHE SUA API KEY COM NINGUÉM E NÃO DISPONIBILIZE SEU PROGRAMA COM SUA API KEY SALVA NELE! ⚠️

## 2 - No passo 3 listamos todos os modelos do Gemini que estão disponíveis. 
Neste Programa utilizaremos a versão "gemini-1.0-pro" já que esta é a versão mais estável e que nos possibilita fazer algumas configurações extras dos parâmetros de resposta.

## 3 - No passo 4 faça a configuração dos parâmetros de resposta do Gemini.

O campo *"candidate_count"* representa o número de variações de resposta a serem retornadas.

**Este valor precisa ser 1.**


O campo *"temperature"* é usado para amostragem durante a geração da resposta. A temperatura controla o grau de aleatoriedade na seleção do token. Temperaturas mais baixas são boas para solicitações que exigem uma resposta menos aberta ou criativa, enquanto temperaturas mais altas podem levar a resultados mais diversos ou criativos.

**Para o 'gemini-1.0-pro' mantenha o intervalo entre 0.0 - 1.0**

As "Safety Settings" configuram o limite de bloqueio de respostas que podem pertencer à categoria de segurança (ódio, sexual, perigoso...) especificada com base na probabilidade.

BLOCK_NONE

BLOCK_LOW_AND_ABOVE

BLOCK_MED_AND_ABOVE

BLOCK_ONLY_HIGH


*Para mais informações sobre as configurações visite a [Documentação da API Gemini](https://cloud.google.com/vertex-ai/generative-ai/docs/model-reference/gemini?hl=pt-br).*

## 4 - Depois de realizar as configurações o ChatBot já pode ser utilizado.

Execute o programa, vá no passo 6 e utilize o Prompt para fazer a sua solicitação.
Pergunte quantas vezes quiser e para finalizar o chat simplesmente envie a palavra "fim".
