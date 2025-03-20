# Template för PROG2 Inlupp 1 och 2

## Bygg och testa Inlupp 1 och kör Inlupp 2

```bash
mvn package
```

För att testa JavaFX innan Inlupp 1 är klar:

```bash
mvn package -Dmaven.test.skip
```

## Bygg och testa enbart Inlupp 1

```bash
mvn compile test -pl backend
```

## Importera i din editor

### Intellij IDEA

Välj File -> New -> Project From Version Control och skriv in https://-url:n
till det här repot.

![Intellij Idea import](assets/idea.png)

Det finns tre bygg/kör alternativ. Klicka på dem för att köra projektet.

### Visual Studio Code

Klicka på Clone Repository och fyll i https://-url:n till det här repot.

![Visual Studio Code import](assets/vscode.png)

Kör genom att klicka på Terminal -> Run Build Task...

Testa Inlupp 1 genom att klicka på test under Maven -> backend.
