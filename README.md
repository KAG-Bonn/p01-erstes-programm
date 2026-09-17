# p01 – Erstes Programm

Aufgabenpaket 1 der Reihe *Objektorientierte Modellierung und Programmierung in Java*
(Leitkontext Organspenderegister).

## Inhalt

| Datei | Wozu |
|---|---|
| `HalloRegister.java` | fertiges Beispielprogramm – vorhersagen, ausführen, verändern (Arbeitsblatt Stunde 5, Aufgaben 1–3) |
| `Registerbegruessung.java` | legt ihr **selbst** an (Aufgabe 4) |

## Programm ausführen

**In VS Code:** Datei öffnen und oben rechts auf ▷ *Run Java* klicken.

**Im Terminal:**

```
javac HalloRegister.java
java HalloRegister
```

`javac` übersetzt den Quelltext in die Datei `HalloRegister.class`,
`java` führt sie aus.

## Arbeiten mit Git (ab Stunde 6)

- Branch: `sNN/p01-erstes-programm` (`sNN` = dein Kurskürzel)
- `main` gehört der Lehrkraft – nie direkt darauf pushen.
- Stundenende = `git add .` · `git commit -m "..."` · `git push`
- Abgabe: Pull Request gegen `main` öffnen, **nicht** mergen.

## Kein JDK auf dem Rechner?

Repository auf GitHub öffnen → *Code* → *Codespaces* → *Create codespace*.
Java ist dort schon eingerichtet. **Nicht** `github.dev` verwenden (die Taste `.`) –
dort lässt sich Java nicht ausführen.
