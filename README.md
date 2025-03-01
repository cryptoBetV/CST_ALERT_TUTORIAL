# CST_ALERT_TUTORIAL
How to use CST ALERT Application by end-user


# Wprowadzenie


# ALERT
1. Utwórz swój TradingView Alert, przejdź do ustawień. [Zdjęcie pomocnicze](https://media.discordapp.net/attachments/1069425610373472287/1345487712920014973/418302305-269f2a9b-3ea5-40a9-be2e-6dc377163008.png?ex=67c4ba94&is=67c36914&hm=f8905a1ada6090d3005006045610fbe17c2ee808d7eef7d63841cd5821ff7082&=&format=webp&quality=lossless&width=553&height=733)
2. W zakładce Powiadomienia/Notifications zaznacz "Webhook URL".
3. Wprowadź adres który otrzymałeś i dopisz na koniec adresu "/alert".
   
4. Przejdź do Ustawienia/Settings. 
5. Ustaw parametry i trigger swojego alertu.
6. Wprowadź do swojej wiadomości. (uwaga, ### ### to separator i musi znajdować się poza innymi separatorami)
   
    ```###||{{ticker}}||<<{{interval}}>>[[{{close}}]]###```
    
8. Przesuń linię niżej i wprowadż ```~~~``` na początku i końcu swojego komentarza jak na załączonym zdjęciu. [Zdjęcie pomocnicze](https://media.discordapp.net/attachments/1069425610373472287/1345487690149138584/418302422-abfa4351-f86f-447f-95a0-c37a18e2bae7.png?ex=67c4ba8f&is=67c3690f&hm=ed6ebe028b181a07a05336f5a4e3c229efea8732798ba5d65f47c49791703e86&=&format=webp&quality=lossless&width=510&height=810)
9. Zapisz alert. [Jak wygląda alert?](https://media.discordapp.net/attachments/1069425610373472287/1345493042898927749/image.png?ex=67c4bf8b&is=67c36e0b&hm=f4f6a50cc18ec9f548806a91b1221c0b1ff8fc41a4e3cc1e8a3b5ad00aae93fd&=&format=webp&quality=lossless&width=349&height=160)

⚠️ Tekst wprowadzony poza separatorem ~~~ ... ~~~ będzie ignorowany.
