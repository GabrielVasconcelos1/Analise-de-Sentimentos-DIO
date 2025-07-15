# Processo, insights e possibilidades aprendidas durante o conteúdo de **"Análise de Sentimentos com Language Studio no Azure AI"**

## **1. Estúdio de Fala:**

**A voz da IA na comunicação - Introdução**

A transcrição de fala para texto e a [Conversão de fala em texto em tempo real](https://speech.microsoft.com/portal/3a8202b21299451ca3ac791302c5e372/speechtotexttoo) são pilares da interação entre humanos e máquinas. A primeira transforma o que falamos em texto escrito, usando algoritmos de reconhecimento de voz. A segunda, por sua vez, usa sistemas de síntese de voz para converter texto em áudio.

Essas tecnologias têm um vasto campo de aplicação, desde assistentes virtuais até ferramentas de acessibilidade para pessoas com deficiência. Apesar de desafios como a precisão em ambientes barulhentos e a naturalidade da fala sintetizada, o avanço contínuo impulsiona uma interação mais intuitiva e inclusiva.

O serviço Speech exemplifica isso, permitindo a transcrição de fala em tempo real, com o texto exibido instantaneamente. Ele também possibilita ouvir gravações enquanto o texto é transcrito, facilitando a análise e o acompanhamento de áudios existentes


- **Exemplo da conversão de fala em texto em tempo real realizada**

![Imagem de Exemplo da conversão da fala em texto em tempo real realizada](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Inputs/Input%201%20speech%20to%20text.png)


## **2. Analise texto com Language Studio:**

**Entendendo Emoções com a Análise de Sentimentos por IA - Introdução**

A [Análise de sentimentos e opiniões](https://language.cognitive.azure.com/tryout/sentiment) por IA usa algoritmos e técnicas de inteligência artificial para identificar e entender as emoções expressas em textos. Isso inclui opiniões, avaliações e mensagens em redes sociais. Essa análise consegue classificar o conteúdo como positivo, negativo ou neutro, e até mesmo identificar nuances como ironia ou sarcasmo.

Para isso, a IA emprega métodos como aprendizado de máquina e processamento de linguagem natural (PLN). Com eles, ela extrai o significado e o contexto das palavras, ajudando empresas e pesquisadores a compreender o sentimento do público sobre produtos, serviços, eventos ou tópicos específicos.

Mesmo com desafios como reconhecer sarcasmo e ambiguidades na linguagem, a análise de sentimentos por IA continua a evoluir. Ela oferece insights valiosos para diversas aplicações, como gerenciar a reputação online, desenvolver produtos e apoiar decisões estratégicas.


- **Exemplo da Análise de sentimentos e opiniões realizada**

**Input:**
***primeiro texto:***
![Imagem de Exemplo do texto da Análise de sentimentos e opiniões 1 ](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Inputs/textodeexemplo.png)

***segundo texto:***
![Imagem de Exemplo do texto da Análise de sentimentos e opiniões 2 ](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Inputs/textodeexemplo2.png)

***terceiro texto:***
![Imagem de Exemplo do texto da Análise de sentimentos e opiniões 3 ](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Inputs/textodeexemplo3.png)


**Output:**

***Análise 1º texto:***

![Primeira imagem de Exemplo da Análise de sentimentos e opiniões gerada 1 ](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados1.1.png)


![Segunda imagem de Exemplo da Análise de sentimentos e opiniões gerada 1.2](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados1.2.png)


![Terceira imagem de Exemplo da Análise de sentimentos e opiniões gerada 1.3](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados1.3.png)


Arquivo JSON gerado: [`ResultadosExaminados.json`](https://github.com/JPLabussiereF/Processamento-de-Linguagem-Natural-Lab03/blob/main/Pratica/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados1.json)


***Análise 2º texto:***

![Primeira imagem de Exemplo da Análise de sentimentos e opiniões gerada 2](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.1.png)

![Segunda imagem de Exemplo da Análise de sentimentos e opiniões gerada 2.1](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.2.png)

![Terceira imagem de Exemplo da Análise de sentimentos e opiniões gerada 2.3](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.3.png)

![Quarta imagem de Exemplo da Análise de sentimentos e opiniões gerada 2.4](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.4.png)

![Quinta imagem de Exemplo da Análise de sentimentos e opiniões gerada 2.5](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.5.png)


Arquivo JSON gerado: [`ResultadosExaminados.json`](https://github.com/JPLabussiereF/Processamento-de-Linguagem-Natural-Lab03/blob/main/Pratica/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.json)


***Análise 3º texto:***

![Primeira imagem de Exemplo da Análise de sentimentos e opiniões gerada 3](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.1.png)

![Segunda imagem de Exemplo da Análise de sentimentos e opiniões gerada 3.2](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.2.png)

![Terceira imagem de Exemplo da Análise de sentimentos e opiniões gerada 3.3](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.3.png)

![Quarta imagem de Exemplo da Análise de sentimentos e opiniões gerada 3.4](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.4.png)

![Quinta imagem de Exemplo da Análise de sentimentos e opiniões gerada 3.5](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.5.png)

![Sexta imagem de Exemplo da Análise de sentimentos e opiniões gerada 3.6](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.4.png)

![Sétima imagem de Exemplo da Análise de sentimentos e opiniões gerada 3.7](https://github.com/GabrielVasconcelos1/Analise-de-Sentimentos-DIO/blob/main/Analise%20de%20sentimentos%20-%20Azure/AnalyzetextwithLanguageStudio/Outputs/ResultadosExaminados2.5.png)




## Referências
Explore Speech Studio - (https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)

Analyze text with Language Studio - (https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

