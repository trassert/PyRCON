# PyRCON

## EN
## Description
[RCON protocol](https://wiki.vg/RCON ) asynchronously in Python.

- `async_mcrcon.py ` this is the asynchronous version [mcrcon.py](https://github.com/barneygale/MCRcon/blob/master/mcrcon.py )

## Usage
```python
from async_mcrcon import MinecraftClient

async with MinecraftClient('1.3.3.7', 25575, 'password') as mc:
  output = await mc.send('list')
  print(output)
```

If you are using this module, please put an star! ;)

## Necessary
**Python 3.5 or higher**

## My server is [Luminto](https://t.me/lumintomc)
**The bot there uses this module!**

## RU

## Описание
[RCON protocol](https://wiki.vg/RCON) в асинхронном виде на языке Python.

- `async_mcrcon.py` это асинхронная версия [mcrcon.py](https://github.com/barneygale/MCRcon/blob/master/mcrcon.py)

## Использование
```python
from async_mcrcon import MinecraftClient

async with MinecraftClient('1.3.3.7', 25575, 'password') as mc:
  output = await mc.send('list')
  print(output)
```
Если вы используете этот модуль, поставьте звёздочку! ;)

## Необходимо
**Python 3.5 или выше**

## Мой сервер - [Luminto](https://t.me/lumintomc)
**Бот там использует этот модуль!**
