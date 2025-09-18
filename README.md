# NetworkAssistantBot v2

Бот предназначен для сетевых администраторов и инженеров связи, чтобы упростить рутинные задачи мониторинга и диагностики.

# Возможности бота
Интеграция NetBox с LibreNMS через Telegram бот:
- Netbox-источник истины
- LibreNMS-система мониторинга

# Логика работы
- При появлении устройства в Netbox оно появится в LibreNMS после подтверждения в Telegram
- При удаления устройства в Netbox оно удалится в LibreNMS после подтверждения в Telegram
- Происходит постоянное сравнение устройств между LibreNMS и Netbox
- При появлении устройства в LibreNMS администратор решает добавить его или нет. Netbox - источник истины!

# Подготовка инфраструктуры
- Установить Netbox https://netboxlabs.com/docs/netbox/installation/ 
- Установить LibreNMS https://docs.librenms.org/Installation/Install-LibreNMS/

# Установка зависимостей

# Запуск программы

# Запуск Docker


