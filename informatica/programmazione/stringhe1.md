# Strings Training 1

## Credits

Questo esercizo è preso e adattato dalla piattaforma di [Soluzioni Futura](https://www.soluzionifutura.it/). L'esercizio originale si trova al seguente link https://challenge.soluzionifutura.it/allenamenti/stringhe-1

## Introduzione

Svolgere i seguenti esercizi con un linguaggio di programmazione a scelta. Gli esempi sono in linguaggio Javascript solo a supporto della spiegazione.

## Esercizi
1. **repeatString** : la funzione accetta una stringa str e un numero n come argomenti e restituisce la stringa ripetuta n volte.

Firma: `function repeatString(str: string, n: number)`

Esempio:

```javascript
repeatString("ciao", 3) // "ciaociaociao"
repeatString("abc", 2) // "abcabc"
repeatString("abc", 0) // ""
```


1. **uppercaseVowels** : la funzione accetta una stringa str come argomento e restituisce la stringa con le vocali in maiuscolo.

Firma: `function uppercaseVowels(str: string): string`

Esempio:

```javascript
uppercaseVowels('ciao mondo') // 'cIAO mOndO'
```


1. **removeChar** : la funzione accetta una stringa 'str' e un carattere char come argomenti e restituisce la stringa senza alcun'occorrenza di quel carattere.

Firma: `function removeChar(str: string, char: string)`

Esempio:

```javascript
removeChar("ciao", "i") // "cao"
removeChar("ciao", "a") // "cio"
removeChar("ciao", "x") // "ciao"
```


1. **reverseCharacter** : la funzione accetta una stringa str come argomento e restituisce con i caratteri minuscoli trasformati in maiusolo e viceversa.

Firma: `function reverseCharacter(str: string): string`

Esempio:

```javascript
reverseCharacter('CIAo mondo') // 'ciaO MONDO'
```


1. **replaceChars** : la funzione accetta una stringa str e 2 caratteri oldChar e newChar come argomenti e restituisce una nuova stringa in cui tutte le occorrenze di oldChar sono sostituite da newChar.

Firma: `function replaceChars(str: string, oldChar: string, newChar: string): string`

Esempio:

```javascript
replaceChars('Ciao mondo', 'o', 'O') // 'CiaO mOndO'
```


1. **reverseString** : la funzione accetta una stringa str come argomento e restituisce la stringa invertita.

Firma: `function reverseString(str: string): string`

Esempio:

```javascript
reverseString('Ciao mondo') // 'odnom oaiC'
```


1. **palindrome** : la funzione accetta una stringa str come argomento e restituisce true se la stringa è palindroma, false altrimenti. In questo caso lettere maiuscole e minuscole sono da considerarsi diverse.

Firma: `function palindrome(str: string): boolean`

Esempio:

```javascript
palindrome('Ciao mondo') // false
palindrome('oro') // true
```


1. **getLongestWord** : la funzione accetta una stringa str come argomento e restituisce la parola più lunga presente nella stringa.

Firma: `function getLongestWord(str: string): string`

Esempio:

```javascript
getLongestWord('Ciao mondo') // 'mondo'
```


1. **getMostFrequentChar** : la funzione che accetta una stringa str come argomento e restituisce il carattere più frequente presente nella stringa.

Firma: `function getMostFrequentChar(str: string): string`

Esempio:

```javascript
getMostFrequentChar('Ciao mondo') // 'o'
```


1. **removeRepetitions** : la funzione accetta una stringa str come argomento e restituisce una stringa contenente tutti i caratteri che appaiono in str non ripetuti. L'ordine dei caratteri non e' rilevante.

Firma: `function removeRepetitions(str: string)`

Esempio:

```javascript
removeRepetitions("ciao mondo") // "ciao mnd"
removeRepetitions("ramarro") // "ramo"
```


1. **wordCount** : la funzione accetta una stringa str come argomento e restituisce il numero di parole presenti nella stringa. Una parola e' un insieme non vuoto di caratteri separato da spazio dall'inizio o fine della stringa.

Firma: `function wordCount(str: string): number`

Esempio:

```javascript
wordCount('Ciao mondo') // 2
wordCount('') // 0
wordCount(' ciao mare ') // 2
```


1. **shorten** : la funzione accetta una stringa str argomento e la restituisce abbreviata se e' piu' lunga di 10 caratteri. L'abbreviazione e' composta dalla prima lettera, il numero di lettere tra la seconda e la penultima, e infine l'ultima lettera.

Firma: `function shorten(str: string)`

Esempio:

```javascript
shorten("localizzazione") // "l12e"
shorten("pneumonoultramicroscopicsilicovolcanoconiosi") // "p42i"
shorten("cane") // "cane"
```


1. **checkFileExtensionRegex** : la funzione restituisce una regex che permette di trovare l'estensione del nome di un file. L'estensione del nome un file comprende tutti i caratteri dopo l'ultimo punto ("."), punto escluso.

Firma: `function checkFileExtensionRegex(): RegExp`

```javascript
const regex = checkFileExtensionRegex() // new RegExp object
"ciaomare.pdf".match(regex)[0] // "pdf"
"ciao.mare.txt".match(regex)[0] // "txt"
```


1. **validateSimpleCodeRegex** : la funzione restituisce una regex che permette di validare un codice. I codici hanno formato "<esattamente 12 caratteri alfanumerici o underscore># <4 o 5 numeri>".

Firma: `function validateSimpleCodeRegex(): RegExp`

```javascript
const regex = validateSimpleCodeRegex() // new RegExp object
```

---

The provided text is now in Markdown format without HTML tags.
