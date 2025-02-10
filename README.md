# ALT Atomic

Базовый образ **ALT Linux** в виде OCI-изображения, совместимый с **bootc**.

Данный образ специально создан минималистичным, его можно использовать для сборки атомарных дистрибутивов, аналогичных **Fedora Silverblue**, **Vanilla OS** и других.

Внутри отсутствует рабочий стол (DE) и некоторые дополнительные утилиты, но присутствует ядро и полезные инструменты для контейнеров, такие как:

- **Flatpak**
- **Distrobox**
- **Podman**
- **Docker**

С полным списком пакетов можно ознакомиться в файле **/src/packages/01-package-list.sh**

Известные проекты построенный на его основе:
- ** https://github.com/alt-gnome/alt-atomic **