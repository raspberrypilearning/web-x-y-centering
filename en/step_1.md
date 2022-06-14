The `xcenter` class in your `style.css` file aligns items to the center horizontally.

The `ycenter` class in your `style.css` file aligns items to the center vertically.

Applying both the `xcenter` and `ycenter` classes will align items to the center both horizontally and vertically. 

![An animated image showing the horizontal x-axis and vertical y-axis with emoji face moving along to highlight the horizontal and vertical centering.](images/center.gif)
    
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
      
<iframe src="https://trinket.io/embed/html/34d34865bf?toggleCode=true" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
