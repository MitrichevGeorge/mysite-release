# mysite-release
release of informaticks analog
[презентация здесь](https://1drv.ms/p/c/577f8842769e83ec/EWZwGBfyOYNAshQ2HTcExCYBpPUdv57X9R4SF1E97ap_gQ?e=zJh6PO)

# Установка:
### 1.Установите git (если у Вас его ещё нет):
 - Перейдите на [официальный сайт](https://git-scm.com/downloads)
 - Скачайте и установите git
### 2.Клонируйте репозиторий:
- ```powershell
  git clone https://github.com/MitrichevGeorge/mysite-f.git
  ```
- ```powershell
  cd mysite-f
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
