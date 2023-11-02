# Übericht über HTML und CSS Befehle

1. [HTML](#html-elemente)
2. [CSS](#css-eigenschaften)

## HTML-Elemente

1. Block Elemente (nehmen gesamte Breite des Elternelements)

    | HTML-Element  | Beschreibung                               | Beispiel                             |
    |:-------------:|:------------------------------------------:|:------------------------------------:|
    | `<h1>`...`<h6>` | Überschriften                            | `<h1>Überschrift</h1>`               |
    | `<p>`          | Textabsatz                                | `<p>Textabsatz</p>`                  |
    | `<div>`        | Containerelement                          | `<div>Inhalt</div>`                  |
    | `<ul>`         | Ungeordnete Liste                         | `<ul><li>Listenelement</li></ul>`    |
    | `<ol>`         | Geordnete Liste                           | `<ol><li>Listenelement</li></ol>`    |
    | `<li>`         | Listenelement                             | `<li>Listenelement</li>`             |

2. Inline Elemente (nehmen nur die Breite ihres Inhalts)

    | HTML-Element | Beschreibung                    | Beispiel                              |
    |:------------:|:-------------------------------:|:-------------------------------------:|
    | `<a>`        | Hyperlink (intern, extern)      | `<a href="url">Linktext</a>`          |
    | `<img>`      | Bild                            | `<img src="bild.jpg" alt="Beschreibung">` |


## CSS-Eigenschaften

CSS (Cascading Style Sheets) wird verwendet, um das Aussehen und Layout von HTML-Elementen zu gestalten. Hier ist eine Tabelle mit einigen grundlegenden CSS-Eigenschaften, sortiert nach ihren Anwendungskategorien:

### Textformatierung
| Eigenschaft       | Beschreibung                                   | Beispiel                        |
|-------------------|------------------------------------------------|---------------------------------|
| `color`           | Setzt die Textfarbe.                           | `color: blue;`                  |
| `font-size`       | Bestimmt die Schriftgröße.                     | `font-size: 16px;`              |
| `text-decoration` | Fügt Dekorationen wie Unterstreichungen hinzu. | `text-decoration: underline;`   |
| `font-weight`     | Definiert die Dicke der Schrift.               | `font-weight: bold;`            |
| `font-family`     | Bestimmt die Schriftart.                       | `font-family: Arial, sans-serif;`|
| `font-style`      | Legt den Stil der Schrift fest (z.B. kursiv).  | `font-style: italic;`           |

### Größen
| Eigenschaft | Beschreibung                            | Beispiel              |
|-------------|-----------------------------------------|-----------------------|
| `width`     | Setzt die Breite eines Elements.        | `width: 100px;`       |
| `height`    | Bestimmt die Höhe eines Elements.       | `height: 200px;`      |

### Abstände und Rahmen
| Eigenschaft | Beschreibung                                   | Beispiel             |
|-------------|------------------------------------------------|----------------------|
| `margin`    | Definiert den Außenabstand um ein Element herum.| `margin: 10px;`     |
| `padding`   | Setzt den Innenabstand innerhalb eines Elements.| `padding: 20px;`    |
| `border`    | Fügt einen Rand um das Element hinzu.           | `border: 1px solid black;`|

### Hintergrund
| Eigenschaft        | Beschreibung                          | Beispiel                    |
|--------------------|---------------------------------------|-----------------------------|
| `background-color` | Legt die Hintergrundfarbe fest.       | `background-color: yellow;` |
