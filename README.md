# VisionBot

============ 25.02.2021 ChangeLog ============

Am adaugat:
Error messages la comenzile de moderatie ca atunci cand nu merge o comanda o sa va zica daca aveti permisiuni sa o executati sau nu.


servername: Poate fii folosita doar de cei care au rol cu Administrator Perms.
kick: Poate fii folosita doar de cei care au rol cu permisiunea de Kick Members.
ban: Poate fii folosita doar de cei care au rol cu permisiunea de Ban Members.
unban: Poate fii folosita doar de cei care au rol cu permisiunea de Ban Members.
banlist: Poate fii folosita doar de cei care cu rol cu permisiunea de Administrator deoarece poate flooda canalele.
purge: Poate fii folosita doar de cei care au rol cu permisiunea de Kick Members.
mute: Poate fii folosita doar de cei care au permisiunea de Kick Members.
unmute: Poate fii folosita doar de cei care au permisiunea de Kick Members.
warn: Poate fii folosita doar de cei care au permisiunea de Kick Members.
logs: Poate fii folosita doar de cei care au permisiunea de Kick Members.
dm: Poate fii folosita doar de cei care au permisiuni de Administrator.
lockdown: Poate fii folosita doar de cei care au permisiuni de Manage Channels.
unlock: Poate fii folosita doar de cei care au permisiuni de Manage Channels.
tempban: Poate fii folosita doar de cei care au permisiuni de Ban Members.

Syntaxa pentru comezi ca sa nu mai existe confuzii:


Kick:
Nu trebuie sa puneti paranteze

?servername "Nume" Ex: "?servername VisionRomania" acceasta comanda va schimba numele de la server in VisionRomania
?kick @Membru/UserID [Motiv] Ex: "?kick @Txvi Gay" sau "?kick 737976503228301373 Gay"
?ban @Membru/UserID [Motiv] Ex: "?ban @Txvi Gay" sau "?ban 737976503228301373 Gay" (Cu UserID puteti sa banati si persoane care nu sunt in server.)
?unban UserID Ex: "?unban 737976503228301373"
?banlist
?purge (Numar de mesage) Ex: "?purge 10"
?mute @Membru/UserID 1s/1m/1h/1d Ex: "?mute @Txvi 13m Gay" sau "?mute 737976503228301373 13m Gay" [Timpul trebuie sa fie exact cum am scris eu in litere mici daca vreti sa dati mute cuiva pentru 12 ore spre exemplu scrieti ?mute @Txvi 12h Gay]
?unmute @Membru/UserID Ex: "?unmute @Txvi" sau "?unmute 737976503228301373"
?warn @Membru/UserID reason Ex: "?warn @Txvi Muie" sau "?warn 781442615169908767 Muie"
?logs @Membru/UserID Ex: "?logs @Txvi" sau "?logs 781442615169908767"
?dm UserID [Mesaj] Ex: "?dm 781442615169908767 Muie"
?lockdown
?unlock
?tempban @Membru/UserID [Timp] [Reason] Ex: "?tempban @Txvi 60 Gay" sau "?tempban 737976503228301373 60 Gay". La TEMPBAN timpul este NUMAI in secunde. Adica cand dati tempban cuiva va trebuii sa puneti in secunde cat timp vreti sa ia accea persoana ban Ex: ?tempban @Txvi 3600 Gay. Aici banul este de o ora. Sau ?tempban @Txvi 604800 Gay. Aici banul este de o saptamana. 

!!!!Unde am scris gay/muie etc acolo este reasonul unde o sa puneti ceea ce vreti voi. Eu le-am folosit ca un exemplu.

============ Latest Update 01/03/2021 ============

Added ?guilds. A command for developer only that shows how many guilds the bot is in and the guilds ids.
Reworked the ?ping command so it is readable.
