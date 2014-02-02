VkTranslator
======

Автоматический перевод входящих и исходящих сообщений на сайте ВКонтакте в разделе "Диалоги". Сервис перевода - Google Translate.

<h4>Описание</h4>
При установке скрипта появляется возможность удобного общения с иностранцами без необходимости каждый раз копировать и вставлять свои и его реплики в переводчик. Теперь все сообщения, и исходящие, и входящие, автоматически переводятся через Google Translate. В правом нижнем углу появляется панелька с выбором языка собеседника (доступен выбор из всех языков, поддерживаемых Google переводчиком) и галочка, которую надо выставить, чтобы включить перевод. Входящие сообщения переводятся на язык, который выставлен у вас в настройках ВКонтакте.

<img src="https://s3.amazonaws.com/uso_ss/25141/large.png?1391368031" />


<h4>Установка</h4>
Скрипт устанавливается через дополнение для браузера. Для Firefox это <a href="https://addons.mozilla.org/ru/firefox/addon/greasemonkey/">Greasemonkey</a> или <a href="https://addons.mozilla.org/ru/firefox/addon/scriptish/">Scriptish</a>, для Chrome - <a href="https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=ru">Tampermonkey</a>
Установить скрипт можно со <a href="http://userscripts.org/scripts/show/311768">страницы на userscripts.org</a>

<h4>Известные проблемы, которые в данный момент исправляются:</h4>
1. Так как ВКонтакте использует ajax-навигацию, при переходе в диалог ничего не произойдёт, поэтому нужно обновить страницу (F5)
2. После того, как вы обновили страницу с диалогом, переводчик будет работать только с тем собеседником, который у вас открыт в данный момент, то есть переключение по вкладкам пока не работает.