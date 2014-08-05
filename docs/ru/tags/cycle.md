Тег {cycle}
===========

Тег {cycle} используется для прохода через множество значений.
С его помощью можно легко реализовать чередование двух или более заданных значений.

```smarty
{for $i=$a.c..}
    <div class="{cycle ["odd", "even"]}">
{/for}


{for $i=$a.c..}
    <div class="{cycle ["odd", "even"] index=$i}">
{/for}
```