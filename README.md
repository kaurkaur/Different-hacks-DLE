# Different-hacks-DLE
Различные хаки которые не дотягивают до полноценных модулей.
Может кому-то пригодятся.


#### Added-tags-in-categorymenu.xml
-----------------------------
  - Шаблон применения **categorymenu.tpl**
  
Добавляет аналогичный тегам `[isparent][/isparent]` теги `[ischildren][/ischildren]`.
Применяются между `[item][/item]` выводит текст для итема который является дочерним. (срабатывает только начиная с дочернего итема)
Тег `{sub-count}` применяется в как можно понять между мегами `[sub-prefix][/sub-prefix]` заменяется на порядковый номер дочерней категории.
