InvoiceRevision
===============

Документ *Исправление счета-фактуры*.

Наследует интерфейс :doc:`DocumentBase`


.. rubric:: Свойства

:Currency:
  **Число, чтение** - код валюты

:ConfirmationDate:
  **Дата и время, чтение** - дата и время подтверждения спец. оператора передачи ЭСФ

:AmendmentRequested:
  **Булево, чтение** - признак, был ли запрос на уточнение

:Revised:
  **Булево, чтение** - признак, было ли исправление данного ЭСФ

:Corrected:
  **Булево, чтение** - признак, была ли корректировка данного ЭСФ

:Total:
  **Число, чтение** - сумма по документу

:Vat:
  **Число, чтение** - сумма НДС по документ

:OriginalDocumentDate:
  **Дата, чтение** - дата первоначального счета-фактуры

:OriginalDocumentNumber:
  **Строка, чтение** - номер первоначального счета-фактуры

:Status:
  **Строка, чтение** - текущий статус документа в Диадоке. :doc:`Возможные значения <./Enums/InvoiceStatus>`

  .. deprecated:: 5.34.0
    Используйте поле **DocflowStatus**
