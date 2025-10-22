`style.css` 文件中的 `xcenter` 类将项水平对齐到中心。

`style.css` 文件中的 `ycenter` 类将项垂直对齐到中心。

如果你同时应用 `xcenter` 和 `ycenter` 类，则可以将项水平和垂直对齐到中心。

![水平 x 轴和垂直 y 轴，表情符号沿着移动以突出显示水平和垂直居中。](images/center.gif)

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

--- /code --

<iframe src="https://editor.raspberrypi.org/zh-CN/embed/viewer/web-x-y-center" width="400" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
