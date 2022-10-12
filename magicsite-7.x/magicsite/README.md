Модуль интеграции MagicSite c Drupal 7
========================================

# Описание
Модуль предназначен для автоматического встраивания обязательных разделов сайта образовательных организаций, предусмотренных законодательством Российской Федерации, из информационной системы «MagicSite» на сайт под управлением CMS Drupal.  
Внешний вид сайта, включая меню и инкапсулированные обязательные разделы, устанавливается в CMS Drupal. Модуль не оказывает влияния на необязательные разделы, которые ведутся на сайте CMS Drupal.  
При использовании модуля владелец сайта должен завести аккаунт в информационной системе MagicSite и внести в неё данные о своей организации.  
Информационная система «MagicSite» зарегистрирована в РОСПАТЕНТ № 2020662557 от 16 октября 2020 год, включена в Единый реестр российских программ для электронных вычислительных машин и баз данных по Приказу Минцифры России от 15.03.2021 № 151 Приложение № 2, реестровый №9719, совместима со всеми операционными системами, в том числе с операционной системой Альт на платформе х86 и для архитектуры aarch64.  

Информационная система «MagicSite» предусматривает ведение следующих обязательных разделов со своими подразделами:
 * Сведения об образовательной организации;
 * Информационная безопасность;
 * Противодействие коррупции;
 * Независимая оценка качества;
 * Педагоги;
 * Организация питания.

Представление на сайте производится в строгом соответствии с законодательством. При изменении законодательства в ИС MagicSite вносятся соответствующие правки, что автоматически находит отражение на сайте пользователя. Пользователь избавлен от необходимости отслеживать требования к сайтам образовательных организаций – достаточно заполнять поля ИС MagicSite. Данные попадают в систему мониторинга сайтов.

# Требования
Drupal версии 7.х с установленным модулем jQuery Update (https://www.drupal.org/project/jquery_update)

# Установка с использованием модуля "Update Manager"
1. Скачайте ZIP архив модуля https://github.com/e-publish/drupal_magic_site/raw/master/magicsite-7.x.tar.gz
2. Авторизуйтесь на вашем сайте под пользователем имеющим права на установку и настройку модулей  
3. В меню администратора кликните по ссылке "Модули"
4. В открывшемся окне кликните по ссылке "Установить новый модуль"
  >Если вы не видите ссылку "Установить новый модуль", необходимо активировать модуль "Update Manager", для чего:
  >* Найдите в списке моудлей "Update Manager"
  >* Отметьте чекбокс рядом с названием данного модуля
  >* Hажмите кнопку "Сохранить конфигурацию" внизу страницы
5. В разделе "Загрузите архив модуля или темы для установки" кликните "Выберите файл" и выберите скачанный в шаге 1 архив
6. Нажмите кнопку "Установить"

После установки модуля вы будете перенаправлены на страницу "Update manager".  
Кликните по ссылке "Включить недавно добавленные модули" ("Enable newly added modules")

# Установка вручную (без использования модуля "Update Manager")
1. Скачайте ZIP архив модуля https://github.com/e-publish/drupal_magic_site/raw/master/magicsite-7.x.tar.gz
2. Распакуйте архив в папку /sites/all/modules вашего сайта.

# Активация
После установки модуля и перехода по ссылке "Включить недавно добавленные модули" ("Enable newly added modules") вы окажитесь на странице "Расширения".  
Если вы не перешли по ссылке "Enable newly added modules" поле установки модуля, то активировать его можно на странице "Модули" администативного раздела, для этого:
1. Авторизуйтесь на вашем сайте под пользователем имеющим права на установку и настройку модулей  
2. В меню администратора кликните по ссылке "Модули"
Активируйте модуль, для чего:
1. Найдите в таблице модуль "MagicSite"
2. Отметтье чекбокс в колонке "Включено" в строке модуля "MagicSite"
3. Внизу страницы нажмите кнопку "Сохранить конфигурацию"

# Настройка
1. Авторизуйтесь на вашем сайте под пользователем имеющим права на установку и настройку модулей  
2. В меню администратора кликните по ссылке "Модули"
3. На странице "Модули" администативного раздела, в колонке "Операции" строки модуля "MagicSite" кликнте по ссылке "Настроить".  
4. В поле "URL сайта в ИС MagicSite" укажите адрес сайта, созданного в виртуальном кабинете MagicSite (https://cp.edusite.ru)  
5. Нажмите кнопку "Сохранить конфигурацию".

# Меню модуля
Для отображения меню навигации по обязатальным разделам сайта образовательной организации разместите блок меню "Сведения об образовательной организации" в нужную область вашего сайта на CMS Drupal, для чего:
1. Авторизуйтесь на вашем сайте под пользователем имеющим права на установку и настройку модулей
2. В меню администатора кликните по ссылке "Структура"
3. В открывшемся окне кликните по ссылке "Блоки"
4. В выпадающем списке колонки "Область" блока "Сведения об образовательной организации" выберите облась сайта, к которой вы хотите разместить меню навигации по обязательным разделам сайта образовательной организации
  >Рекомендуем разместить данное меню в той же области сайта, где расположено основное меню навигации.
  >Как правило, это "первая боковая колонка"
5. Нажмите кнопку "Сохранить блоки"

# Удаление
1. Авторизуйтесь на вашем сайте под пользователем имеющим права на установку и настройку модулей  
2. В меню администратора кликните по ссылке "Модули"
3. Снимите отметку с чекбокса в колонке "Включено" в строке модуля "MagicSite"
4. Внизу страницы нажмите кнопку "Сохранить конфигурацию"
5. Перейдите на закладку "Удалить" страницы "Модули"
6. Отметтье чекбокс в колонке "Удалить" в строке модуля "MagicSite"
7. Нажмите кнопку "Удалить"
8. В открывшемся окне подтверждения нажмите кнопку "Удалить"