
# Нейронная сеть для дизаризации текста

## Описание
В представленном Ipynb файле представленна нейронная сеть, основная задача которой является сегментация текста по спикерам.
Данная сеть может решать задачу разделения аудиодорожки на временные отрезки, которые показывает когда начинает и заканчивает говорить спикер.
В ней заложена возможность транскрибирования аудиозаписи, данная нейронная сеть компанует все текста спикеров по таймингу.


## Технологии
Перечислите технологии, библиотеки и инструменты, которые использовались в проекте. Например:
- Python 3.10
- whisperx
- pyannote

## Установка
```bash
Первым делом загрузите:
!pip install --q git+https://github.com/m-bain/whisperx.git
!pip install typer==0.9.0
!pip install --upgrade typer

Далее импортируйте:
import whisperx
import gc

Примеры использования
Загрузите аудиозапись из репозитория, затем положить ссылку на нее в переменную (audio_file)

Copy code
В самом Ipynb файле представленно подробное описание каждого шага, вы можете переделать код под свою задачу
