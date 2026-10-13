🚗 FuelApp
🇷🇺 Русский | 🇬🇧 English

🇷🇺 FuelApp — Учет заправок автомобиля
FuelApp — это легкое веб-приложение для удобного ведения учета заправок, расхода топлива и расходов на ваш автомобиль.

✨ Основные возможности
📊 Отслеживание истории заправок и расходов.

⚡ Автоматическая установка и настройка системных зависимостей через один скрипт.

⚙️ Интеграция с systemd для автозапуска и работы в фоновом режиме.

🔒 Авторизация и разграничение доступа.

🚀 Быстрая установка
Создайте директорию для установки и перейдите в нее:

Bash
cd /opt && sudo mkdir -p fuelapp_install && cd fuelapp_install
Загрузите файл fuelapp.sh в эту директорию (например, через SFTP).

Сделайте скрипт исполняемым и запустите его:

Bash
chmod +x fuelapp.sh
./fuelapp.sh
🛠️ Управление приложением
При запуске скрипта ./fuelapp.sh откроется удобное консольное меню:

Plaintext
==================================================
                    FUEL CONTROL
               Управление приложением
==================================================

  1. Установить / обновить
  2. Показать статус
  3. Перезапустить
  4. Удалить
  5. Выход

Выберите действие [1-5]:
Процесс установки:
Выберите пункт 1 (Установить / обновить).

Укажите желаемый порт (по умолчанию: 5000).

Скрипт автоматически подготовит Python-окружение, установит зависимости, настроит шаблоны интерфейса, конфигурацию и сервис systemd.

🌐 Вход в систему
После завершения установки откройте браузер и перейдите по адресу:

Plaintext
http://<IP_ВАШЕГО_СЕРВЕРА>:<ПОРТ>
Логин по умолчанию: admin

Пароль по умолчанию: admin

⚠️ ВАЖНО: После первого входа обязательно смените пароль в разделе «Настройки»!

📸 Скриншоты интерфейса
💖 Поддержать разработку
Если вам нравится проект и вы хотите поддержать его развитие:

💳 Карты РФ / СБП / Tinkoff Pay:

👉 Поддержать через CloudTips

🇬🇧 FuelApp — Car Fuel Tracking App
FuelApp is a lightweight web application designed for convenient tracking of refueling history, fuel consumption, and car maintenance expenses.

✨ Key Features
📊 Track refueling history and expenses.

⚡ Automatic installation and configuration of system dependencies via a single script.

⚙️ Integration with systemd for auto-start and background execution.

🔒 Authentication and access control.

🚀 Quick Installation
Create an installation directory and navigate to it:

Bash
cd /opt && sudo mkdir -p fuelapp_install && cd fuelapp_install
Upload the fuelapp.sh script to this directory (e.g., via SFTP).

Make the script executable and run it:

Bash
chmod +x fuelapp.sh
./fuelapp.sh
🛠️ Application Management
Running the ./fuelapp.sh script will open a convenient console menu:

Plaintext
==================================================
                    FUEL CONTROL
                Application Management
==================================================

  1. Install / Update
  2. Show Status
  3. Restart
  4. Uninstall
  5. Exit

Select an action [1-5]:
Installation Process:
Select option 1 (Install / Update).

Specify the desired port (default: 5000).

The script will automatically prepare the Python environment, install dependencies, set up interface templates, configuration, and the systemd service.

🌐 Logging In
Once the installation is complete, open your browser and navigate to:

Plaintext
http://<YOUR_SERVER_IP>:<PORT>
Default Username: admin

Default Password: admin

⚠️ IMPORTANT: After your first login, make sure to change your password in the "Settings" section!

📸 Screenshots
💖 Support the Project
If you like this project and want to support its development:

💳 Support via CloudTips:

👉 Donate via CloudTips
