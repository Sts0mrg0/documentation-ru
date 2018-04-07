Руководство по синтаксису
=========================

Канборд использует `Markdown
синтаксис <https://ru.wikipedia.org/wiki/Markdown>`__ для комментариев
или описания задач. Далее приведены примеры:

Жирный и курсив
---------------

-  Жирный текст: Используйте 2 звездочки или 2 подчеркивания вокруг
   слов(а)
-  Курсив: Используйте 1 звездочку или 1 подчеркивание вокруг слов(а)

Пример написания (источник)

::

    This **word** is very __important__.

    And here, an *italic* word with one _underscore_.

Результат

This **word** is very **important**.

And here, an *italic* word with one *underscore*.

Неупорядоченные списки
----------------------

Неупорядоченный список использует звездочки, минусы или плюсы вначале
абзаца

Пример написания (источник)

::

    - Item 1
    - Item 2
    - Item 3

    или

    * Item 1
    * Item 2
    * Item 3

Результат

-  Item 1
-  Item 2
-  Item 3

Упорядоченные списки
--------------------

Упорядоченные списки префиксом имеют цифру:

Пример написания (источник)

::

    1. Do that first
    2. Do this
    3. And that

Результат

1. Do that first
2. Do this
3. And that

Ссылки
------

Пример написания (источник)

::

    [My link title](https://kanboard.org/)
    <https://kanboard.org>


Исходный код
------------

Используйте обратные кавычки (переключитесь на анлийскую раскладку и
нажмите ё)

::

    Execute this command: `tail -f /var/log/messages`.

Execute this command: ``tail -f /var/log/messages``.

Используйте 3 обратных кавычки с указанием языка программирования

::

    ```php
    <?php

    phpinfo();

    ?>
    ```

Заголовки
---------

::

    # Title level 1
    ## Title level 2
    ### Title level 3
