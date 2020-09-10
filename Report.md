# Отчёт о тестировании KeyValidator

## Краткое описание:

09.09.2020 было проведено тестирование документации, тестирование установки, тестирование сборки, функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
1. [Приложение KeyValidator не совместимо с Java 11](https://github.com/Dmitrii4/Task-1-KeyValidator/issues/1)
2. Обнаружены невалидные ключи для проверки:
   * 80b427f8-92cd-3aae-ba04-3927fbe17c6 
   * 387eedc6-12e9-3b32-9881-63b6b5e85317
3. Обнаружен валидный ключ для проверки:
   * 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорты
* Тестовая документация

В качестве тестовых данных использовались данные [отсюда](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
######Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
######Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

####Тестирование производилось в следующем окружении:
* Windows 7 x64
* IntelliJ IDEA 2020.2.1
* openjdk version "1.8.0_265"
  OpenJDK Runtime Environment (AdoptOpenJDK)(build 1.8.0_265-b01)
  OpenJDK 64-Bit Server VM (AdoptOpenJDK)(build 25.265-b01, mixed mode)
* openjdk version "11.0.8" 2020-07-14
  OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
  OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)

