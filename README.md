# Bot de Soporte Técnico - UTN TUP
## Organización Empresarial - Trabajo Práctico Integrador

## Descripción
Chatbot desarrollado en Python para Telegram que automatiza el proceso de soporte técnico nivel 1 de una organización. El bot permite registrar tickets de soporte, validar empleados y asignar prioridades automáticamente.

## Tecnologías utilizadas
- Python 3.14
- python-telegram-bot 22.7
- openpyxl 3.1.5
- Google Sheets / Excel (base de datos simulada)

## Cómo ejecutarlo
1. Clonar el repositorio
2. Instalar dependencias: pip install python-telegram-bot openpyxl
3. Ejecutar: python bot.py
4. Abrir Telegram y buscar @soporte_tecnico_utn_bot
5. Escribir /start para iniciar

## Comandos
- /start - Inicia el proceso de registro de ticket
- /cancelar - Cancela la operación en curso

## Estructura del proyecto
- bot.py - Código principal del chatbot
- Base de datos.xlsx - Base de datos simulada con empleados y tickets
- token.txt - Token de acceso a la API de Telegram
