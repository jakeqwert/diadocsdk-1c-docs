Department
==========

Подразделение организации

.. rubric:: Свойства

:Id:
  **Строка, чтение** - идентификатор подразделения в Диадоке

:Name:
  **Строка, чтение** - наименование подразделения

:Abbreviation:
  **Строка, чтение** - аббревиатура подразделения

:Kpp:
  **Строка, чтение** - КПП подразделения

:ParentDepartment:
  :doc:`Department` **, чтение** - родительское подразделение

:Subdepartments:
  :doc:`Коллекция <Collection>` **объектов** :doc:`Department` **, чтение** - дочерние подразделения

:Address:
  :doc:`AddressInfo <AddressInfo>` **, чтение** - адрес подразделения


.. note::
  Идентификатор головного подразделения всегда ``00000000-0000-0000-0000-000000000000``
