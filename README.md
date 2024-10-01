# etiquetas.io ESL Meeting room display

## Contents
- [Calendários Suportados](#Calendários-Suportados)
- [Como pegar o arquivo .ICS ou .ICAL da sua Agenda ?](#Como-pegar-o-arquivo-.ICS-ou-.ICAL-da-sua-Agenda-?)
- [Instalação](#Installation)

## Calendários Suportados

A agenda é linkada com um feed ical ICS de link público, dependendo da URL e o domínio que você está usando, será necessário desabilitar o CORS do seu navegador ou colocá-lo em uma Whitelist

- ✔ Calendário de Outlook
- ✔ Calendário do Google ( Gmail e Gsuite Workspace )
- 
## Como pegar o arquivo .ICS ou .ICAL da sua Agenda ?
This largley depends on what calendar you are using. \
(See "Supported calendars" for a list of calendar this PWA has been tested with)

### Calendário do Outlook
Para o Outlook você pode publicar o feed ICS se você for em:
- Settings (Cog up in the right corner), 
- Todas as configuração dos calendários outlook, 
- Calendários Compartilhados, 
- Publicar um calendário

[Link para um Tutorial da Microsoft](https://support.microsoft.com/en-us/office/share-your-calendar-in-outlook-on-the-web-7ecef8ae-139c-40d9-bae2-a23977ee58d5)\
[Link de como compartilhar o calendário da Agenda Outook](https://answers.microsoft.com/en-us/outlook_com/forum/all/how-do-i-publish-a-room-calendar/2c1f5f65-4e74-40fb-b9b2-e8c8fe34ba3b)

### Calendário do Google Agenda
For Google Calendar you can publish an ICS feed if you go to 
- Settings (Cog up in the right corner),
- Choose the calednar you want to choose, (in the left menu)
- Make your calendar publicaly available under "Access permissions for events",
- To get the direct ics link go to "Integrate calendar" section and there it is in the "Public adress in iCal format" box
[Link to Google documentation](https://support.google.com/calendar/answer/37083?hl=en)

## Instalação (Em desenvolvimento)

1. Clone o repositório GIT, e hospede o código em um WebServer.

    -  Você pode analisar o código e customizar com sua marca !

2. Compartilhe ou Publique o seu calendário em um feed ICS com uma URL que o seu hardware pode acessar. (ver [Como pegar um  ICAL/ICS feed do seu calendário](#How-to-get-ICAL/ICS-feed-from-your-calendar))

3. On your hardware navigate to the public webpage and [download the PWA](https://support.google.com/chrome/answer/9658361?hl=en&co=GENIE.Platform%3DAndroid) ([on ios add it to homescreen](https://mobilesyrup.com/2020/05/24/how-install-progressive-web-app-pwa-android-ios-pc-mac/#:~:text=Navigate%20to%20the%20website%20you,like%20a%20native%20iOS%20app.)) 

4. Dê um nome para a Sala e entre com a URL do seu feed ICS e pressione continuar, as informações da agenda deverão ser mostradas.

    - Se você tiver problemas com CORS, adicione uma extensão https://chromewebstore.google.com/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino   , ou configure o seu WebServer para ignorar CORS.

6. Você pode fazer o append do nome da sala diretamenta na URL de chamada  ?name=YourName&icsurl=YourICSURL. 




