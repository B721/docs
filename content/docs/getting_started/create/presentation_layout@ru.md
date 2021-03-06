---
$title: Изменение представления и макета
---

## Изменение представления

Настройка стиля страниц AMP и их элементов выполняется с использованием стандартных свойств CSS. Вы можете изменить стиль элементов, используя селекторы классов или элементов в таблице стилей `<style amp-custom>`, встроенной в раздел `<head>`:

[sourcecode:html]
<style amp-custom>
  /* any custom style goes here */
  body {
    background-color: white;
  }
  amp-img {
    background-color: gray;
    border: 1px solid black;
  }
</style>
[/sourcecode]

Каждая страница AMP может иметь только одну встроенную таблицу стилей, в которой не разрешается использовать некоторые селекторы. [См. дополнительную информацию о настройке стиля]({{g.doc('/content/docs/design/responsive/style_pages.md', locale=doc.locale).url.path}}).

## Управление макетом

В разметке AMP используются более строгие правила расположения элементов на странице. Для расположения элементов на обычной странице HTML как правило используются только таблицы CSS. Однако разметка AMP в целях повышения скорости отображения требует указания точных размеров всех элементов с самого начала.

Дополнительная информация о том, как разметка AMP выполняет визуализацию и компоновку страницы, а также о способах изменения макета содержится в разделе [Управление макетом]({{g.doc('/content/docs/design/responsive/control_layout.md', locale=doc.locale).url.path}}).

<div class="prev-next-buttons">
  <a class="button prev-button" href="{{g.doc('/content/docs/getting_started/create/include_image.md', locale=doc.locale).url.path}}"><span class="arrow-prev">Предыдущий</span></a>
  <a class="button next-button" href="{{g.doc('/content/docs/getting_started/create/preview_and_validate.md', locale=doc.locale).url.path}}"><span class="arrow-next">Следующий</span></a>
</div>
