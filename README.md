# Git, GitHub, Visual Studio Code, Markdown och HTML 

## Introduktion

Den här README.md visar vad jag har lärt mig om grundläggande kunskaper inom Git, GitHub, Visual Studio Code, Markdown och HTML. Exemplen riktar sig till nya studenter.

## 1. Git

Git är ett versionshanteringssystem som används för att hantera ändringar och versioner i ett projekt.

### Git-kommandon

```bash
git status
git add .
git commit --message "Ändrade"
git push origin main
```

- `git status` visar projektets aktuella ändringar.
- `git add .` lägger till ändringar inför nästa commit.
- `git commit` sparar ändringar lokalt som en version.
- `git push` skickar commits till GitHub.

## 2. GitHub

GitHub är en onlineplattform för att lagra och dela repositories.

### Skapa och koppla repository

1. Skapa ett repository på GitHub.
2. Aktivera README.md.
3. Kopiera repository-URL.

```bash
git clone <repository-url>
```

`git clone` kopierar repository från GitHub till datorn och skapar en lokal kopia med en koppling till fjärrrepositoryt.

Git hanterar versioner lokalt och GitHub lagrar repository online.

## 3. Visual Studio Code

Visual Studio Code (VS Code) är en kodredigerare för att skapa och redigera filer.

### Funktioner

* Öppna ett repository.
* Skapa och redigera `index.html`.
* Skriva HTML-kod.
* Skriva Markdown i `README.md`.
* Spara filer med `Cmd + S`.
* Använda Terminal för Git-kommandon.

## 4. Markdown

Markdown används för att formatera text med rubriker, listor, länkar och fet text, till exempel i README.md.

### Exempel

```markdown
# Rubrik
## Underrubrik

**Fet text**

*Italic text*

- Första punkten
- Andra punkten
```


## 5. HTML

HTML (HyperText Markup Language) används för att strukturera innehåll på webbsidor.

### HTML-element

| Element | Funktion |
|---|---|
| `<h1>` | Huvudrubrik |
| `<h2>` | Underrubrik |
| `<title>`|Sidtitel |
| `<p>` | Textstycke |
| `<a>` | Länk |
| `<img>` | Bild |
| `<div>` | Container |
| `<ol>`  |Ordnad lista  |
| `<ul>` | Oordnad lista |
| `<li>` | Listpunkt |
| `<button>` | Knapp |

### Exempel

```html
<!DOCTYPE html>
<html lang="sv">
<head>
    <title>Min webbsida</title>
</head>
<body>
    <h1>Min första rubrik</h1>
    <p>Det här är min första text.</p>
    <button>Klicka här</button>
</body>
</html>
```

HTML-element används för att strukturera rubriker, text och andra innehåll på en webbsida.

## Sammanfattning

Git används för versionshantering, GitHub för online-lagring och Visual Studio Code för kodredigering. Markdown används för textformatering och HTML för att strukturera webbsidor.