# ITMOWebFirstHW.github.io
Доработать лабораторную работу 1 для работы с внешним API, позволяющим получить данные о погоде в городе.
При первой загрузке страницы происходит запрос пользователя на получение данных о геолокации с использованием HTML5 Geolocation API. Если пользователь соглашается предоставить данные о геолокации – получаем из внешнего API данные о погоде (API можно выбрать самостоятельно). Если нет – запрашиваем информацию для города по умолчанию (город по умолчанию можно выбрать самостоятельно). Эти сведения отображаются в верхней части страницы – "Погода здесь". Иконка погоды должна соответствовать тем данным о погоде, что были получены из API.

У пользователя есть возможность добавления и удаления городов в избранное. Информация о погоде отображается для всех городов из избранного в соответствии с макетом и реализацией первой лабораторной работы (секция "Избранное"). Список избранных городов сохраняется в LocalStorage. Сами данные о погоде в LocalStorage сохранять не нужно – запрос актуальных сведений происходит при каждой загрузке страницы.

Пока происходит загрузка данных по конкретному городу/локации – показываем loader и/или сообщение об ожидании загрузки данных. Пример ниже, в вашей реализации может отличаться.


В случае возникновения ошибки при работе с API пользователь должен получить информацию о возникновении подобной ситуации. Адаптивность страницы должна сохраняться.
Реализация должна быть на нативном JavaScript, без использования сторонних библиотек.

Разработка должна вестись итеративно и публиковаться на github. К моменту проверки и сдачи работы репозиторий должен быть публичным. Также должна быть настроена публикация работы на github pages.
