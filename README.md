# HabrCacheEnhanced
Перенаправляет удалённые или скрытые в черновики записи с habr.com на СоХабр, ITnan и кэш Google.

Основан на скрипте [HabrCache](https://userscripts-mirror.org/scripts/show/136481) от [dotneter](https://userscripts-mirror.org/users/138395.html). Код для работы с СоХабром любезно предоставлен [CaptainFlint](https://habr.com/users/CaptainFlint/).

Обучен распознавать страницы 404 в блогах компаний (у блогов страницы о недоступности поста отличаются от аналогичных страниц обычных пользователей, поэтому старый скрипт на этих страницах не срабатывал) и сами удалённые блоги компаний.

Скрипт тестировался лишь в Firefox. Ниже располагаются примеры для проверки работы.

* [запись, скрытая в черновики](https://habr.com/post/423433/)
* [запись, удалённая из блога компании](https://habr.com/company/muk/blog/255299/)
* [удалённый блог компании, прекратившей деятельность на ресурсе](https://habr.com/company/teradata/blog/)
