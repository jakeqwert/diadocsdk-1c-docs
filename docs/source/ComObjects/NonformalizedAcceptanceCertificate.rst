NonformalizedAcceptanceCertificate
==================================

Документам *Акт о выполнении работ* в произвольном формате.
Является производным объектом от :doc:`DocumentBase`


.. rubric:: Свойства

:Total:
  **Число, чтение** - cумма по документу

:Vat:
  **Число, чтение** - cумма НДС по документу

:Grounds:
  **Строка, чтение** - основание документа

:Status:
  **Строка, чтение** - статус документа. :doc:`Возможные значения <./Enums/BilateralStatus>`

  .. deprecated:: 5.34.0
    Используйте поле **DocflowStatus**
