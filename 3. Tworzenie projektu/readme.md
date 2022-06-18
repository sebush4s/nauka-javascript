# 3. Tworzenie projektu
___
Tworzenie nowego projektu rozpoczynamy od polecenia:
```bash
npm init
```
Aby pominąć wpisywanie danych projektu, możesz użyć flagi `-y`
```bash
npm init -y
```

Po wykonaniu polecenia powinieneś ujrzeć plik `package.json`. Jeśli użyłeś flagi `-y`, powinien on wyglądać tak:
```json
{
  "name": "nazwa-projektu",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "homepage": ""
}

```

W następnej kolejności stwórz plik `index.js` w tym samym folderze. Otwórz plik i wklej tam poniższy kod:
```js
console.log('Hello World')
```

W konsoli nakierowanej na katalog z twoim projektem wykonaj polecenie:
```bash
node .
```

Twoim oczom powinien ukazać się tekst `Hello World`!
