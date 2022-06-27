<h1 align="center"> NIKE-BOT </h1>


![Badge versao](https://img.shields.io/badge/version-1.7.2-blue)

## Índice 

* [Como rodar](#como-rodar)
* [Funcoes](#funcoes)
* [Status do Projeto](#status-do-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)


A bot that cop everything in nike.com.br !

## Como rodar

Ao entrar no programa, você verá deverá inserir o cookie IFC

Para pegar o cookie IFC, basta colar no console o código a seguir:

```javascript:{function getCookie(o){const t=`; ${document.cookie}`.split(`; ${o}=`);if(2===t.length)return t.pop().split(";").shift()}IFC=getCookie("IFCSHOPSESSID"),alert("IFCSHOPSESSID: "+IFC);}```

![solicitando cookie](https://user-images.githubusercontent.com/108239405/175842904-37d0a43c-4fe0-4af9-81fe-66449d80bfc8.png)

Após colar o cookie no programa, digite o nome da task ( usado para mandar o webhook e para o controle ). 
Se não digitar nada o nome será gerado automaticamente.

![Escolhendo nome da task](https://user-images.githubusercontent.com/108239405/175843443-4e980015-ad0e-4597-bd1f-2685f3abdaa0.png)

Logo após isso, o bot vai pegar automaticamente alguns dados na sua conta da nike.

Você deverá escolher em seguida, um dos 3 modos disponíveis. 

Veja o que cada modo faz no modulo de FUNCOES.

![Modos](https://user-images.githubusercontent.com/108239405/176005226-399e1f63-a17c-4aa6-9542-73e341a645b8.png)


Após escolher, se for restock mode basta aguardar ele finalizar a compra.

se for quicktask mode basta colocar o sku e esperar

se for drop mode basta colocar o sku, horario e esperar

Quando o pedido for finalizado, chegará uma mensagem parecida com essa no seu discord: 

![Webhook](https://user-images.githubusercontent.com/108239405/176006965-e0004e09-722f-4571-bde3-7de5f46a6df3.png)


## Funcoes

O bot é 100% em requisições, a única coisa que deve ser feito é abrir o browser para fazer o login e pegar o valor do cookie de sessão.
Após isso, não é necessário o navegador estar aberto.

- Modo quicktask : em um caso de flashdrop, o bot é excelente e precisa apenas do sku do produto para adicionar e finalizar.
- Modo drop : você coloca o sku do produto e o horario para iniciar, quando a hora chegar, ele ira adicionar e finalizar automaticamente.
- Modo restock : caso você adicione o produto pelo celular, basta pegar o cookie de sessão e colocar no bot, ele ira monitorar o estoque e quando o produto estiver disponivel ele vai finalizar o pedido normalmente

- Suporte para proxy : funciona com ou sem o uso de proxy, porém recomendamos fortemente o uso para evitar ban e para ter mais chances de cop!
- Webhook : quando o pedido for finalizado, será enviado no discord um webhook onde será possível ver dados do pedido.
- Servidor no discord : 100% de suporte em qualquer duvida ou dificuldade com o bot.

## Status do Projeto

O bot está 100% concluído e atualizações são feitas toda vez em que é detectado alguma forma de melhoria ou bug.

Atualmente na versão 1.7.2

Versão 2.0.0 em produção, onde a principal melhoria será suportar sms.

## Tecnologias utilizadas

- Javascript





