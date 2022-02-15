## Fritzing

### Если была установлена старая версия, то удаляем её:

```
sudo apt update && sudo apt purge fritzing && sudo apt autoclean && sudo apt autoremove
```

### Установка:

```
cd ~/ ; git clone https://github.com/rurewa/Fritzing.git && cd Fritzing && cp ${HOME}/Fritzing/Fritzing.desktop ${HOME}/Рабочий\ стол/
```

### Обновление (beta):

```
cd ~ ; cd Fritzing/ && git pull
```