---
title: Индекс.мд
the_answer: 'let Code = function() { return function(name) { return "Hello " + name
  + "!"; }; }; '

---
## Скоро тут будет какой-то контент

> (но это не точно).

А пока подумайте над задачей:

```javascript
let hello = new Code();
let name = "stgolem";
console.log(hello(name)); // -> "Hello, stgolem!"
```

Как реализовать `Code` ?

1. Никак - такой результат невозможен :(
2. Используйте воображение - это JS детка!

<div id="the_answer" style="display: none">
{% highlight javascript %}
{{ page.the_answer }}
{% endhighlight %}
</div>

## А вот и первая кровь

- [Как мы дизайнер в веб перетаскивали]({{ site.baseurl }}{% post_url 2018-08-26-web-stack-choose-enterprise %})