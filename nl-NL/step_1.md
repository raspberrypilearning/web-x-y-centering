De klasse `xcenter` in jouw `style.css`-bestand lijnt items horizontaal uit op het midden.

De klasse `ycenter` in jouw `style.css`-bestand lijnt items verticaal uit op het midden.

Als je zowel de klasse `xcenter` als `ycenter` toepast, lijn je items zowel horizontaal als verticaal uit op het midden.

![De horizontale x-as en de verticale y-as met emoji-gezichten die bewegen om de horizontale en verticale centrering te benadrukken.](images/center.gif)

## --- code ---

language: html
filename: index.html
line_numbers: false
--------------------------------------------------------

```
  <section class="wrap">
    <div class="xcenter tile tertiary">
      <p>Lorem ipsum</p>
    </div>
    <div class="ycenter tile secondary">
      <p>Lorem ipsum</p>
    </div>
    <div class="xcenter ycenter tile tertiary">
      <p>Lorem ipsum</p>
    </div>
  </section>
```

\--- /code ---

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/web-x-y-center" width="400" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
