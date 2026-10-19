# Architecting-LR1

Упаковал java-приложение из примера в докер через команду
docker build ./ -t "java_app"
И проверил создался ли образ командой docker images -a:
![alt text](images/image.png)

Запушил в реестр образов
![alt text](images/image-1.png)

Запустил compose:
![alt text](images/image-2.png)

Проверил, работает ли приложение в compose:
![alt text](images/image-3.png)