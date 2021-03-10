# Отчёт о тестировании Валидатор номера банковской карты.

## Краткое описание

<02.03.2021> - <02.03.2021> было проведено: дымовое, функциональное тестирование
приложения **Валидатор номера банковской карты**.

На тестирование затрачено: 0,03 часа

В результате тестирования выявлены следующие дефекты:
* [Валидатор карт не распознал номер карты VISA длинной более чем 16 цифр](https://github.com/Shliskenstickin/DZ_java1_2/issues/1)
* [Валидатор карт не распознал номера карт American Express](https://github.com/Shliskenstickin/DZ_java1_2/issues/2)
* [Валидатор карт не распознал номер карты Discover длинной более чем 16 цифр](https://github.com/Shliskenstickin/DZ_java1_2/issues/3)
* [Валидатор карт не распознал номер карты JCB длинной более чем 16 цифр](https://github.com/Shliskenstickin/DZ_java1_2/issues/4)
* [Валидатор карт не распознает карты Diners Club - Carte Blanche](https://github.com/Shliskenstickin/DZ_java1_2/issues/5)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Исходный код программы](src/Main.java)

В качестве тестовых данных использовались данные из [Сайт генератор карт](https://www.freeformatter.com/credit-card-number-generator-validator.html):

**VISA:**
<br/>4916629992433400
<br/>4716087107175766
<br/>4916791452817371254
<br/>4539430435406564899
<br/>4916611254331467628

**MasterCard:**
<br/>2221005892016567
<br/>5572635476314331
<br/>5267830527635582

**American Express (AMEX):**
<br/>370835069690353
<br/>343251075048467
<br/>343797433165708

**Discover:**
<br/>6011183306186386
<br/>6011736651339080
<br/>6011835681443662514
<br/>6011018732248916545
<br/>6011502901181543557

**JCB:**
<br/>3535480862374586
<br/>3544327118022627
<br/>3545269547809941591
<br/>3545947481155782997
<br/>3534629624130568739

**Diners Club - Carte Blanche:**
<br/>30414221492439
<br/>30126125053303
<br/>30082990586507

**Maestro:**
<br/>6304599538872293
<br/>6763523455463310
<br/>5038741670314479

**Visa Electron:**
<br/>4844552748017342
<br/>4026250086529305
<br/>4913215839480078

**InstaPayment:**
<br/>6398809037140762
<br/>6394392426182376
<br/>6398659574384251

Тестирование производилось в следующем окружении:
* Windows 10 64 bit
* Java 11.0.10