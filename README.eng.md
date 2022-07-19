<p align="center">
      <img src="Project Logo Url" width="726">
</p>

## About

About Text Here

## Documentation

### BOLT:
-  **`BOLT`** - это оптимизатор пост-компоновки, разработанный для ускорения работы больших приложений.

### SQL30:
-  **`SQL30`** - это нуливое значение ORM(Object–relational mapping) для sqlite3 в Python.
-  **`ORM(Object–relational mapping)`** - in computer science is a programming technique for converting data between type systems using object-oriented programming languages. This creates, in effect, a "virtual object database" that can be used from within the programming language. 
### Systemd:
-  **`Systemd`** - это менеджер демонов в Linux. Этот демон позволяет управлять запуском сервисов и обеспечивает такие функции, как мониторинг и логирование.

## Installation
### BOLT:
    > ` git clone https://github.com/facebookincubator/BOLT llvm-bolt`
    >`mkdir build`
    > `cd build`
    > `cmake -G Ninja ../llvm-bolt/llvm -DLLVM_TARGETS_TO_BUILD="X86;AArch64" -DCMAKE_BUILD_TYPE=Release -DLLVM_ENABLE_ASSERTIONS=ON -DLLVM_ENABLE_PROJECTS="clang;lld;bolt"`
    > `ninja`

### SQL30:
-  **`pip install sql30`**

### Systemd:
    > `apt-get update -y`
    > `apt-get install -y systemd`


## Developers

- [Amir Ayupov](https://github.com/aaupov)
- [Maxim Shcherbakov](https://github.com/M4RFF)

## License
Project Linux-perfd is distributed under the MIT license.
