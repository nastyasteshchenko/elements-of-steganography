# Elements of steganography

## Описание

Этот проект содержит реализацию LSB внедрения в изображения и извлечения из изображений сообщений.

## Запуск задания

Для запуска проекта (не через архив) можно прописать из корневой папки репозитория:

```bash
./gradlew run --console=plain
```

## Сборка задания

Для сборки и создания .jar файлов используйте Gradle задачу createJar. Выполните следующую команду, находясь в корневом
каталоге репозитория:

```bash
./gradlew createJar
```

Эта команда создаст .jar файл.

## Запуск .jar файлов

Для запуска выполните следующую команду из корневой папки
репозитория (для уже лежащего архива в папке проекта):

```bash
java -jar ./elements-of-steganography-1.0-SNAPSHOT.jar
```

Если же вы хотите запустить .jar, сгенерированный с помощью ранее описанной задачи ```./gradlew createTask```,
то тогда необходимо прописать из корневой папки репозитория:

```bash
java -jar ./build/libs/<имя-.jar>
```