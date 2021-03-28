### @ explicitHints true
### @flyoutOnly true

# Das Tutorial zum Einstieg

## Schritt 1: Allgemein @unplugged
### Herzlich willkommen
Allgemeine Einführung
+ Punkt 1
+ Punkt 2

## Schritt 2a: Hinweise 1
Wir starten mit der ersten Aufgabe:
Beim Start sollte die Zahl 5 dargestellt werden - suche jetzt die Befehle.
```blocks
    basic.showNumber(5)
```

## Schritt 2b: Blocks 2
Wir starten mit der ersten Aufgabe:
x sollte die Zahl 5 dargestellt werden - suche jetzt die Befehle.
```blocks
    basic.forever(function () {
        basic.showNumber(input.temperature())
        basic.pause(1000)
    })

    input.onButtonPressed(Button.A, function () {
        basic.showString("AL")
    })

    basic.showString("Start")
 ```  



## Schritt 3: Hinweise 2
Wir starten mit der zweite Aufgabe (sigs):
Beim Start sollte die Zahl 6 dargestellt werden - suche jetzt die Befehle.

    basic.showNumber(6)
```blocks
    basic.forever(() => {
        basic.showString("forever")
    })
```




* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

