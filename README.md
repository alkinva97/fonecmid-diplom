# Инструкция по начальной настройке

## Для корректной работы новых разделов Обслуживание клиентов и Расчет управленческой зарплаты требуется дополнительная настройка

Вам нужно:

- Заполнить справочник Сотрудники в разделе Обслуживание клиентов в группе Справочники
    
    Справочник заполнить всеми сотрудниками которые будут взаимодействовать с новой функциональностью
- Сотрудникам категории "Специалист" создать пользователя информационной базы с профилем Специалист
- Сотрудникам категории "Администротивный персонал" создать пользователя информационной базы с профилями  Менеджер, Бухгалтер IT-Фирмы, Кадровик-расчетчик в соответствии с их функциональными обязонастями
- В справочнике Номенклатура создать 2 элемента, которые будут отражать абонентскую плату и работу специалиста в документе Реализация товаров и услуг
- В разделе для технического специалиста заполнить константы "Номенклатура абонентская плата" и "Номенклатура работы специалиста" соответствуемщими элементами справочника Номенклатура созданнами на предыдущего шага
- В разделе для технического специалиста заполнить константы "Токен управления телеграм-ботом" и "Идентификатор группы для оповещения"
- В разделе Расчет управленческой зарплаты заполнить Графики работы персонала в группе Справочники
    
    Графиков работы отражающих рабочее время может быть неограниченное количество, но один из графиков обязательно должен отражать календарное время (его нужно указывать при расчете Отпуска)
- Необходимо заполнить Регистр сведений Режим работы в группе Прочие, для этого оптимально воспользоваться обработкой Заполнение режима работы в группе Сервис 
- Нужно заполнить Регистр сведений Условия оплаты сотрудников в группе Прочие
