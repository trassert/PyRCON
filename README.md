# PyRCON

![Issues](https://img.shields.io/github/issues-raw/trassert/PyRCON?color=c78aff&label=issues&style=for-the-badge)
![Contributors](https://img.shields.io/github/contributors/trassert/PyRCON?color=c78aff&label=contributors&style=for-the-badge)
![Lines](https://img.shields.io/endpoint?url=https://ghloc.vercel.app/api/trassert/PyRCON/badge?style=flat&logoColor=white&color=c78aff&style=for-the-badge)
![Commit Activity](https://img.shields.io/github/commit-activity/m/trassert/PyRCON?color=c78aff&label=commits&style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/trassert/PyRCON?color=c78aff&label=last%20commit&style=for-the-badge)

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
