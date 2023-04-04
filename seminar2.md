# Краткое руководство по Маркдауну

## Краткое руководство


### Списки


### Цитаты


### Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.

```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count"
        class="publisher-nav-color" data-nav="conversation">
      <span class="comment-count">0
комментариев</span>
      <span class="comment-countplaceholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" datatoggle="dropdown">
      <span class="dropdown-toggle-wrapper">
      <span>
      Войти
      </span>
      </span>
      <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности.