# Diplom_1

Учебный проект по покрытию кода Unit тестами. 

## Описание

Версия Java 11.

Проект использует следующие библиотеки:
- JUnit 4
- Mockito
- Jacoco

### Запуск Unit тестов

Для запуска тестов необходимо:

1. Скачать код

 ```sh
   git clone https://github.com/ManaskinaTatyanaSergeevna/Diplom_1.git
   ```

2. Для создания отчета в Jacoco ввести команду

```sh
mvn clean verify
```

Отчет будет находиться в target/site/jacoco/index.html

### Структура проекта

```bash
.gitignore
pom.xml
README.md
src
   |-- main
   |   |-- java
   |   |   |-- praktikum
   |   |   |   |-- Bun.java
   |   |   |   |-- Burger.java
   |   |   |   |-- Database.java
   |   |   |   |-- Ingredient.java
   |   |   |   |-- IngredientType.java
   |   |   |   |-- Praktikum.java
   |   |-- resources
   |   |   |-- read.me
   |-- test
   |   |-- java
   |   |   |-- BunMockTest.java
   |   |   |-- BunParameterizedTest.java
   |   |   |-- BurgerTest.java
   |   |   |-- DatabaseTest.java
   |   |   |-- IngredientMockTest.java
   |   |   |-- IngredientParameterizedTest.java
   ```
