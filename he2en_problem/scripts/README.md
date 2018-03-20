Для воспроизведения результатов нужно просто запустить скрипт, запускающий процесс транслитерации с нуля, от обучения модели до измерения качества:
```sh
./run_all.sh
```
Cкрипт, который из сырых данных генерирует данные для t2t модели:
```sh
./run_datagen.sh
```
Cкрипт, который запускает обучение модели:
```sh
./run_train.sh train_steps random_seed
```
Скрипт, который удаляет чекпоинты и другие артефакты предыдущего обучения модели:
```sh
./reset_model.sh
```
Скрипт, который запускает применение модели:
```sh
./run_eval.sh result_name
```