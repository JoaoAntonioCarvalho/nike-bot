# nike-bot
A bot that cop everything in nike.com.br

Ao entrar no programa, você verá deverá inserir o cookie IFC
Para pegar o cookie IFC, basta colar no console o código a seguir:

```javascript:{function getCookie(o){const t=`; ${document.cookie}`.split(`; ${o}=`);if(2===t.length)return t.pop().split(";").shift()}IFC=getCookie("IFCSHOPSESSID"),alert("IFCSHOPSESSID: "+IFC);}```

![solicitando cookie](https://user-images.githubusercontent.com/108239405/175842904-37d0a43c-4fe0-4af9-81fe-66449d80bfc8.png)

Após colar o cookie no programa, digite o nome da task ( usado para mandar o webhook e para o controle )
Se não digitar nada o nome será gerado automaticamente.

![Escolhendo nome da task](https://user-images.githubusercontent.com/108239405/175843443-4e980015-ad0e-4597-bd1f-2685f3abdaa0.png)


