# Using SEGGER RTT on STM32 Nucleo Board

Real Time Terminal (SEGGER RTT), can send real time messages to the host system even while debugging.<br>
To see the messages on host, JLinkRTTViewer can be used.

## Requirements:
- STM32F767 NUCLEO-144 Development Board<br>
    ST-Link should be upgraded to run as JLink.<br>

- JLinkRTTViewer<br>
    This application can be used on Host to see the incoming messages from Jlink.

## Working Principle
When application starts running Blue LED will start blinking each 500 ms.<br>
Red LED will be toggled after user's each press on button.<br>
"Hello from STM32 Nucleo -> Segger_RTT\r\n" message will be seen on JLinkRTTViewer each 500 ms.<br>
Note: Project is developped with CubeIDE.

