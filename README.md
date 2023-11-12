#Agar.io BR
Uma implementação de servidor Agar.io de código aberto, baseada em [Ogarserv](https://github.com/JaraLowell/OgarServ/releases/tag/1.5.9) de Jaralowell e [Cigar](https://github.com/CigarProject /Charuto)

## Como acessar o servidor
Vá para localhost se você definir a porta como 80, vá para localhost:80
## Rastreador de servidor
  [Rastreador de Servidor](http://ogar3tracker.wdr.icu/)
  ## Informações
Como Agar.io BR é escrito em Node.js, você deve ter o Node.js e seu módulo "ws" instalados para usá-lo (a menos que você esteja no Windows). Geralmente você pode baixar o Node usando o gerenciador de pacotes da sua distribuição (para sistemas do tipo unix) ou no [site do Node](http://nodejs.org). Para instalar o módulo “ws” necessário, abra a linha de comando do sistema (cmd para windows, terminal para mac) e digite “npm install ws”.

Embora o Agar.io BR permita que você execute o servidor mestre Agar.io e o servidor de jogo separadamente, atualmente é recomendado que você execute os dois servidores juntos até que o servidor mestre esteja mais implementado. Alternativamente, você pode executar apenas o servidor do jogo e usar um mod do lado do cliente para conectar-se ao endereço IP do servidor.

```sh
~$ git clone git:github.com/BUGG404M3U/Agar.io BR.git "Agar.io BR"
~$ npm install ./Agar.io BR
~$ npm início
```

Atualmente, Agar.io BR escuta nesta porta (por enquanto):
* *:80 - para o servidor do jogo


Observe que em alguns sistemas, pode ser necessário executar o processo como root ou elevar seus privilégios para permitir que o processo escute nas portas necessárias.

## Configurando Agar.io BR
Use gameserver.ini em src para modificar o campo de configurações do Agar.io BR.
