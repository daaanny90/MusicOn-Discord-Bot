# :video_game: MusicOn Discord Bot (Italian Version) :headphones:

Un semplice bot che vi permetterà di gestire canzoni e playlist di Youtube in un canale audio Discord (e che parla italiano :pizza:).

## Installazione :heavy_check_mark:

1. Procuratevi prima di tutto il token per utilizzare l'app su Discord e una chiave API di Google.
2. Modificate il file `auth.js` con i vostri dati
3. Da un terminale date:

```
git clone https://github.com/daaanny90/MusicOn-Discord-Bot.git
cd MusicOn-Discord-Bot
npm install
node bot.js
```

Una volta online e seguito le guide sopra, dovreste vedere il vostro bot online nel vostro canale.

## Input :heavy_exclamation_mark:

Ecco un elenco di cosa può fare per il momento MusicOn:
- **!play**: Scrivendolo da solo, vi darà i primi dieci risultati della ricerca globale su YouTube
- **!play _termine di ricerca_**: Vi darà i primi dieci risultati della ricerca per la parola chiave che avete dato. Dopodichè indicherete con un numero quale brano riprodurre
- **!play _link_**: Ovviamente funziona anche dandogli direttamente un link, che sia di un brano o di una Playlist
- **!volume**: Vi dirà a quale grado da 1 a 10 è impostato attualmente il volume
- **!volume _0-10_**: Imposterà il volume al livello desiderato (numero da o a 10)
- **!skip**: Passa alla canzone successiva della Playlist
- **!stop**: Ferma la riproduzione
- **!pause**: Mette in pausa la riproduzione
- **!resume**: Riprende la riproduzione se messa in pausa precedentemente

## TO-DO :heavy_plus_sign:
- [ ] Permettere il loop infinito delle playlist
- [ ] Gestione brani Spotify
- [ ] Gestione brani Soundcloud
