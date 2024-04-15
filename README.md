# MisureElettroniche
Repository dedicata all'esame di sistemi di Misure Elettroniche

# Ripetizione
## 2. Metrologia
- [x] Introduzione
- [x] Incertezza
- [x] Intersezione delle misure
- [x] valutazione incertezza A e B con probabilità
- [x] Introduzione incertezza composta
- [x] incertezza estesa
###  Lezione 3B-C-D incertezza
- [x] Dimostrazione incertezza composta taylor DA FARE
- [x] accuratezza e precisione
- [x] Ripetibilità vs riproducibilità
- [x] Regressione
- [x] Coefficiente di determinazione R<sup>2</sup>
- [x] Errore standard della stima
### ME-4-5
- [x] Cifre significative
- [x] Arrotondamenti
- [x] Riferibilità: quando delle misure sono compatibili
- [x] Introduzione **sistemi acquisizione dati**
## 5. Sistemi di acquisizione dati
### ME-5+6
- [x] Struttura di un mote
- [x] Livello di **trasduzione**
- [x] Classificare i trasduttori (tramite grafico 3D)
- [x] Principi di funzionamento dei sensori
- [x] **Sensori resistivi**
  - [x] Termistori: diversi materiali --> diverse 
## 6. Trasduttori di misura
### ME-6-Principio di funzionamento dei sensori
#### Trasduttori Resistivi
- [x] Termocoppie
- [x] Trasduttore di **portata massica** 
- [x] Effetto piroelettrico
- [x] Fotoresistivi
- [x] Trasduttori di deformazione ed estensimetri
- [x] Trasduttori di pressione (pressure gauge analogico - meccanico)
- [x] Trasduttore igrometro resistivo (sensore di umidità)
- [x] **Accelerometri resistivi** (visti alla fine della lezione, funzionano tramite molla e resistenza variabile)
#### Trasduttori Capacitivi
- [x]  Igrometro capacitivo (sensore umidità)
#### Trasduttori Induttivi LVDT
- [x] Trasduttore a variazione di riluttanza (basato su un trasformatore particolare)
- [x] **Accelerometri LVDT**
#### Trasduttori Magnetici
- [x] Trasduttori a correnti parassite (generazione di un campo magnetico indotto)
- [ ] Trasduttori magnetostrittivi e magnetoelastici (effetto hall)
#### Trasduttori Ottici
- [x] Trasduttori di posizione ottici (barra forata)
- [x] Encoder ottici (disco forato)
- [x] Introduzione gray code
#### Trasduttori a tempo di volo
- [x] Sonar (ultrasuoni)
---
- [x] MEMS - Micro Electro Mechanical Systems (sensori stampati)
- [ ] Rilevatori di Gas (biossido di stagno che varia la sua conducibilità elettrica)
## 7. Condizionamento dei segnali e ponti
### ME-7.1 circuiti di condizionamento e ponti in cc
- [x] Recap amplificatori operazionali
  - [x] OpAmp differenziali
  - [x] OpAmp come filtri
    - [x] LPF
    - [x] HPF
    - [x] BPF
#### Circuiti di condizionamento
- [x] Ponti in corrente continua: **Ponte di Wheatstone**
- [x] Dimostrazione resistenza (**DIM**)
- [x] Calcolo incertezza composta **DA FINIRE** (**DIM**)
- [x] Interpolazione lineare
### ME-7.2-Ponti in ca
- [x] **Ponte di Winston**
- [x] Equilibrio delle impedenze (**DIM**) - **equilibrio a croce**
- [ ] Ponte di Schering **<u>DA FARE</u>**
- [x] Capacità parassite
- [x] Il problema della messa a terra del circuito
## 8. Circuiti di Sample & Hold, Multiplexer e Switch
### ME-7.2-Sample & Hold
- [x] Sample & Hold: tra il blocco di condizionamento ed il convertitore
- [x] Problemi reali del S&H: periodo transitorio
  - [x] Sovraelongazioni
  - [x] Scarica del condensatore
- [x] Ottimizzazioni: carica veloce e scarica lenta
- [x] Configurazioni: in cascata e retroazione comune
### ME-8-Multiplexer E Switch

> Per "switch" si intendono gli interruttori MOS presenti nei multiplexer che selezionano gli ingressi.

