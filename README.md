## Создание extensions_pack
- открыть терминал
- создать/перейти в директорию tmp, которая будет рутовая для extensions_pack
- ввести команду yo code и следовать указанием
- изменить в директории tmp файл package.json:
- добавить "publisher"
- изменить в директории tmp файл README.md
- ввести  vsce package ( появиться файл extensions_pack-версия.vsix )

## Установка extensions_pack
- скачать файл extensions_pack-версия.vsix
- выполнить code --install-extension extensions_pack-версия.vsix в VS Code [ Ctrl + ` ] или в стандартном терминале

## Список расширений
- git extension pack
- TODO Highlight v2
- Prettier
- Trailing Spaces
- YAML
- JSON
- XML
- Swagger Viewer
- PostgreSQL
- Oracle Developer Tools for VS Code (требуется установка https://www.oracle.com/database/technologies/appdev/dotnet/install-dotnetcore-windows.html)
- SQL Formatter
- docker (требуется установка Docker)
- kubernetes (требуется установка https://kubernetes.io/ru/docs/tasks/tools/install-kubectl/)
- Language Support for Java(TM) by Red Hat
- Gradle Language Support
- Spring Boot Extension Pack
- Remote Development