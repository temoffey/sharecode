// Ну здравствуй, мой дорогой друг!

Ура! Я запилил комнаты!!!

// Новое на 26.04.2014:
// * кроссбраузерная верстка.
// * подсветка курсоров для неограниченного количества пользователей.
// * прогрузка кода и курсоров пользователей с прогрузкой страницы.
// * создание комнат, и сохранение их состояния при выходе всех пользователей.

ВНИМАНИЕ!!! Сервис на стадии BETA тестирования, данные, сохраненные в комнатах, могут быть утеряны!!!

// Известные баги:
// * баг наложения курсора в IE
// * баг с фантомным курсором при обновлении страницы (Chrome)
// * баг со смещением курсоров при одновременном вводе текста несколькими клиентами (зависит от скорости соединения)
// * по умолчанию нет фокуса на поле ввода (Chrome)

// Планы
// * подсветка курсоров при выделении (от начальной до конечной позиций)
// * подсветку имен (продумываю способы авторизации)
// * создание главной страницы со списком комнат
// * оптимизация затрат на передачу данных + реакция на кнопку Tab
// * создание приватных и readonly комнат (продумываю способы авторизации)

// Тестовые строчки

function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) + 
             ' class=""';
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      return/\d+[\s/]/g;
  }
}