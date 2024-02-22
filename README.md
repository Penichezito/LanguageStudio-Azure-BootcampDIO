# LanguageStudio-Azure-BootcampDIO

Neste LAB, exploramos o uso do Azure Speech Studio e a análise linguística proporcionada pelo Language Studio. Durante a prática, aprofundamos nosso entendimento sobre como aproveitar essas ferramentas avançadas da Microsoft Azure. Focamos em aprimorar nossas habilidades na implementação de soluções de análise de fala e linguagem, abrindo portas para uma compreensão mais ampla e prática das capacidades oferecidas por essas tecnologias inovadoras.

# ***Analise avaliações no Language Studio***

1. Num navegador web, navegue até Language Studio em https://language.cognitive.azure.com .

2. Na página inicial Bem-vindo ao Language Studio , selecione a guia Classificar texto e, em seguida, selecione o bloco Analisar sentimento e extrair opiniões .

3. Em Selecionar idioma do texto , selecione Português .

4. Em Selecione seu recurso do Azure , selecione seu recurso.

5. Em Digite seu próprio texto, carregue um arquivo ou use nosso texto abaixo de exemplo , copie e cole a seguinte revisão:

```
Bom hotel e funcionários
 The Royal Hotel, Londres, Reino Unido
 02/03/2018
 Quartos limpos, bom serviço, excelente localização perto do Palácio de Buckingham e da Abadia de Westminster, e assim por diante. Nós apreciamos completamente a nossa estadia. O pátio é muito tranquilo e fomos a um restaurante que faz parte do mesmo grupo e é indiano (costa oeste com muito peixe) com estrela Michelin. Tivemos o menu de degustação que foi fabuloso. Os quartos eram muito bem decorados com cozinha, sala, quarto e banheiro enorme. Totalmente recomendado.

```

6. Revise a saída, O resultado vai ser esse abaixo. Observe que o documento é analisado quanto ao sentimento, assim como cada frase . Selecione Frase 1 para mostrar a análise de sentimento dessa frase.

![analise de sentimento azure](https://github.com/Penichezito/LanguageStudio-Azure-BootcampDIO/blob/main/inputs/sentimentos-azure.jpg)

![resultado feedback 2](https://github.com/Penichezito/LanguageStudio-Azure-BootcampDIO/blob/main/inputs/result2.jpg)

![resultado feedback analise texto](https://github.com/Penichezito/LanguageStudio-Azure-BootcampDIO/blob/main/inputs/result-analise-sentimento.jpg)


Observe que há um sentimento geral seguido por pontuações próximas a três categorias: pontuação positiva , pontuação neutra e pontuação negativa . Em cada uma das categorias é atribuída uma pontuação entre 0 e 1. Essas pontuações de confiança indicam a probabilidade do texto fornecido ser um sentimento específico.
