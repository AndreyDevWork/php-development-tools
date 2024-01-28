# php-development-tools

## Инструкция по использованию PHP Tools

Этот инструмент предоставляет функциональность для форматирования кода с использованием Prettier и конфигурации
редактора. Следуйте указанным шагам для установки и настройки.

### Шаг 1: Клонирование репозитория

Выполните команду `git clone` для клонирования репозитория на вашем компьютере:

```bash
git clone https://github.com/ваш-проект.git
cd ваш-проект
```

### Шаг 2: Установка зависимостей

Используйте менеджер пакетов `pnpm` для установки необходимых зависимостей:

```bash
pnpm i
```

### Шаг 3: Настройка IDE (PhpStorm / IntelliJ / JetBrains IDE)

1. Откройте настройки (File, Settings).

2. Перейдите в раздел Plugins, выберите Marketplace, найдите Prettier, установите плагин и перезапустите IDE.

3. Откройте настройки, выполните поиск Prettier, выберите Prettier в левой навигации.

4. Убедитесь, что пакет Prettier был обнаружен автоматически, это должно быть что-то вроде
   myproject/node_modules/prettier.

5. Обновите Run for Files, чтобы включить .php, например: {\*_/_,\*}.{js,ts,jsx,tsx,php,json,scss,vue,md}.

6. Отметьте кнопку On Save, если вы хотите, чтобы форматирование файлов выполнялось при сохранении.

### Шаг 4: Удаление папки .git

Если вы хотите удалить историю репозитория, выполните следующие шаги:

```bash
rm -rf .git
```
