# RPG de Mesa com Mestre de RPG Inteligente (Google Generative AI)

## Descrição:

Este repositório contém o código Python para um RPG de mesa com um Mestre de RPG inteligente, utilizando a API Generative AI do Google. O Mestre de RPG é guiado por um conjunto de instruções e configurações e gera respostas em formato JSON, que são convertidas em texto Markdown e exibidas ao jogador.

## Funcionalidades:

* Geração de descrições de cenários, eventos e informações.
* Criação de desafios e combates com diferentes níveis de dificuldade.
* Personalização do Mestre de RPG com nome e estilo de narração.
* Integração com botão para simular rolagem de dados.
* Histórico do chat para acompanhar o desenrolar da aventura.

## Requisitos:

* Python instalado
* Conta Google Colab
* API Key do Google Generative AI (obtenha em https://cloud.google.com/ai/generative-ai)

## Como Usar:

1. Clone este repositório em seu Google Colab.
2. Abra o notebook RPG_Mesa_Inteligente.ipynb.
3. Crie o SECRET_KEY em Secrets com a sua API Key do Google Generative AI.
4. Execute as células do notebook na ordem.
5. Siga as instruções na tela para iniciar a aventura.

## Documentação

Para mais informações sobre a API Generative AI, consulte a documentação oficial: https://cloud.google.com/ai/generative-ai
Para tutoriais sobre como usar o Google Colab, acesse: https://colab.research.google.com/

## Exemplos de Uso
### Início da Aventura

> Mestre: A floresta se fecha ao seu redor, as árvores centenárias entrelaçam seus galhos 
> formando um dossel impenetrável à luz do sol. Uma trilha estreita serpenteia pelo 
> chão coberto de musgo, convidando-o a seguir em frente. Você continua pela trilha 
> principal ou procura um caminho alternativo?

### Desafio
> Mestre: Ao chegar a uma clareira, você se depara com um desfiladeiro profundo. Uma 
> ponte de madeira oscilante cruza o abismo, ligando as duas margens. O vento sopra forte, 
> fazendo a ponte balançar perigosamente. Você cruza a ponte ou procura outro caminho?
> (Desafio: 3)

### Combate
> Mestre: Um grupo de goblins emerge das sombras, brandindo lanças e espadas enferrujadas. 
> Eles gritam em uma língua gutural e avançam em sua direção. Quantos goblins você ataca 
> primeiro? (Vida do inimigo: 10 por goblin)

## Observações

* Este é um projeto em desenvolvimento e novas funcionalidades serão adicionadas no futuro.
Relate qualquer problema ou sugestão de melhoria na seção "Issues" do GitHub.
Contribuições:

* Se você deseja contribuir para o desenvolvimento deste projeto, sinta-se à vontade
para enviar um pull request com suas alterações.

## Agradecimentos

Ao Google AI por fornecer a API Generative AI.

## Licença

Este projeto está licenciado sob a licença MIT.
