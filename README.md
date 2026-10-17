# Tra le sedute · Quaderno personale

Una piccola web app per i giorni tra un incontro e l'altro con la propria psicoterapeuta o il proprio psicoterapeuta, con focus su:
- diario delle emozioni
- ruota delle emozioni
- termometro dell'umore
- registro dei pensieri a 7 colonne, con le trappole del pensiero
- attività con piacere e padronanza (attivazione comportamentale)
- diario dei sogni (psicodinamico e junghiano)
- relazioni (sistemico-relazionale)
- appunti con allegati, materiale per la seduta da condividere (per esempio su WhatsApp), compiti e note di fine seduta
- archivio completo da scaricare e reimportare
- haiku sul tema della cura, dell'ascolto e delle emozioni
- scelta degli strumenti, con profili per i diversi orientamenti

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
Per problemi di salute non urgenti, anche di notte e nei festivi, c'è il **116117**: gratuito, 24 ore su 24, collega con la guardia medica e nel Lazio offre anche un primo supporto psicologico (non ancora attivo in tutte le regioni).
Per parlare con qualcuno, Telefono Amico Italia risponde al **02 2327 2327**.

Più dettagli in [LEGAL.md](LEGAL.md).

## 🔒 Privacy

Tutto ciò che si scrive resta solo nel browser e sul dispositivo di chi usa l'app (`localStorage`):
- nessun account
- nessun server
- nessun invio di dati

Se si cancellano i dati del browser o si usa una finestra privata, le voci vanno perse. Per conservarle si usa «Copia tutte le voci» nella scheda «Strumenti».

Gli allegati (foto, documenti, HTML, ZIP…) stanno in un archivio separato dello stesso browser (`IndexedDB`), più capiente. Solo toccando «Condividi» un appunto, un file o un link passa all'app scelta. «Scarica l'archivio» crea un unico file con note, impostazioni e allegati, da reimportare con «Importa un archivio».

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
- **Ruota** delle emozioni: sette famiglie (gioia, tristezza, paura, rabbia, sorpresa, disgusto, vergogna) con le loro sfumature; la parola scelta passa al diario
- **Umore**: umore, energia e sonno giorno per giorno, con grafico degli ultimi 30 giorni
- **Pensieri**: registro a 7 colonne (situazione, pensiero automatico, emozione e comportamento, prove a favore, prove contro, pensiero alternativo, quanto ci si crede prima e dopo), con 11 trappole del pensiero da segnare e il grafico di quelle più frequenti
- **Attività**: attività fatte o da fare, per giorno e momento, con voti di piacere e padronanza da 0 a 10; riepilogo degli ultimi 7 giorni e attività che hanno fatto stare meglio
- **Sogni**: diario dei sogni con titolo, racconto, emozioni nel sogno e al risveglio, associazioni, legami con la vita di questi giorni, sogni ricorrenti
- **Relazioni**: momenti con le persone (con chi, cosa è successo, cosa ho provato, cosa ho fatto, cosa avrei voluto, cosa mi ricorda), nomi già usati a portata di tocco, persone che compaiono più spesso
- **Seduta**: data del prossimo incontro con conto alla rovescia, appunti da portare, importanti in evidenza, con foto, file e link allegati a ogni appunto; «Materiale per la seduta» con anteprima delle immagini, «Scarica» e «Condividi» (pannello di condivisione del telefono: WhatsApp, posta, Drive…; i tipi non condivisibili dal browser, come ZIP, si scaricano e si allegano a mano); compiti tra le sedute con «Segna fatto oggi», la settimana da lunedì a domenica (anche le precedenti) e le difficoltà; «Dopo la seduta» per annotare cosa ci si porta via, cosa si è provato e cosa non si è detto, che può finire direttamente negli appunti; copia di appunti e compiti
- **Haiku**: 68 haiku originali in undici temi, «Pesca un haiku»; in cima a ogni pagina compare un haiku casuale sul tema della pagina
- **Informazioni e note legali**: link in alto a destra (o indirizzo `#informazioni`) che apre una finestra con descrizione, note legali e licenza
- **Strumenti**: profili di partenza (tutti, cognitivo-comportamentale, psicodinamico, sistemico-relazionale, umanistico) e interruttori per ogni scheda o sezione; spegnere una scheda la nasconde senza cancellare nulla. Sotto: privacy, consigli d'uso, numeri utili, copia di tutte le voci, archivio completo (scarica e importa), cancellazione
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
2. In «Strumenti», scegliere il profilo più vicino al proprio percorso e le schede da tenere
3. Scegliere una sezione dalle schede in alto
4. Scrivere quello che si vuole, quando si vuole: anche una riga conta
5. Prima della seduta, aprire «Seduta» e copiare gli appunti, se utile
6. Ogni tanto copiare tutte le voci altrove, per non perderle

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
Versione 1.4 · 17/10/2026 - Questo file va aggiornato periodicamente con data e note eventuali.
