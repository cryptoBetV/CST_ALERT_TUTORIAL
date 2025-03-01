# CST_ALERT_TUTORIAL
How to CST ALERT Application by end-user


# Wprowadzenie
• Użyj swojego unikalnego adresu

• W razie kłopotów wprowadź port na końcu adresu ```:80```


# ALERT

> Alert to typ powiadomienia który osadzony jest w wiadomości embed discord posiada ticker, cene, interwał oraz komentarz tradera.


![Alt text of the image](https://media.discordapp.net/attachments/1069425610373472287/1345493042898927749/image.png?ex=67c4bf8b&is=67c36e0b&hm=f4f6a50cc18ec9f548806a91b1221c0b1ff8fc41a4e3cc1e8a3b5ad00aae93fd&=&format=webp&quality=lossless&width=349&height=160)


1. Utwórz swój TradingView Alert, przejdź do ustawień. [Zdjęcie pomocnicze](https://media.discordapp.net/attachments/1069425610373472287/1345487712920014973/418302305-269f2a9b-3ea5-40a9-be2e-6dc377163008.png?ex=67c4ba94&is=67c36914&hm=f8905a1ada6090d3005006045610fbe17c2ee808d7eef7d63841cd5821ff7082&=&format=webp&quality=lossless&width=553&height=733)
2. W zakładce Powiadomienia/Notifications zaznacz "Webhook URL".
3. Wprowadź adres który otrzymałeś i dopisz na koniec adresu "/alert".
4. Przejdź do Ustawienia/Settings. 
5. Ustaw parametry i trigger swojego alertu.
6. Wprowadź do swojej wiadomości👇 (uwaga, ### ### to separator i musi znajdować się poza innymi separatorami)
   
    ```###||{{ticker}}||<<{{interval}}>>[[{{close}}]]###```
    
   • Wiadomość musi zostać spreparowana według wskazówek odnośnie separatorów.
   
   • Wiadomość nie może zawierać znaków specjalnych ``` ~ < > [ ] { } | ```

8. Przesuń linię niżej i wprowadż ```~~~``` na początku i końcu swojego komentarza jak na załączonym zdjęciu. [Zdjęcie pomocnicze](https://media.discordapp.net/attachments/1069425610373472287/1345487690149138584/418302422-abfa4351-f86f-447f-95a0-c37a18e2bae7.png?ex=67c4ba8f&is=67c3690f&hm=ed6ebe028b181a07a05336f5a4e3c229efea8732798ba5d65f47c49791703e86&=&format=webp&quality=lossless&width=510&height=810)
9. Zapisz alert.

⚠️ Tekst wprowadzony poza separatorem ~~~ ... ~~~ będzie ignorowany.



# POST

> Post to typ powiadomienia który osadzony jest w wiadomości embed discord posiada komentarz tradera.

![image](https://media.discordapp.net/attachments/1069425610373472287/1345497642511237202/image.png?ex=67c4c3d4&is=67c37254&hm=9391470ceddb1a3e3e37cac5a0dd80036c60c2b33168b59af8144f59439afa92&=&format=webp&quality=lossless&width=618&height=184)


1. Utwórz swój TradingView Alert, przejdź do ustawień.
2. Przejdź do Ustawienia/Settings. 
3. Wprowadź swoją wiadomość  [Zdjęcie pomocnicze](https://media.discordapp.net/attachments/1069425610373472287/1345494858806329427/image.png?ex=67c4c13c&is=67c36fbc&hm=7011eea6dd50db9f6ad3a991987125ae6fae7b3a9e9317ea849b2b1b63025a04&=&format=webp&quality=lossless&width=511&height=810)
   
   ℹ️ Możesz wykorzystać formatowanie tekstu discord, zestaw poniżej:
   ``` > tekst ``` ">" + spacja a po tym tekst pozwoli stworzyć cytat [Jak wygląda cytat](https://media.discordapp.net/attachments/1069425610373472287/1345496911775404112/image.png?ex=67c4c325&is=67c371a5&hm=ae557cae2802ab33fd5157a85efef1527abbca9604e0a827b46f330ef22f926d&=&format=webp&quality=lossless&width=463&height=80)

   ℹ️ Możesz wykorzystać pogrubienie ``` ** tekst ** ```
   
4. W zakładce Powiadomienia/Notifications zaznacz "Webhook URL".
5. Wprowadź adres który otrzymałeś i dopisz na koniec adresu "/post". [Zdjęcie pomocnicze](https://media.discordapp.net/attachments/1069425610373472287/1345495527394906113/image.png?ex=67c4c1db&is=67c3705b&hm=d201baabe7d1ed31ed1cbe95f6b45e902faa7a49e05c0288474ea567ea4837bd&=&format=webp&quality=lossless&width=511&height=715)
6. Zapisz alert.
