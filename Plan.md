# ***План тестирования приложения (Application testing plan)***
***
 
## Содержание (Table of contents)

1.  [Вступление (Introduction)](#Introduction)
2.  [Описание программного обеспечения (Software Description)](#SoftwareDescription)
3.  [Рамки проекта (Project framework)](#ProjectFramework)
4.  [План работы (Work plan)](#WorkPlan)
5.  [План и стратегия тестирования (Testing plan and strategy)](#Plan)
6.  [Ресурсы (Resources)](#Resources)
7.  [Перечень возможных рисков при тестировании (List of possible risks during testing)](#Risks)
8.  [Временная оценка процесса тестирования, в часах (Time evaluation of the testing process, in hours)](#Time)
9.  [Критерии оценки качества (Quality assessment criteria)](#Quality)

## ***Вступление (Introduction)***<a id ="Introduction"></a>

> Основная информация (Basic information):

  * В документе описаны методы тестирования и подходы, которые будут использоваться тестировщиком для тестирования приложения (The document describes the testing methods and approaches that will be used by the tester to test the application)
  * **Тестирование** - это деятельность, направленная на проверку функциональности сайта или приложения, проверку соответствия требованиям, обеспечение уверенности в качестве программного обеспечения (**Testing** is an activity aimed at checking the functionality of the site or application, checking compliance with the requirements, ensuring confidence in the quality of the software) 

> Цель (Purpose):

*  Определить существующую информацию о проекте и программных компонентах, подлежащих тестированию (Identify existing information about the project and software components
   to be tested)
*  Определить необходимые ресурсы для проведения работ по тестированию (Determine the necessary resources to carry out testing work)
*  Привести результаты тестирования (Provide the test results)

## ***Описание программного обеспечения (Software Description)*** <a id ="SoftwareDescription"></a>

> **Приложение предоставляет функционал по работе с претензиями хосписа и включает в себя (The application provides functionality for working with hospice claims and includes)**:
* Информацию о претензиях и функционал для работы с ними (Information about claims and functionality for working with them).
* Новостную сводку хосписа (The hospice news summary).
* Тематические цитаты (Thematic quotes).

## ***Рамки проекта (Project framework)*** <a id ="ProjectFramework"></a>

> В объем работ по тестированию сайта входит тестирование следующих
компонентов и функций (The scope of site testing includes testing of the following
components and functions):


- Блок "Новости" (The "News"
  Block)
- Блок "Заявки" (Block "Applications")
- Блок "Новости" (Block "News")
- Блок "О приложении" (Block "About the application")
- Блок цитат о хосписе (Block of quotes about the hospice)

## ***План работы (Work plan)*** <a id ="WorkPlan"></a>

1. Подготовка плана тестирования (Preparation of a test plan)
2. Составление чек листов, тест-кейсов и прочей документации (Compilation of checklists, test cases and other documentation)
3. Настройка необходимого окружения (Setting up the necessary environment)
4. Функциональное тестирование и отчеты об ошибках (Functional testing and bug reports)
5. Подготовка финального отчета (Preparation of the final report)

## ***План и стратегия тестирования (Testing plan and strategy)*** <a id ="Plan"></a>

**Основные типы тестирования, которые будут выполнены (The main types of testing that will be performed):**
* **Функциональное тестирование.** Цель данного вида тестирования убедиться, что приложение соответствует заявленным требованиям и в отсутствии критических или значимых ошибок (Functional testing. The purpose of this type of testing is to make sure that the application meets the stated requirements and that there are no critical or significant errors)
* Тестирование пользовательского интерфейса (User interface testing)
* Юзабилити-тестирование (Usability testing)
* Регрессионное тестирование (Regression testing)


**Обеспечение надлежащего качества целевой функциональности (Ensuring the proper quality of the target functionality):**
* Выполнить каждый сценарий, используя допустимые и недопустимые
  данные (Execute each scenario using valid and invalid
  data):
  * Ожидаемые результаты возникают при использовании верных
    данных (The expected results occur when using the correct
    data)
  * Неожидаемые результаты возникают при использовании неверных
    данных ( Unexpected results occur when using incorrect
    data)
* Все дымовые тесты пройдены ( All smoke tests have been passed)
* Нет блокирующих багов, все баги с высоким приоритетом поправлены (There are no blocking bugs, all bugs with high priority have been fixed)
* Тесты пройдены (Tests passed)

## ***Ресурсы (Resources)*** <a id ="Resources"></a>

**Перечень используемых устройств (List of devices used)**
 * PC (CPU: Intel Core i7-4710HQ, 2500 MHz, RAM 12 Gb, Win 10 x64)
 * Mobile Phone (Xiaomi Note 10, Android 12, RAM 8 Gb)

**Перечень используемых инструментов (List of tools used)**
 * Android Studio
 * Android API Emulator 29
 * Allure
 * Espresso 

## ***Перечень возможных рисков при тестировании (List of possible risks during testing)*** <a id ="Risks"></a>

* Отсутствие спецификации (No specification)
* Недостаточная квалификация тестировщика (Insufficient qualification of the tester)
* Высокая стоимость автоматизации и поддержания актуальности автотестов столь малого проекта (The high cost of automating and maintaining the relevance of autotests of such a small project)

## ***Временная оценка процесса тестирования, в часах (Time evaluation of the testing process, in hours)*** <a id ="Time"></a>

* Составление плана тестирования - 3 часа (Preparation of a test plan - 3 hours)
* Составление чек-листа - 5 часов (Drawing up a checklist - 5 hours)
* Подготовка тест-кейсов - 10 часов (Preparation of test cases - 10 hours)
* Подготовка проекта (настройка окружения) - 2 часа (Project preparation (environment setup) - 2 hours)
* Написание автоматизированных тестов -30 часов (Writing automated tests -30 hours)
* Проведение автоматизированного тестирования - 2 часа (Automated testing - 2 hours)
* Формирование отчета о тестировании - 2 часа (Test report generation - 2 hours)

## ***Критерии оценки качества (Quality assessment criteria)*** <a id ="Quality"></a>

* Продукт должен работать (The product should work)
* Продукт не должен содержать критических и блокирующих дефектов в окончательной версии проекта (The product must not contain critical and blocking defects in the final version of the project)

