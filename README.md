# Como visualizar a quantidade de processos abertos para acessar uma pagina
   Pré requisitos
-Sistema linux
-chromium e firefox instalados na maquina
## Chromium
### Após baixar a aplicação em
````
https://chromium.woolyss.com/download/en/
````
- execute o comando em um terminal:
- a apagina sera aberta na web
````
--chromium --incognito http://desconstruindoaweb.com.br
````
- em outro terminsal execute:
- o output sera a quantidade de procesos abertos
``````
ps xufa | grep [c]hromium | wc -l
``````
 # Firefox
- execute o comando em um terminal:
- a apagina sera aberta na web
````
--firefox incognito http://desconstruindoaweb.com.br
````
- em outro terminsal execute:
- o output sera a quantidade de procesos abertos
``````
ps xufa | grep [c]hromium | wc -l

