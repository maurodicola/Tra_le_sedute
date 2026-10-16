# Tra le sedute · Quaderno personale

Una piccola web app per i giorni tra un incontro e l'altro con la propria psicoterapeuta o il proprio psicoterapeuta, con focus su:
- diario delle emozioni
- ruota delle emozioni
- termometro dell'umore
- registro dei pensieri a 7 colonne, con le trappole del pensiero
- attività con piacere e padronanza (attivazione comportamentale)
- appunti e compiti tra le sedute
- haiku sul tema della cura, dell'ascolto e delle emozioni

È pensata come dono di gratitudine per chi ascolta, e come strumento personale per chi è in un percorso di cura.

## ⚠️ Avvertenza sanitaria e legale

Questo repository contiene un quaderno digitale per uso personale. Non è un dispositivo medico, non fa diagnosi, non propone terapie e non sostituisce in alcun modo il lavoro con un professionista.

### Uso previsto
- Annotare emozioni, umore e pensieri tra una seduta e l'altra
- Preparare gli argomenti da portare in seduta
- Leggere e condividere haiku

### Cosa non è
- Non è uno strumento di valutazione clinica
- Non è un servizio di emergenza
- Non invia nulla alla terapeuta o a chiunque altro
- Gli strumenti più specifici, come il registro dei pensieri, vanno usati solo se il professionista li ritiene adatti al proprio percorso

### Se stai male adesso
Se senti di essere in pericolo o hai bisogno di aiuto subito, chiama il **112**.
Per parlare con qualcuno, Telefono Amico Italia risponde al **02 2327 2327**.

Più dettagli in [LEGAL.md](LEGAL.md).

## 🔒 Privacy

Tutto ciò che si scrive resta solo nel browser e sul dispositivo di chi usa l'app (`localStorage`):
- nessun account
- nessun server
- nessun invio di dati

Se si cancellano i dati del browser o si usa una finestra privata, le voci vanno perse. Per conservarle si usa «Copia tutte le voci» nella sezione «Come funziona».

L'unica risorsa esterna sono i caratteri tipografici di Google Fonts. Senza connessione la pagina funziona lo stesso, con i caratteri di sistema.

## ✅ Obiettivo del progetto

L'obiettivo è semplice:
- dare un posto alle cose che succedono tra una seduta e l'altra
- aiutare a dare un nome preciso a ciò che si prova
- arrivare in seduta ricordando ciò che si voleva dire
- accompagnare ogni pagina con un haiku

## 🧩 Funzioni principali

- **Oggi**: segno rapido dell'umore, riepilogo della settimana, scorciatoie
- **Diario delle emozioni**: quando, emozione, intensità 0–10, situazione, pensiero, azione, bisogno; vista settimanale a colori
- **Ruota delle emozioni**: sette famiglie (gioia, tristezza, paura, rabbia, sorpresa, disgusto, vergogna) con le loro sfumature; la parola scelta passa al diario
- **Umore**: umore, energia e sonno giorno per giorno, con grafico degli ultimi 30 giorni
- **Pensieri**: registro a 7 colonne (situazione, pensiero automatico, emozione e comportamento, prove a favore, prove contro, pensiero alternativo, quanto ci si crede prima e dopo), con 11 trappole del pensiero da segnare e il grafico di quelle più frequenti
- **Attività**: attività fatte o da fare, per giorno e momento, con voti di piacere e padronanza da 0 a 10; riepilogo degli ultimi 7 giorni e attività che hanno fatto stare meglio
- **Per la seduta**: data del prossimo incontro con conto alla rovescia, appunti da portare, importanti in evidenza; compiti tra le sedute con i giorni in cui sono stati fatti e le difficoltà; copia di appunti e compiti
- **Haiku**: 58 haiku originali in nove temi, «Pesca un haiku»; in cima a ogni pagina compare un haiku casuale sul tema della pagina
- **Informazioni e note legali**: link in alto a destra (o indirizzo `#informazioni`) che apre una finestra con descrizione, note legali e licenza
- **Come funziona**: privacy, consigli d'uso, numeri utili, copia di tutte le voci, cancellazione
- tema chiaro e scuro automatico
- tendine e calendari uniformi, pensati per il telefono
- al primo avvio, voci di esempio segnate come tali che spariscono alla prima voce vera

## 📦 Requisiti

Questo progetto è in HTML, CSS e JavaScript puro.

Per usarlo:
- un browser moderno
- nessuna dipendenza da installare
- nessun backend richiesto

## 🛠️ Struttura del progetto

```text
/
├── .gitignore
├── LEGAL.md
├── LICENSE
├── LICENZA.md
├── README.md
└── index.html
```

## ▶️ Come usare

1. Aprire `index.html` nel browser, oppure la pagina pubblicata
2. Scegliere una sezione dalle schede in alto
3. Scrivere quello che si vuole, quando si vuole: anche una riga conta
4. Prima della seduta, aprire «Per la seduta» e copiare gli appunti, se utile
5. Ogni tanto copiare tutte le voci altrove, per non perderle

## 📄 Licenza

Il codice è distribuito con licenza MIT, salvo diversa indicazione.

Per maggior chiarezza:
- puoi usare, modificare e redistribuire il codice
- devi mantenere la nota di copyright
- gli haiku sono opere dell'autore e accompagnano il progetto: se li riusi, cita «AI Haiku Gaea»

Vedi [LICENSE](LICENSE) e la spiegazione in italiano in [LICENZA.md](LICENZA.md).

## 🧾 Nota finale

Questo repository è nato come regalo di gratitudine verso una professionista della cura. Non è un prodotto commerciale e non è promosso come strumento clinico.

Se decidi di usarlo con dei pazienti:
- valuta tu, come professionista, se e quali sezioni proporre
- ricorda alle persone che i dati restano sul loro dispositivo
- non usarlo come canale di comunicazione o di emergenza

## Autore
Mauro Di Cola · Haiku di AI Haiku Gaea

## Ultimo aggiornamento
Versione 1.2 · 16/10/2026 - Questo file va aggiornato periodicamente con data e note eventuali.
