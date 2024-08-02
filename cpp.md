# CPP Tutorial

## Basi

- linguaggio compilato
- aggiunge al C il paradigma della programmazione ad oggetti
- potente
- diffuso


## Gestione del flusso

Il flusso può essere gestito utilizzando il costrutto if

```cpp
if (x==3) {
  std::cout << "OK" << std::endl;
} else {
  std::cout << "NO" << std::endl;
}
```

Nelle parentesi viene posta la condizione da verificare. Se la condizione
restituisce esito positivo allora viene eseguito il primo blocco di codice,
altrimenti viene eseguito il secondo blocco.

Il ramo ```else``` è opzionale.

Un blocco di codice è un insieme di codice racchiuso tra parentesi graffe.

Tra parentesi tonde è possibile inserire più condizioni. Le condizioni vanno 
unite con gli operatori logici E e O e possono essere raggruppate utilizzando
le parentesi.

```cpp
if (x>=0 && x<=10) {
  std::cout << "il numero è compreso tra 1 e 10" << std::endl;
}
```
## Cicli
