# Mention Highlight (Fabric 1.21.4)

Если в чате кто-то пишет твой ник — фон этого сообщения становится красным.
Свои сообщения (где ты автор: `<Nick>`, `Nick:`, `Nick »`) не подсвечиваются.

## Сборка .jar

Нужны JDK 21 и Gradle 8.12+.

    gradle build

Готовый файл: `build/libs/mention-highlight-1.0.0.jar` (не берите `-sources`).
Кладите его в `.minecraft/mods` рядом с Fabric Loader 0.16+.
Fabric API не требуется.

## Без установки чего-либо

Залейте папку в новый репозиторий на GitHub — вкладка Actions → Build mod →
после сборки скачайте артефакт `mention-highlight-jar`.
