# Firmware ESP32 (Wokwi)

Proyecto Wokwi: https://wokwi.com/projects/480449645373943809

- `sketch.ino`: lectura DHT22 (GPIO 4) y relé (GPIO 5), envío HTTPS con `Authorization: Bearer`.
- `diagram.json` y `libraries.txt`: circuito y librerías del proyecto.
- `secrets.h`: NO se versiona (ver `.gitignore`). Crear con `SECRET_WIFI_SSID`, `SECRET_WIFI_PASS`,
  `SECRET_SERVER_URL` y `SECRET_API_TOKEN`.
