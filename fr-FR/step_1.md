La classe `xcenter` dans ton fichier `style.css` aligne les éléments au centre horizontalement.

La classe `ycenter` dans ton fichier `style.css` aligne les éléments au centre verticalement.

Si tu appliques les classes `xcenter` et `ycenter`, tu alignes les éléments au centre à la fois horizontalement et verticalement.

![L'axe x horizontal et l'axe y vertical avec les visages emoji se déplaçant pour mettre en évidence le centrage horizontal et vertical.](images/center.gif)

--- code ---
---
language: html
filename: index.html
line_numbers: false
---
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

--- /code ---

<iframe src="https://editor.raspberrypi.org/fr-FR/embed/viewer/web-x-y-center" width="400" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
