=== Noindex Links ===
Contributors: Flector
Donate link: https://money.yandex.ru/to/41001443750704/200
Tags: wp-noindex, noindex, yandex, nofollow
Requires at least: 2.3
Tested up to: 6.6
Requires PHP: 5.3
Stable tag: trunk

Плагин заключает любые ссылки в комментариях в теги &lt;noindex&gt;&lt;/noindex&gt;.

== Description ==

Плагин <strong>Noindex Links</strong> (старое название <strong>WP-Noindex</strong>) запрещает Яндексу учитывать ссылки в комментариях. Плагин оборачивает noindex тегами как ссылки авторов комментариев (если они заполнили поле "Сайт" при написании комментария), так и ссылки в тексте самих комментариев.

Яндекс давно уже учитывает "nofollow" атрибут у ссылок, но среди SEO-специалистов бытует мнение, что полностью игнорировать ссылки Яндекс будет только, если они заключены в noindex теги (в пользу этой теории говорит появление в последнее время нескольких бирж по продаже nofollow-комментариев). 

В версии плагина 2.00 простые теги &lt;noindex&gt;&lt;/noindex&gt; заменены на валидные эквиваленты &lt;!--noindex--&gt;&lt;!--/noindex--&gt;. Более подробно читайте на [странице плагина](http://www.wordpressplugins.ru/seo/wp-noindex.html).

Если вам понравился мой плагин, то <strong>пожалуйста</strong> поставьте ему 5 звезд.
 

== Frequently Asked Questions ==

= Инструкция по установке =

1. Установите плагин через меню &#171;<strong>Плагины\Добавить новый</strong>&#187; (искать &#171;<strong>Noindex Links</strong>&#187;).
2. Активируйте плагин в меню &#171;<strong>Плагины</strong>&#187;.
3. Это все.

== Screenshots ==

1. Пример ссылки в комментарии при просмотре в инспекторе кода.

== Changelog ==

= 2.0 =
* Ссылки в поле "Сайт" тоже теперь оборачиваются noindex тегами.
* Теги &lt;noindex&gt; заменены на валидные варианты в виде &lt;!--noindex--&gt;.
* Плагин переименован в "Noindex Links" вместо "WP-Noindex".

= 1.0 =
* Первая версия
