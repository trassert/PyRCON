# PyRCON

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

## Необходимо
**Python 3.5 или выше**

## Мой сервер - t.me/trassert_server
**Бот там использует этот модуль!**
