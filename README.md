# Dugimail_letter
Dugimail репозиторий с примером верстки e-mail для почтовых сервисов

Инструмент
Проверка поддержки свойств - https://www.caniemail.com/
Проверка поддержки свойств - https://caniuse.email/
Инлайнер - https://www.campaignmonitor.com/resources/tools/css-inliner/
Валидатор - https://validator.w3.org/
Фреймворк - https://mjml.io/
Ручные тесты - https://putsmail.com/
Автоматические тесты - www.emailonacid.com/

ibb.co хостинг для картинок


Правило
1. Использовать инлайн-стили
2. Использовать табличную верстку
3. Использовать html-атрибуты везде, где возможно
4. Мобильная версия - ниже 600 пикселей как правило\
5. Стараться без медиа-запросов - яндекс не поддерживает
6. Для outlook иногда могут пригодиться спец комментарии
7. Соблюдать порог 102кб (не считая картинок) у кода письма, ибо gmail сожмет письмо
8. Яндекс почта перезагружает фотографии к себе
9. Предупредить, что outlook изначально не загружает никакие фотографии, лишь по клику внутри письма
10. Яндекс в темной теме инвертирует цвета (белый становится темным, черный - белым)
11. Важно писать стили полностью (не padding: 5px 5px, а padding-top: 5px; padding-left: 5px и так далее)
12. Избегать чрезмерной вложенности (для поддержки шаблона, для порога 102кб)
13. Не использовать background-image, ибо outlook не поддерживает (9% поддержка outlook)
14. Не использовать вебшрифты, только безопасные - https://websitesetup.org/web-safe-fonts-html-css/
15. Осторожно использовать gif и анимацию (ховер эффекты и т.д.)
16. Писать значения цветов полностью: #ffffff вместо #fff
17. <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN"> - обязательный доктайп
18. Не используйте colspan, rowspan
19. Используйте valign и align
20. cellpadding и cellspacing установите в 0. так же не используйте border
21. Старайтесь использовать пиксели (не считая ширины и высоты, возможно)
22. Используйте <br> для переносов
23. Следите за поддержкой свойств: https://www.caniemail.com/ https://caniuse.email/
24. Используйте прехедер <div style="font-size:0px;font-color:#ffffff;opacity:0;visibility:hidden;width:0;height:0;display:none;">текст прехедера</div>
25. Старайтесь делать фолбэки для картинок, если это возможно (bgcolor)
26. Делайте телефон и почту - ссылками
27. Старайтесь использовать резиновую верстку, если возможно
28. Не забывайте про атрибуты title у ссылок, alt у картинок
29. Внедряйте интерактив, но аккуратно. Без него - скучно.
30. Можно писать стили в теге style, а затем использовать css-инлайнеры: https://www.campaignmonitor.com/resources/tools/css-inliner/
31. Если вдруг не нужна поддержка outlook - используйте фреймворк mjml
32. Проверяйте валидность: https://validator.w3.org/
33. Тестируйте: https://putsmail.com/ и www.emailonacid.com
34. Изучайте чужие письма на предмет поиска крутых решений
35. Лишь сверстав кучу писем - поймете как их делать) иначе никак


Features	gmail - web	gmail - android	Outlook - windows	Outlook - android	mail.ru - web	mail.ru - android	yandex - web	yandex - android	yahoo! mail	outlook.com	spark
background-image	 +	 +	 -	 +	 +	 +	 +	 +	?	 ?	 +
gif	 +	 +	 -	?	 +	 +	 +	 +	?	?	 +
web fonts	 -	 -	 -	?	 -	 -	 -	 -	?	 -	 +