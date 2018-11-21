# Сборка проекта при помощи cmake
**Cmake** - тоже утилита для сборки проектов. Она читает файл **CMakeLists.txt**. Генерирует на его основе **Makefile** и затем уже собирает проект при помощи **make**. 

```bash
mkdir build # создаем временный каталог в котором будет производиться сборка
cd build # переходим в него
cmake .. # запускаем cmake с указанием каталога с CmakeLists.txt, для создания Makefile
make # запускаем make для сборки проекта
```

# Едем дальше
Переходим в бранч [hello-conan](https://github.com/460s/meeting_backend/tree/hello-conan)
