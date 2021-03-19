FROM debian:latest

# Информация:
LABEL maintainer="VolkovRA"
LABEL description="Event emitter service"

# Создание директории приложения
WORKDIR /usr/src/app

# Порты:
EXPOSE 80/tcp

# Копируем файлы приложения:
COPY bin/service.bin bin/service.bin

# Точка входа:
CMD ["bin/service.bin"]