![external-link](images/external-link.png)[English](https://peter88213.github.io/timeline-view-tk/help/)

---

# Timeline viewer

**Benutzerhandbuch**


Diese Seite bezieht sich auf die aktuelle Ausgabe von 
[timeline-view-tk](https://github.com/peter88213/timeline-view-tk/). 
Sie können sie mit **Hilfe \> Online-Hilfe** öffnen.

## Bedienung


### Scrollen mit der Maus

-   Scrollen Sie die Zeitleiste horizontal mit dem Mausrad bei
    gedrückter Umschalttaste.
-   Scrollen Sie die Zeitleiste vertikal mit dem Mausrad.
-   Scrollen Sie die Zeitleiste in alle Richtungen, indem Sie die Maus
    mit gedrückter rechter Taste ziehen.
-   Den Zeitmaßstab vergrößern oder verkleinern Sie mit dem Mausrad bei
    gedrückter `Strg`-Taste.
-   Die Abstandsgrenzen für das Stapeln verändern Sie mit dem Mausrad
    bei gleichzeitig gedrückter `Strg`- und Umschalttaste.


### Einen Abschnitt in der Zeit verschieben

-   Halten Sie die Umschalttaste gedrückt und klicken Sie auf den
    Zeitleisteneintrag, dann ziehen Sie ihn mit der Maus. Damit bewegen
    Sie den Abschnitt in der Zeit vor oder zurück, während die Dauer
    erhalten bleibt.

### Das Abschnittsende verschieben

-   Halten Sie die `Strg`- und die Umschalttaste gedrückt und klicken
    Sie auf den Zeitleisteneintrag, dann ziehen Sie ihn mit der Maus.
    Damit erhöhen oder verringern Sie die Zeitdauer des Abschnitts,
    während Beginndatum und -zeit erhalten bleiben.

---

**Hinweis** 

- Verschiebe-Operationen mit der Maus lassen sich durch Drücken der
`Esc`-Taste vor dem Loslassen der Maustaste abbrechen. -
Verschiebe-Operationen mit der Maus lassen sich mit
![undo](images/undo.png) rückgängig machen.

---

## Befehlsreferenz

### \"Gehe zu\"-Menü

Erstes Ereignis

:   Damit verschieben Sie die Zeitleiste so, dass das früheste Ereignis
    in der Nähe des linken Rands erscheint.

Letztes Ereignis

:   Damit verschieben Sie die Zeitleiste so, dass das späteste Ereignis
    in der Nähe des rechten Rands erscheint.


### \"Maßstab\"-Menü

Stunden

:   Damit stellen Sie den Maßstab auf eine Stunde pro Skalenstrich ein.

Tage

:   Damit stellen Sie den Maßstab auf einen Tag pro Skalenstrich ein.

Jahre

:   Damit stellen Sie den Maßstab auf ein Jahr pro Skalenstrich ein.

Ans Fenster anpassen

:   Damit stellen Sie den Maßstab und die Position so ein, dass alle
    Abschnitte mit gültiger Datum/Zeitinformation ins Fenster passen.

### \"Kaskadieren\"-Menü

Die Abschnitte werden in der Ereignisdarstellung gestapelt, damit sie
sich nicht überlappen oder den Titel des vorhergehenden Abschnitts
verdecken. Sollte Ihnen der Stapelagorithmus nicht gut genug erscheinen,
können Sie die Abstandsgrenzen für das Stapeln anders einstellen.

Dicht

:   Aufeinander folgende Ereignisse auch dann hintereinander anordnen,
    wenn sie etwas dichter beieinander liegen.

Aufgelockert

:   Aufeinander folgende Ereignisse auch dann untereinander anordnen,
    wenn sie etwas weiter auseinander liegen.

Normal

:   Das Kaskadieren auf die Normaleinstellung zurücksetzen.

---

**Hinweis**


Sie können die Grenzen für das Stapeln mit dem Mausrad fein einstellen,
wenn Sie gleichzeitig die `Strg`- und die Umschalttaste drücken.

---

### \"Optionen\"-Menü

Benutze 00:00 für fehlende Zeiten

:   -   Wenn dieses Feld angekreuzt ist, wird \"00:00\" für Abschnitte
        ohne Zeitangaben verwendet. Dies hat keinen Einfluss auf die
        Eigenschaften des Abschnitts.
    -   Wenn dieses Feld nicht angekreuzt ist, werden Abschnitte ohne
        Zeitangabe nicht angezeigt.

### \"Hilfe\"-Menü

Online-Hilfe

:   Diese Hilfeseite im Webbrowser öffnen.

### Schaltflächen in der Werkzeugleiste am unteren Rand

![rewindLeft](images/rewindLeft.png) Eine Bildschirmseite zurück

:   Damit verschieben Sie die Zeitleiste, um etwa eine Bildschirmbreite
    in die Vergangenheit zu gehen. Dasselbe bewirkt die
    \"Zurück\"-Maustaste (Windows).

![arrowLeft](images/arrowLeft.png) Zurückscrollen

:   Damit verschieben Sie die Zeitleiste, um etwa 1/5 Bildschirmbreite
    in die Vergangenheit zu gehen. Mit dem Mausrad können Sie sie
    genauer verschieben.

![goToFirst](images/goToFirst.png) Gehe zum ersten Ereignis

:   Damit verschieben Sie die Zeitleiste so, dass das früheste Ereignis
    in der Nähe des linken Rands erscheint.

![goToLast](images/goToLast.png) Gehe zum letzten Ereignis

:   Damit verschieben Sie die Zeitleiste so, dass das späteste Ereignis
    in der Nähe des rechten Rands erscheint.

![arrowRight](images/arrowRight.png) Vorscrollen

:   Damit verschieben Sie die Zeitleiste, um etwa 1/5 Bildschirmbreite
    in die Zukunft zu gehen. Mit dem Mausrad können Sie sie genauer
    verschieben.

![rewindRight](images/rewindRight.png) Eine Bildschirmseite nach vorne

:   Damit verschieben Sie die Zeitleiste, um etwa eine Bildschirmbreite
    in die Zukunft zu gehen. Dasselbe bewirkt die \"Vorwärts\"-Maustaste
    (Windows).

![arrowDown](images/arrowDown.png) Den Zeitmaßstab verkleinern

:   Damit verkleinern Sie den Zeitmaßstab in groben Schritten. Für die
    Feineinstellung ist das Mausrad vorgesehen.

![fitToWindow](images/fitToWindow.png) Ans Fenster anpassen

:   Damit stellen Sie den Maßstab und die Position so ein, dass alle
    Abschnitte mit gültiger Datum/Zeitinformation ins Fenster passen.

![arrowUp](images/arrowUp.png) Den Zeitmaßstab vergrößern

:   Damit vergrößern Sie den Zeitmaßstab in groben Schritten. Für die
    Feineinstellung ist das Mausrad vorgesehen.

![undo](images/undo.png) Die letzte Änderung rückgängig machen

:   Damit stellen Sie Datum/Uhrzeit/Dauer vor der letzten Mausoperation
    an einem Abschnitt wieder her.

