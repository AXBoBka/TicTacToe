# Крестики-нолики (Tic-Tac-Toe) на Java

Этот проект представляет собой консольную реализацию игры "Крестики-нолики" на Java.

## Инструкции по запуску

1. Убедитесь, что у вас установлена Java Development Kit (JDK) - всё тестировалось на 8 версии.
2. Склонируйте репозиторий:

    ```shell
    git clone https://github.com/your-username/TicTacToe.git
    ```
   
3. Перейдите в каталог проекта:

    ```shell
    cd TicTacToe
    ```

4. Соберите Сервер и Клиент.

    ```shell
    javac src/server/Server.java
    javac src/client/Client.java
    ```

5. Запустите Сервер и 2 экземпляра Клиента.

    ```shell
    java src.server.Server
    java src.client.Client
    java src.client.Client
    ```

## Инструкции по игре

1. Игра "Крестики-нолики" представляет собой игровое поле размером {BOARD_SIZE}x{BOARD_SIZE}.
2. Игроки ходят по очереди, ставя свои символы (PALYER_SYMBOL_1 или PALYER_SYMBOL_2) на пустые клетки игрового поля.
3. Целью игры является заполнить горизонталь, вертикаль или диагональ одним типом символов (PALYER_SYMBOL_1 или PALYER_SYMBOL_2).
4. Первый игрок, который сможет сделать это, выигрывает игру.
5. Если все клетки игрового поля заполнены, и нет ни одного победителя, игра заканчивается вничью.


[Note:] Class Constants - содержит переменные BOARD_SIZE, PALYER_SYMBOL_1, PALYER_SYMBOL_2 и другие.  
[Note:] Сервер ждёт подключения двух клиентов(игроков) и автоматически начинается игра(псевдослучайно выбирается игрок, которому передаётся ход)

## Демонстрация игры

![Скриншот игрового процесса](https://github.com/AXBoBka/TicTacToe/assets/60500497/ca360f41-d477-42a7-9b70-4ab15082b1da)


