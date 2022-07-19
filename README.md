<p align="center">
      <img src="Project Logo Url" width="726">
</p>

<p align="center">
   <img src="" alt="Unity Version">
   <img src="" alt="Game Version">
   <img src="" alt="License">
</p>

## О проекте 

В данном проекте реализована система автоматического сбора профильной информации с применением технологии BOLT.  При использовании профильных оптимизаций производительность компилятора Clang повышается до 30%, после сбора профиля необходимо передать его компилятору для повторной оптимизации, но во многих случаях перекомпиляция не возможна. BOLT – технология, которая решает эту проблему. BOLT позволяет получить существенное ускорение без перекомпиляции.  

## Документация

### BOLT:
- **-** **`BOLT`** - это оптимизатор пост-компоновки, разработанный для ускорения работы больших приложений.

### SQL30:
- **-** **`SQL30`** - это нуливое значение ORM(Object–relational mapping) для sqlite3 в Python.
- **-** **`ORM(Object–relational mapping)`** - это метод для преобразования данных  между типов систем с использованием объектно ориентированных языков программирования.
 
## Distribute

- [Service Name](Page Link)


## Developers

- [Delevoper Name](GitHub Profile Link)

## Установка
- **-** **` git clone https://github.com/facebookincubator/BOLT llvm-bolt`** - BOLT
-- **-** **`mkdir build`** - BOLT
-- **-** **`cd build`** - BOLT
-- **-** **`cmake -G Ninja ../llvm-bolt/llvm -DLLVM_TARGETS_TO_BUILD="X86;AArch64" -DCMAKE_BUILD_TYPE=Release -DLLVM_ENABLE_ASSERTIONS=ON -DLLVM_ENABLE_PROJECTS="clang;lld;bolt"`** - BOLT
-- **-** **`ninja`** - BOLT
- **-** **`pip install sql30`** - SQL30

## License
