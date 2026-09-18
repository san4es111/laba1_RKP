# Лабораторная работа № 1 «Решение уравнения»
Морозов Александр
Б.ПИН.ИИ.26.16
Программа решает уравнения вида `A*x² + B*x + C = 0`.

## Файлы

- `main.py` — первая учебная программа из части 1;
- `mathtool.py` — основное приложение;
- `tests.txt` — полный набор тестов;
- `.gitignore` — исключения для Git;
- `control_questions.md` — ответы на контрольные вопросы.

## Запуск

```powershell
python mathtool.py
python mathtool.py --help
python mathtool.py solve
python mathtool.py solve -a 1 -b -3 -c 2
```

Проверить код возврата в PowerShell:

```powershell
$LASTEXITCODE
```

## Рекомендуемые коммиты

```powershell
git add main.py
git commit -m "Добавлена первая программа"
git add mathtool.py
git commit -m "Добавлено решение уравнений"
git add tests.txt README.md .gitignore control_questions.md
git commit -m "Добавлены тесты и документация"
git push
```
