# Настройка линтера

## Что используется

- `pylint` для Python

## Быстрая настройка

```bash
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements-dev.txt
```

После этого в VS Code:

1. Откройте проект.
2. Выберите интерпретатор `.venv`.
3. Убедитесь, что установлено расширение `fnando.linter`.
4. Перезагрузите окно VS Code.

## Если не подсвечивает

- Откройте `View -> Output`
- Выберите канал `linter`
- Проверьте, видит ли VS Code `${workspaceFolder}/.venv/bin/pylint`
