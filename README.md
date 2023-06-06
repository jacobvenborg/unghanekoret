# Unghanekorets sangsamling
Til udvikling af Unghanekorets sangsamlingsapp, som findes på https://sangapp.unghanekoret.dk!

Planen er, at instruktioner for, hvorledes man kan hjælpe med her på GitHub, kommer til at fremgå af denne readme. Indtil videre er dog lidt instruktioner i [markdown](https://www.markdownguide.org/)-formatet, som er det, alle sange er skrevet i.

# Hjælp til markdown-format

## Til søg og erstat (regex)

For at finde f.eks. "1\\. " og bruge regex:
```
([0-9]\\\.)( )
```
Erstat med
```
$1\\\n
```
Der kan desuden findes enormt meget hjælp på https://regex101.com/


## Tekst-effekter
| Markdown-kode | Effekt |
| :- | :- |
| `*Kursiv tekst*` | *Kursiv tekst* |
| `**Fed tekst**` | **Fed tekst** |
| `***Fed og kursiv tekst***` | ***Fed og kursiv tekst*** |
| `~~Gennemstreget tekst~~` | ~~Gennemstreget tekst~~ |
| `` `Kodelinje` `` | `Kodelinje` (vs. normal tekst) |

**Kodeblok**
````
```
Brug 3 backticks på linjen over og under din tekst for kodeblok.
```
````
```
Brug 3 backticks på linjen over og under din tekst for kodeblok.
```
**Citation**
```
> Brug ">" for at lave citater.
```
> Brug ">" for at lave citater.

## Overskrifter
Brug "#" efterfulgt af mellemrum i starten af linjen for at angive, at linjen er en overskrift. Antal #'er angiver overskriftens størrelse. Afslut overskrift med linjeskift.

| Markdown-kode | Effekt |
| :- | :- |
| `# Overskrift 1`| <h1>Overskrift 1</h1> |
| `## Overskrift 2`| <h2>Overskrift 2</h2>  |
| `### Overskrift 3`| <h3>Overskrift 3</h3>  |
| `####  Overskrift 4`| <h4>Overskrift 4</h4>  |
| `#####  Overskrift 5`| <h5>Overskrift 5</h5>  |
| `######  Overskrift 6`| <h6>Overskrift 6</h6>  |

## Lister og punkter
| Markdown-kode | Effekt |
| :- | :- |
| `1. Nummeret listepunkt 1`<br>`2. Nummeret listepunkt 2`| <ol><li>Nummeret listepunkt 1</li><li>Nummeret listepunkt 2</li></ol> |
| `- Vilkårlig liste 1`<br>`- Vilkårlig liste 2`| <ul><li>Vilkårlig listepunkt 1</li><li>Vilkårlig listepunkt 2</li></ul> |
