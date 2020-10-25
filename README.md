# Клонирования:

`git clone https://github.com/netBriler/simple-cryptor`

# Установка зависимостей:

`pip install -r requirements.txt`

# Использование
Чтобы закриптовать/раскриптовать файлы, нужно переместить их в директорию `/result`

# Закриптовать

После чего запустить файл `crypt.py`, он создаст 2 ключа (если нету):

`python crypt.py` - закриптовать

1 приватный `private.pem` (нельзя никому передавать, он нужен для раскриптовки)

2 публичный `receiver.pem` (можно кому угодно передавать, он нужен для криптовки)

# Разкриптовать

Чтобы разкриптовать нужно чтобы в главной директории возле скриптов был приватный файл `private.pem`

Запускаем файл и `decrypt.py` и все файлы в директорию `/result` раскриптованы

`python crypt.py` - раскриптовать