- [x] Multiplexer
  - [x] Fonti di errore nei CMOS (capacità parassite)
- [ ] Digitalizzazione dei segnali

## 9. Digitalizzazione dei segnali

### ME 9.1 Digitalizzazione dei segnali

> Digitalizzazione -> Campionamento -> Quantizzazione -> Codifica

- [x] **Campionamento**
- [x] Teorema del campionamento
- [x] Aliasing
- [x] Filtro anti aliasing
- [ ] **Quantizzazione**

### ME 9.2 Digitalizzazione dei segnali P2

- [x] Risoluzione del quantizzatore
- [x] quantizzatore non silenziato vs silenziato
- [x] Codifica 
- [x] codificatore unipolare 
- [x] Codificatore bipolare e complemento a due
- [x] Problemi nel passaggio da analogico a digitale: le soglie non sono ben definite **DA FARE MEGLIO**
- [x] Risoluzione
- [x] Errori caratteristici
  - [x] Errore di offset
  - [x] Errore di guadagno
  - [x] Errori di DNL e INL
  - [x] Non monotonicità del convertitore
- [x] Parametri usati per valutare il convertitore
  - [x] Andamenti di THD
  - [x] SNR - Rapporto segnale rumore
    - [x] Valore efficace dell'errore di quanitzzazione
    - [x] SNR della sinusoide 
  - [x] SINAD - Signal to noise and distortion
  - [x] ENOB - Effective number of bit
  - [x] Errore in ampiezza: Jitter
  - [x] Settling time dei convertitori

### ME 9.3 Architetture DAC

- [x] DAC a resistori pesati con tensione di riferimento
- [x] Legame ingresso uscita **DA FARE**
- [x] Problemi del DAC a resistori pesati
- [x] DAC R-2R
  - [x] Dimostrazione con Thevenin
- [ ] Considerazioni
  - [x] Vantaggi
  - [x] Cause di incertezza
- [x] DAC moltiplicatore
- [x] Circuito di condizionamento LPF
- [x] Protezione in uscita con sample e hold
- [x] Potenziometro digitale

### ME 9.4 Architetture ADC

- [x] Comparatore
- [x] Convertitore a contatore
- [x] Frequenza di campionamento massima
- [x] Convertitore ad inseguimento - up/down converter
- [x] convertitore ad approssimazioni successive - SAR
- [x] Convertitori Flash
- [x] Encoder
- [x] Caratteristica silenziata
- [x] Convertitori a sovracampionamento

### ME 9.5 - ADC sigma delta

- [x] Noise shaping
- [x] Considerazioni degli ADC
- [x] Modulatore del secondo ordine
- [x] Modulatori per altissime frequenze
  - [x] Problemi
- [x] Diverse architetture viste

---

- [x] Errori comuni della prima esercitazione
- [x] info sulla seconda esercitazione: curve di regressione

## 10. Software di misura

### Smartphones and augmented reality for measurement applications

Visione della presentazione (di 10 anni fa) di come gli smartphones possono essere usati come strumenti di misura

## 11. Oscilloscopio digitale

### 11.1 A Sistemi acquisizione dati PT2

- [x] Acquisizione dati parte 2
- [x] a piu ingressi
- [x] ad ingresso singolo
- [x] Difetti
- [x] campionamento simultaneo
- [x] tempificazione dei componenti
- [x] **Schemi di architettura DAC**
  - [x] monocanale
  - [x] multicanale
  - [x] multicanale "a risparmio"

### 11.1B Oscilloscopio numerico P1

- [x] Oscilloscopio numerico
- [x] Cosa guardare quando si acquista un oscilloscopio
  - [x] Frequenza di campionamento
  - [x] profondità di memoria
  - [x] quanti segnali si possono osservare contemporaneamente (canali)
  - [x] refresh dello schermo e qualità
  - [x] **modalità di trigger**

### 11.2A Oscilloscopio numerico P2

- [x] Campionamento in tempo reale (classico)
- [x] Campionamento in tempi equivalenti
- [x] Campionamento casuale in tempo equivalente
- [x] Maschera
- [x] Elaborazioni del segnale
- [x] Display
- [x] Quantizzazione e campionamento

### 11.2B Elementi campione P1

