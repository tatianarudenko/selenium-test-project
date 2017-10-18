# selenium-test-project

### How this template was created
This template was generated with following command:
```
mvn archetype:generate -DgroupId=com.mycompany.selenium -DartifactId=selenium-test-project -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```
Afterwards, following was added:
* Selenium and TestNg dependencies into pom.xml
* .gitignore file for not git tracking unnecessary files, which we don\`t want to commit
* Test resources folder into _src/test_. Also marked as "Test Resources" in IDEA
* Added drivers into _src/test/resources_ folder. **NOTE** - it might be needed to update the driver versions



### Task:
1. Открыть браузер и развернуть на весь экран.
2. Зайти на ss.com.
3. Поменять язык на русский.
4. в поиске ввести искомую фразу (напр. Компьютер....)
5. выбрать разные параметры поиска.
6. Нажать кнопку Искать
7. удостовериться что отображается хотя бы одно объявление

---

8. Отсортировать результаты по цене и выбрать закладку ‘продажа’.
9. Зайти в расширенный поиск.
10. Задать параметр поиска по цене от 0 до 300.
11. Выбрать не менее 3 любых объявлений.
12. Нажать кнопку Показать выбранные объявления. (proveritj chto cifra v skobkah praviljanaja)
13. Проверить, что объявления на странице совпадают с выбранными ранее

**NOTE** - 
1. Think about - how to make the tests Small, Atomic (One test - one clear goal, TC should verify only one functionality) and Autonomous. In order to do that, examine
 * how many features are tested
 * can or should those features be divided into separate test
2. Try to use CSS Selectors instead of XPath
---

