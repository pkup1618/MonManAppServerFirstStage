# Unified Financial Analysis

Это очень старый проект, который хотелось-бы преобразовать во что-то большее.

Какое приложение хочется получить:
* Я загружаю выписки из по операциям из банков
* Приложение сохраняет их в унифицированном формате
* Можно редактировать отдельные операции
* Можно строить красивую отчетность по полученным данным из разных банков

Как такое реализовать?

1. Нужно создать общее для всех операций по счетам представление в памяти компьютера
2. Нужно написать парсеры, преобразующие выписки из разных банков, приводящие данные к этому формату
3. Нужно создать реляционное хранилище для операций
4. Нужно написать какой-то UI (console/web/mobile/desktop), а может быть и всё сразу.
    * Красиво рисовать не обязательно, достаточно циферками
    * Уверен, есть библиотека которая хорошо с этим справляется
    * Console - API не нужно, но это сложный вопрос (как делают консольные приложения?)
    * Desktop - API не нужно, но десктоп на Java выглядит отстойно
    * Web/Mobile - нужно API
