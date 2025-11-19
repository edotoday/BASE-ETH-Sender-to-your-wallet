# BASE-ETH-Sender-to-your-wallet
Python-скрипт для отправки ETH в сети Base. 
Читает приватные ключи из private.txt, адреса получателей из recipients.txt и прокси из proxy.txt (опционально) 
Проверяет баланс, отправляет транзакции с учетом газа и случайными задержками. Т
ребуются библиотеки web3.py и requests. 
Настройте RPC-URL, газ и файлы перед запуском.

Установка:Установите Python 3.6+ и библиотеки: pip install web3 requests.


Запустите: python main.py 

Внимание: Храните private.txt в безопасности. Тестируйте в тестовой сети Base (например, Sepolia) перед mainnet

