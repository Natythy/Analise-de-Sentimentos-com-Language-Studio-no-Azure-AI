# Analise de Sentimentos com Language Studio no Azure AI

![Static Badge](https://img.shields.io/badge/Status_Projeto:-Concluído_(11/Abr/2024)-green)

## Descrição do Projeto

Este desafio é o 4º do Bootcamp [Microsoft Azure AI Fundamentals](https://web.dio.me/track/microsoft-azure-ai-fundamentals). Ele tem como objetivo aprender a usar e testar a ferramenta Language Studio.

## Acesso

O processo de acesso e criação de recursos para a exploração dos recursos já citados foram feitos com base nas orientações disponíveis pela Microsoft no seguint site (as instruções estão em inglês):

[Análise de Sentimento](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

## Insights

### Texto 1: "O céu noturno brilha com estrelas distantes."
- O texto foi escolhido pela minha interpretação da neutralidade dos sentimentos. E foi constatado que a ferramenta detectou a mesma neutralidade.

[screen-capture (3).webm](https://github.com/Natythy/Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/88320974/09bed291-7da6-4d4c-9fb6-d6d41e8d2ec3)


### Texto 2: "O aroma do café fresco pela manhã é reconfortante."
- A escolha do texto foi motivada pela positivada atribuíada ao adjetivo que referencia a palavra "aroma" na gramática. A ferramenta detectou a mesma relação entre a palavra aroma e o adjetivo "reconfortante". Indicando sua positividade.

[screen-capture (4).webm](https://github.com/Natythy/Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/88320974/080450e5-161a-4578-9f0e-ff125491abf1)

### Texto 3: "O Chalé da Solidão, situado nas remotas montanhas, prometia ser um refúgio tranquilo para escapar da agitação da cidade. No entanto, minha estadia se transformou em um pesadelo que jamais esquecerei."
- O texto em questão é uma review negativa sobre um hotel. A ferramenta separa em duas frases. Na 1ª frase, a conclusão foi de ser uma frase negativa. Apesar de na minha interpretação houve uma dificuldade em entender o sentimento, isso se deve pela não conclusão da opnião dentro da frase.
- Na 2ª frase há a conclusão da negatividade do texto, com o adjetivo "pesadelo" relacionado à palavra "estadia". Fato que foi efetivamente detctada pela ferramenta.

[screen-capture (5).webm](https://github.com/Natythy/Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/88320974/015e7102-5517-49ed-b796-9ba6100376b0)

## Conclusões

A ferramenta é efetiva no que prometem, é uma ferramenta que otimiza o tempo de muitas pessoas que precisam extrair sentimento de texto muito longos ou um volume grande de dados. Vale muito apena testar e sendo o caso incorporar na sua rotina.

## Limpando o ambiente

> [!WARNING]
> Após a conclusão do projeto, se não for reaproveitar os recursos utilizados, é aconselhável excluí-los, bem como os grupos de recursos, para que não haja cobranças indevidas na sua Azure Subscription.