- [ ] Sorgenti di tensione di riferimento: Diodo zener

## 13.  Elementi campione

### 13.1 Elementi campione P2

- [ ] Tensione campione (recap)
- [ ] Resistori campione
- [ ] Effetti induttivi e capacitivi del resistore e come correggerli
- [ ] Resistori variabili
- [ ] Resistori a 5 morsetti: Fluke 742A
- [ ] Modello reale di un resistore
- [ ] Condensatore campione
- [ ] Modello equivalente serie/parallelo
- [ ] Condensatore a 3 morsetti: con involucro
- [ ] Induttore campione

## 14. Strumentazione di misura

### 14.1 Caratteristiche metrologiche della strumentazione di misura

#### Caratteristiche generali

- [ ] Caratteristiche di ingresso
- [ ] Caratteristiche di uscita

#### Caratteristiche statiche

- [ ] Intervallo di lettura
- [ ] Portata
- [ ] Sensibilità
- [ ] Linearità
  - [ ] Riferita allo zero (minima distanza tra curva e retta, passa per l'estremo inferiore)
  - [ ] Riferita agli estremi (retta passante per gli estremi)
  - [ ] Indipendente (minima distanza tra curva e retta, passa per l'estremo inferiore)
  - [ ] Minimi quadrati (Minimo scostamento dai quadrati)
- [ ] **Risoluzione (minima variazione dell'input che produce uno scostamento dell'output)**
- [ ] **Precisione (Ampiezza entro la quale si ritiene sia presente il 95% del misurando) n.d.s si noti come questa definizione è concorde alla differenza tra precisione ed accuratezza.**
- [ ] **Isteresi** (massima differenza tra i valori ottenuti "a salire ed a scendere")

#### Caratteristiche dinamiche

Ottenute tramite la risposta in frequenza ed i diagrammi di Bode

- [ ] Sovraelongazione
- [ ] Tempo di salita (tempo necessario affinchè la risposta arrivi *per la prima volta* al 90%)
- [ ] Tempo di assestamento (tempo necessario affinchè la risposta arrivi *e non esca più* al 90%)

#### Caratteristice fisiche

- [ ] Dimensioni
- [ ] Peso
- [ ] Accessori

### 14.2 Strumenti magnetoelettrici

- [x] Strumenti magnetoelettrici
- [x] Voltmetro
- [x] Misure in salita ed in discesa
- [x] Classe dello strumento
- [x] Massimo errore
- [x] Incertezza tipo

### 14.3 Misure in corrente continua P1

## 16 Oscillatori e contatori

### 16 Oscillatori e contatori

- [x] Oscillatori - circuito risonante rlc
- [x] Risonatore al quarzo
- [x] Contatori numerici con flip-flop
- [x] Contatore a decadi
- [x] Contatore di frequenza
  - [x] Trigger
  - [x] Accoppiatore AC/DC
  - [x] GATE
  - [x] Incertezza di quantizzazione
- [x] Contatore di eventi
- [x] Frequenzimetro considerazioni
- [x] Periodimetro e quando usarlo

## 17. Multimetri

### 17 Multimetri numerici

- [x] Misura di tensione
  - [x] Voltage divider
  - [x] Cimatore
  - [x] Selettore AC/DC
    - [x] il blocco RMS/DC, come calcolare il valore efficace
    - [x] Circuiti base per l'RMS
    - [ ] Circuito True RMS
    - [ ] Circuito per True RMS termico
- [ ] Misura di corrente
  - [ ] Shunt
- [ ] Misura di resistenze
  - [ ] Misura a due morsetti
  - [ ] Misura a quattro morsetti

## 18. Terza esercitazione: LPF

### ME 18 Terza esercitazione

info sulla terza esercitazione

## 19. Sistemi automatici di misura

### ME 19 - Sistemi automatici di misura

- [x] intro
- [x] bottleneck
- [x] protocollo di comunicazione seriale
- [x] protocollo di comunicazione GPIB 7/ IEEE 488
- [x] Schede acquisizione dati
- [ ] Misure distribuite
- [ ] Sistemi strettamente accoppiati
- [ ] Sistemi debolmente accoppiati
- [ ] Software usati per controllare la strumentazione
  - [ ] Strumento virtuale

