<img src="https://img.shields.io/badge/Versione-1.0-green"> <img src="https://img.shields.io/badge/Aggiornato-si-orange"> <a href="https://forum.hassiohelp.eu/d/503-package-cronotermostato"><img src="https://img.shields.io/badge/Forum-hassiohelp-blue"></a> <a href="https://www.buymeacoffee.com/mariocandida80"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" width="90" alt="Buy Me A Coffee"></a>
<br>

Se vi piace il mio lavoro, potete supportarmi su <a href="https://www.paypal.com/paypalme/mariocandida">Paypal</a> oppure <a href="https://www.buymeacoffee.com/mariocandida80">offrimi un caffè</a>.<br>
<p align="center"/> <b>Addon Telegram per cronotermostato</b> <br> </p>

Questo package ha una serie di automazioni che permettono di comandare il totalmente<a href="https://github.com/mariocandida80/cronotermostato/blob/master/README.md"> cronotermostato</a> tramite telegram. <br>
<p align="center"/><img src="https://github.com/mariocandida80/addon_telegram/blob/master/foto/pannello1.jpg" width="390"></p>

Prerequisiti:<br>
Aver configurato il <a href="https://github.com/mariocandida80/addon_telegram/wiki">bot telegram</a><br>

Per installarlo basterà copiare il file addon_telegram.yaml nella cartella package e riavviare home assistant.<br>
Per chi ha il package no-climate, basterà aprire il file addon_telegram con un editor e sostituire tutti i climate.riscaldamento con il prorio.<br>

<p align="center"/> <b>Funzionamento</b> <br> </p>
Per avviare il pannello vi basterà aprire il vostro bot telegram e digitare /termostato.<br>
Vi apparirà il pannello di controllo principale con i seguenti bottoni:<br>
Stato: vi mostra lo stato attuale del termostato (modalità impostata, temperatura attuale e impostata,e orari di accensione e spegnimento della fascia 1)<br>
Manuale: Accende il termostato in modalità manuale mostrandovi un messaggio che indica la modalità e la temperatura attuale e quella impostata.<br>
Auto: Accende il termostato in modalità auto mostrandovi un messaggio che indica la modalità, la temperatura attuale e quella impostata e gli orari di accensione e spagnimento.<br>
Preriscaldamento: Accende il termostato in modalità preriscaldamento mostrandovi un messaggio che indica la modalità, la temperatura attuale e quella impostata e gli orari di accensione e spagnimento.<br>
Spento: Spegne il termostato mostrandovi un messaggio che indica la modalità e la temperatura attuale e quella impostata.<br>
Eco: Accende il termostato in modalità eco mostrandovi un messaggio che indica la modalità e la temperatura attuale e quella impostata.<br>
Imposta temperatura: mostra la temperatura attualmente impostata e vi da la possibilità di scegliere la temperatura da impostare da 18 a 24 con step di mezzo grado.<br>
Imposta orari: mostra un sottomenù con 2 scelte: Orario accensione e Orario spegnimento; cliccando sul primo vi mostrerà l'orario di accensione impostato attualmente e vi darà una serie di pulsanti per scegliere il nuovo orario di accensione con step di 30 minuti; cliccando invece su orario spegnimento vi mostrerà l'orario di spegnimento impostato attualmente e vi darà una serie di pulsanti per scegliere il nuovo orario di spegnimento con step di 30 minuti.<br>
<p align="center"/><img src="https://github.com/mariocandida80/addon_telegram/blob/master/foto/pannello2.jpg" width="390">  </p>
