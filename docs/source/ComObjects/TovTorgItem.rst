TovTorgItem
===========

`Сведения об ассортименте, количестве, стоимости товара <https://normativ.kontur.ru/document?moduleId=1&documentId=265102&rangeId=233865>`_

.. deprecated:: 5.27.0
  Используйте :doc:`DynamicContent`

.. rubric:: Свойства

:Product:
  **Строка, чтение/запись** - наименование товара

:Feature:
  **Строка, чтение/запись** - характеристика товара

:Sort:
  **Строка, чтение/запись** - сорт товара

:VendorCode:
  **Строка, чтение/запись** - артикул товара

:ProductCode:
  **Строка, чтение/запись** - код товара

:UnitName:
  **Строка, чтение/запись** - наименование единицы измерения товара

:Unit:
  **Строка, чтение/запись** - код единицы измерения

:PackageType:
  **Строка, чтение/запись** - вид упаковки товара

:QuantityInPack:
  **Число, чтение/запись** - количество мест в 1 упаковке

:Quantity:
  **Число, чтение/запись** - количество единиц товара

:Gross:
  **Число, чтение/запись** - масса брутто

:Net:
  **Число, чтение/запись** - масса нетто, количество передано (отпущено)

:ItemToRelease:
  **Число, чтение/запись** - Количество надлежит отпустить

:Price:
  **Число, чтение/запись** - цена за единицу товара

:SubtotalWithVatExcluded:
  **Число, чтение/запись** - сумма без учета налога

:TaxRate:
  **Строка, чтение/запись** - ставка налога. :doc:`Возможные значения <./Enums/TaxRate>`

:Vat:
  **Число, чтение/запись** - сумма налога

:Subtotal:
  **Число, чтение/запись** - сумма всего

:ItemAccountDebit:
  **Строка, чтение/запись** - корреспондирующие счета: дебет

:ItemAccountCredit:
  **Строка, чтение/запись** - корреспондирующие счета: кредит

:StructedAdditionalInfos:
  :doc:`Коллекция <Collection>` **объектов** :doc:`StructedAdditionalInfo` **, чтение** - информационное поле документа



.. rubric:: Методы

+------------------------------------------+
| |TovTorgItem-AddStructedAdditionalInfo|_ |
+------------------------------------------+

.. |TovTorgItem-AddStructedAdditionalInfo| replace:: AddStructedAdditionalInfo()



.. _TovTorgItem-AddStructedAdditionalInfo:
.. method:: TovTorgItem.AddStructedAdditionalInfo()

  Добавляет :doc:`новый элемент <StructedAdditionalInfo>` в коллекцию *StructedAdditionalInfos* и возвращает его
