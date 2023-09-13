# Die schwarze Brauerey
Willkommen, Reisender. Setz dich gerne zu uns und erzähle uns von deinen Reisen und den Wundern, die su gesehen hast -- die unbekannten Monster, und dunklen Höhlen. Erzähle uns von den Schätzen und Artefakten, die du gefunden hast und deren Wunder noch darauf warten entdeckt zu werden --

## Selbst gemachte DSA Abenteuer einfach gestaltet
`Die schwarze Brauerey` macht das Erstellen teilen von selbst geschriebenen und gut ausschauenden DSA 5 Abenteuern sehr einfach. Es wird [Markdown](https://guides.github.com/features/mastering-markdown/) und ein wenig CSS Magie verwendet um deine Geschichten glänzen zu lassen.

<div class="x-center y-bottom">
<!-- newline required -->

```table-wide
| Block       | Name              | Edition  |
|:-----------:|:-----------------:|:--------:|
| Spell list  | spells            | 5e       |
| Note        | note              | 5e       |
| Descriptive | descriptive       | 5e       |
| Stat Block  | stats, stats-wide | 5e       |
| Class Table | class, class-wide | 5e       |
| Table       | table, table-wide | 5e       |
| TOC         | toc               | 5e       |
| Sidebar     | sidebar           | 3.5e, 4e |
| Wide Sidebar| sidebar-wide      | 3.5e, 4e |
```
</div>

**Probier es aus!** Bearbeite einfach den text auf der Linken Seite und schau zu, wie sich die rechte Seite live anpasst.

NAtürlich ist auch das bestausschaunde Dokument keine große Hilfe, wenn man es nicht ausdrucken kann. Glücklicherweise ist das Exportiren von PDFs mit der `Schwarzen Brauerey` ziemlich simpel:
- **Mac**: &#8984;-Shift-E.
- **Windows**: Strg-Shift-E.

Hast du Ideen wie die `Schwarzen Brauerey` noch besser werden kann? Oder hast du etwas gefunden, was nicht richtig funktioniert? Dann komm [hier hin](https://github.com/FrogWithAHat/DieSchwarzeBrauerey/issues/new) und lass es mich wissen!

## Lizenzkrams

`Die schwarze Brauerey` arbeitet unter der MIT License, was heißt, dass du mit der `SchwarzenBrauerey` machen kannst was du magst, 
\col 
außer zu behaupten, dass du es selbst gemacht hast. habe ich nämlich auch nicht. Diese Version der `Schwarzen Brauerey`basiert auf dem [DnD Homebrewey Projekt](https://github.com/noahlange/homebrewery-electron) von Noah Lange.

Wenn du *irgendwelche* Dokumente öffentlich publizieren willst, die mit der `Schwarzen Brauerey` gestaltet wurden, liegt es an dir dich darum zu kümmern, dass du die entsprechenden Rechte/Nutzungsrechte an Schriften, Bildern und Layoutelementen, Namen und urheberrechtlich geschützen Inhalten hast.

Bei den Schriften habe ich versucht die im Layoutguide vorgegebene Schriften durch frei verfügbare Versionen zu ersetzten. Ob man diese aber auch frei in komerziellen Projekten nutzen darf habe ich nicht geprüft.

Ein weiterer interessanter Punkt dürfte die 2023 an gekündigte ELF Lizenz von Ulisses sein. Aber auch hier bist *DU* am Drücker und musst dich kümmern.

### Dokumente im DSA 5 Stil erstellen - Vorbereitungen
Um das volle Benutzerelebnis zu haben musst du ein wenig mitarbeiten. Ulisses hat ein Layoutpaket zusammengestellt mit dem man Dokumente im Stil von DSA 5 für das Scriptorium designen kann. Da es sich hierbei um urheberrechtlich geschützte Dateien handelt liegen diese nicht im Auslieferungszustand bei. Du kannst sie aber kostenlos im [eBook Store][def] von Ulisses herunter laden und dann einfach in die passenden Ordner in diesem Projekt kopieren, die Scripte erwarten die Dateien dann dort.

## Markdown
Markdown is a lightweight markup language that is used to generate the HTML styled by `The Homebrewery`. If Markdown proves insufficient for your needs, you can use a limited subset of HTML to augment your Markdown.

- **Headers**: Headers are denoted with pound signs, the more signs, the smaller the header. Follow the last pound with a space and the text of your header.
- **Emphasis**: Emphasis is shown with asterisks on either side of a word or phrase -- single asterisks for *italic*, double asterisks for **bold**.
- **Small caps** - use backticks to render `small caps`.
- **Links**: Links are created with square brackets (around the text of the link) followed directly with parentheses and the url inside.
- **Lists**: Undordered lists are made with dashes and can be nested arbitrarily with two spaces. Ordered lists use a number instead of a dash.
- **Images:** Images use the same format as links, but are prefixed with an exclamation point (!). Currently images must be hosted on a third-party site (imgur, etc.) or provided with an absolute filepath.
- **Column and page breaks** are left to the author. To start a new page, use a backslash followed by the word *page*. Use a backslash followed by the word *col* to break to the next column.
- **Fences** are block elements. Indicate sidebars, notes and tables with triple backticks, followed by the name of the block element. Close the block with three more backticks.

<div class='page-number'>1</div>
<div class='footnote'>PART 1 | FANCINESS</div>


[def]: https://www.drivethrurpg.com/product/197880/Scriptorium-Aventuris--LayoutBaukasten