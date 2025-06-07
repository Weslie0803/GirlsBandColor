# Girls Band Color
[中文](doc/README-zh.md)　[日本語](doc/README-jp.md)

For better calling of different Girls Band Color when using `matplotlib` as well as other scientific drawing tools, this python-based package is made for gathering colors data.

## Install
Clone this repository:
``` bash
git clone https://github.com/Weslie0803/GirlsBandColor.git
cd GirlsBandColor
```

Add this package into the environment:
```bash
pip install .
```

Now you can use this package in Python and Jupyter Notebook and so on.

## Usage
Import in python
``` python
import gbcolor
# Other needed packages
```

Calling colors:：
``` python
tomori = gbcolor.bangdream.mygo.tomori
# There are many other colors in the package.
```

Plot in color:
``` python
plt.plot(x, line_tomori, color=tomori, label='Tomori', linewidth=1)
```

Full demostration lies in `demo.ipynb`：
![](../img/Mayou_Uta_plot.png)

## Color List

[Here](colorlist.md)