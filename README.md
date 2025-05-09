# mysite-release
release of informaticks analog

# Установка:
### 1.Установите git (если у Вас его ещё нет):
 - Перейдите на [официальный сайт](https://git-scm.com/downloads)
 - Скачайте и установите git
### 2.Клонируйте репозиторий:
- ```powershell
  git clone https://github.com/MitrichevGeorge/mysite-release.git
  ```
- ```powershell
  cd mysite-release/mysite
  ```
### 3.Подготовка
- установите необходимые библиотеки:
  ```powershell
  pip install flask flask_login requests cssutils bleach psutil
  ```
- или используйте venv:
   - для powershell
     ```powershell
     win-env\Scripts\activate.ps1
     ```
   - для cmd
     ```bash
     win-env\Scripts\activate.bat
     ```
### 4.Запуск
```powershell
python run.py
```
