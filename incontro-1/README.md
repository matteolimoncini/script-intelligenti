# Incontro 1 · Dalle regole agli esempi

**Script intelligenti: sviluppare modelli di Machine Learning con il codice** · martedì 27 ottobre 2026

Il kit dell'incontro: tre attività da rifare in classe, ognuna con i materiali per gli studenti e una guida per il
docente. Tempi indicativi in classe: da 30 a 60 minuti per attività.

## 1 · Siete botanici (senza computer)

Gli studenti ricavano a mano delle regole per riconoscere tre specie di iris dalle misure dei fiori, poi le mettono
alla prova su quattro fiori misteriosi. È quello che fa un modello di Machine Learning, fatto a mano.

| File | A che cosa serve |
|---|---|
| [siete_botanici_scheda.pdf](schede/siete_botanici_scheda.pdf) | La scheda da stampare, una per coppia |
| [siete_botanici_guida_docente.pdf](schede/siete_botanici_guida_docente.pdf) | Soluzione, domande per il confronto, varianti per le materie |

## 2 · Teachable Machine (no-code, nel browser)

Si addestra un classificatore di immagini su mele, banane e arance, poi lo si addestra di nuovo con dati rovinati
apposta: pochi esempi, sfondo truccato, classi sbilanciate. Niente webcam e niente account.

| File | A che cosa serve |
|---|---|
| [immagini_frutta.zip](teachable_machine/immagini_frutta.zip) | Le 372 foto, divise nelle cartelle dei tre esperimenti più la cartella `prova` (6 MB) |
| [teachable_machine_consegne.pdf](schede/teachable_machine_consegne.pdf) | Le consegne da stampare, una per coppia |
| [teachable_machine_guida_docente.pdf](schede/teachable_machine_guida_docente.pdf) | Tempi, che cosa aspettarsi, intoppi frequenti, varianti, privacy |

Lo strumento: [teachablemachine.withgoogle.com](https://teachablemachine.withgoogle.com) → Inizia → Progetto di
immagini → Modello di immagine standard.

## 3 · Esploriamo Iris con Gemini (vibecoding in Colab)

Il codice lo scrive Gemini, l'assistente di Google Colab: noi chiediamo bene e controlliamo il risultato. Due tappe:
caricare ed esplorare i dati, poi un grafico e una domanda.

| File | A che cosa serve |
|---|---|
| [iris_guida.ipynb](notebook/iris_guida.ipynb) · [**apri in Colab**](https://colab.research.google.com/github/matteolimoncini/script-intelligenti/blob/main/incontro-1/notebook/iris_guida.ipynb) | Il notebook da completare: consegne, prompt di esempio, celle vuote |
| [iris_soluzione.ipynb](notebook/iris_soluzione.ipynb) · [**apri in Colab**](https://colab.research.google.com/github/matteolimoncini/script-intelligenti/blob/main/incontro-1/notebook/iris_soluzione.ipynb) | La soluzione già eseguita, con i risultati e gli intoppi possibili |
| [iris.csv](dati/iris.csv) | I 150 fiori del dataset Iris, nella versione UCI (colonne in inglese) |

Aperto in Colab, il notebook va salvato con *File → Salva una copia in Drive*: senza la copia le modifiche non si
salvano. Il file `iris.csv` lo scarica il notebook stesso da questa cartella, quindi non serve caricarlo.

## Crediti

- **Dataset Iris:** misure raccolte da Edgar Anderson e pubblicate da Ronald Fisher (1936).
- **Foto delle iris:** Wikimedia Commons (Radomil, CC BY-SA 3.0; Danielle Langlois, CC BY-SA 3.0; Frank Mayfield,
  CC BY-SA 2.0).
- **Foto dei frutti:** dataset [Fruits-360](https://github.com/fruits-360) di Mihai Oltean (CC BY-SA 4.0), ritagliate
  e composte su sfondi generati al computer. Le immagini della cartella sono distribuite con la stessa licenza
  CC BY-SA 4.0; i crediti completi sono nel file `LEGGIMI.txt` dentro lo zip.
