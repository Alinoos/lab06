# lab06
$ mkdir lab06
$ cd lab06
$ git init
Инициализирован пустой репозиторий Git в /home/alina/lab06/.git/
$ git add .
$ git commit -m "lab04"
[master (корневой коммит) 6e68793] lab04
 103 files changed, 7108 insertions(+)
 create mode 100644 .github/workflows/Linux.yml
 create mode 100644 .github/workflows/Windows.yml
 create mode 100644 formatter_ex_lib/CMAkeLIsts.txt
 create mode 100644 formatter_ex_lib/CMakeLists.txt
 create mode 100644 formatter_ex_lib/_build/CMakeCache.txt
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CMakeCCompiler.cmake
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CMakeCXXCompiler.cmake
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CMakeDetermineCompilerABI_C.bin
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CMakeDetermineCompilerABI_CXX.bin
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CMakeSystem.cmake
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CompilerIdC/CMakeCCompilerId.c
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CompilerIdC/a.out
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CompilerIdCXX/CMakeCXXCompilerId.cpp
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/3.22.1/CompilerIdCXX/a.out
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/CMakeDirectoryInformation.cmake
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/CMakeOutput.log
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/Makefile.cmake
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/Makefile2
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/TargetDirectories.txt
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/cmake.check_cache
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/DependInfo.cmake
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/build.make
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/cmake_clean.cmake
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/cmake_clean_target.cmake
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/compiler_depend.make
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/compiler_depend.ts
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/depend.make
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/flags.make
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/formatter_ex.cpp.o
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/formatter_ex.cpp.o.d
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/link.txt
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/formatter_ex.dir/progress.make
 create mode 100644 formatter_ex_lib/_build/CMakeFiles/progress.marks
 create mode 100644 formatter_ex_lib/_build/cmake_install.cmake
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/DependInfo.cmake
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/build.make
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/cmake_clean.cmake
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/cmake_clean_target.cmake
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/compiler_depend.make
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/depend.make
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/flags.make
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/formatter.cpp.o
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/formatter.cpp.o.d
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/link.txt
 create mode 100644 formatter_ex_lib/_build/formatter/CMakeFiles/formatter.dir/progress.make
 create mode 100644 formatter_ex_lib/_build/formatter/cmake_install.cmake
 create mode 100644 formatter_ex_lib/_build/libformatter_ex.a
 create mode 100644 formatter_ex_lib/formatter_ex.cpp
 create mode 100644 formatter_ex_lib/formatter_ex.h
 create mode 100644 formatter_lib/CMakeLists.txt
 create mode 100644 formatter_lib/_build/CMakeCache.txt
 create mode 100644 formatter_lib/_build/CMakeFiles/CMakeDirectoryInformation.cmake
 create mode 100644 formatter_lib/_build/CMakeFiles/Makefile.cmake
 create mode 100644 formatter_lib/_build/CMakeFiles/Makefile2
 create mode 100644 formatter_lib/_build/CMakeFiles/TargetDirectories.txt
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/DependInfo.cmake
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/build.make
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/cmake_clean.cmake
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/cmake_clean_target.cmake
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/compiler_depend.make
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/compiler_depend.ts
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/depend.make
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/flags.make
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/formatter.cpp.o
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/formatter.cpp.o.d
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/link.txt
 create mode 100644 formatter_lib/_build/CMakeFiles/formatter.dir/progress.make
 create mode 100644 formatter_lib/_build/CMakeFiles/progress.marks
 create mode 100644 formatter_lib/_build/cmake_install.cmake
 create mode 100644 formatter_lib/formatter.cpp
 create mode 100644 formatter_lib/formatter.h
 create mode 100644 hello_world_application/CMakeLists.txt
 create mode 100644 hello_world_application/_build/CMakeCache.txt
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/CMakeDirectoryInformation.cmake
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/DependInfo.cmake
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/build.make
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/cmake_clean.cmake
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/compiler_depend.internal
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/compiler_depend.make
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/depend.make
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/flags.make
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/formatter_ex.cpp.o
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/formatter_ex.cpp.o.d
 create mode 100644 hello_world_application/_build/formatter_ex/CMakeFiles/progress.marks
 create mode 100644 hello_world_application/_build/formatter_ex/cmake_install.cmake
 create mode 100644 hello_world_application/_build/formatter_ex/libformatter_ex.a
 create mode 100644 hello_world_application/hello_world.cpp
 create mode 100644 solver_application/CMAkeLists.txt
 create mode 100644 solver_application/CMakeLists.txt
 create mode 100644 solver_application/_build/CMakeCache.txt
 create mode 100644 solver_application/_build/formatter_ex/CMakeFiles/CMakeDirectoryInformation.cmake
 create mode 100644 solver_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/cmake_clean.cmake
 create mode 100644 solver_application/_build/formatter_ex/CMakeFiles/formatter_ex.dir/flags.make
 create mode 100644 solver_application/_build/formatter_ex/CMakeFiles/progress.marks
 create mode 100644 solver_application/_build/formatter_ex/cmake_install.cmake
 create mode 100644 solver_application/_build/formatter_ex/libformatter_ex.a
 create mode 100644 solver_application/equation.cpp
 create mode 100644 solver_lib/CMakeLists.txt
 create mode 100644 solver_lib/_build/CMakeCache.txt
 create mode 100644 solver_lib/_build/CMakeFiles/TargetDirectories.txt
 create mode 100644 solver_lib/_build/cmake_install.cmake
 create mode 100644 solver_lib/solver.cpp
 create mode 100644 solver_lib/solver.h
$ git remote add origin https://github.com/Alinoos/lab06.git
$ git push origin master
Username for 'https://github.com': Alinoos
Password for 'https://Alinoos@github.com': 
Перечисление объектов: 115, готово.
Подсчет объектов: 100% (115/115), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (105/105), готово.
Запись объектов: 100% (115/115), 45.64 КиБ | 3.51 МиБ/с, готово.
Всего 115 (изменений 37), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
remote: Resolving deltas: 100% (37/37), done.
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Alinoos/lab06/pull/new/master
remote: 
To https://github.com/Alinoos/lab06.git
 * [new branch]      master -> master
$ cd formatter_lib
$ nano CMakeLists.txt
$ cd ..
alina@alina-Vostro-5402:~/lab06$ cd formatter_ex_lib
$ nano CMakeLists.txt
$ cd ..
$ cd formatter_lib
$ nano CMakeLists.txt
$ cd ..
$ cd solver_application
$ nano CMakeLists.txt
$ cd ..
$ nano CMakeLists.txt
$ git add .
$ git commit -m "CMake for all"
[master 091bcd7] CMake for all
 4 files changed, 55 insertions(+), 35 deletions(-)
 create mode 100644 CMakeLists.txt
 rewrite formatter_ex_lib/CMakeLists.txt (98%)
 rewrite solver_application/CMakeLists.txt (98%)
$ git push origin master
Username for 'https://github.com': Alinoos
Password for 'https://Alinoos@github.com': 
Перечисление объектов: 14, готово.
Подсчет объектов: 100% (14/14), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (9/9), готово.
Запись объектов: 100% (9/9), 1.37 КиБ | 1.38 МиБ/с, готово.
Всего 9 (изменений 5), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
remote: Resolving deltas: 100% (5/5), completed with 4 local objects.
To https://github.com/Alinoos/lab06.git
   6e68793..091bcd7  master -> master
$ cat >> CPackConfig.cmake << EOF
> EOF
$ nano CPackConfig.cmake
$ git add .
$ git commit -m "CPack"
[master 698bebc] CPack
 1 file changed, 25 insertions(+)
 create mode 100644 CPackConfig.cmake
$ git push origin master
Username for 'https://github.com': Alinoos
Password for 'https://Alinoos@github.com': 
Перечисление объектов: 4, готово.
Подсчет объектов: 100% (4/4), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (3/3), готово.
Запись объектов: 100% (3/3), 676 байтов | 676.00 КиБ/с, готово.
Всего 3 (изменений 1), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Alinoos/lab06.git
   091bcd7..698bebc  master -> master
$ cd .github
$ cd workflows
$ nano Action.yml
$ git add .
$ git commit -m "Action"
[master 2513cd5] Action
 1 file changed, 22 insertions(+)
 create mode 100644 .github/workflows/Action.yml
$ git push origin master
Username for 'https://github.com': Alinoos
Password for 'https://Alinoos@github.com': 
Перечисление объектов: 8, готово.
Подсчет объектов: 100% (8/8), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (4/4), готово.
Запись объектов: 100% (5/5), 606 байтов | 606.00 КиБ/с, готово.
Всего 5 (изменений 1), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Alinoos/lab06.git
   698bebc..2513cd5  master -> master
$ nano Realease.yml
$ git add .
$ git commit -m "Realease"
[master d63b2a6] Realease
 1 file changed, 38 insertions(+)
 create mode 100644 .github/workflows/Realease.yml
$ git push origin master
Username for 'https://github.com': Alinoos
Password for 'https://Alinoos@github.com': 
Перечисление объектов: 8, готово.
Подсчет объектов: 100% (8/8), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (4/4), готово.
Запись объектов: 100% (5/5), 847 байтов | 847.00 КиБ/с, готово.
Всего 5 (изменений 1), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Alinoos/lab06.git
   2513cd5..d63b2a6  master -> master
$ cd ..
$ cd ..
$ nano DESCRIPTION
$ nano LICENSE
$ git add LICENSE
$ git add DESCRIPTION
6$ git commit -m "LIC DESC"
[master 7643b18] LIC DESC
 2 files changed, 202 insertions(+)
 create mode 100644 DESCRIPTION
 create mode 100644 LICENSE
$ git push origin master
Username for 'https://github.com': Alinoos
Password for 'https://Alinoos@github.com': 
Перечисление объектов: 5, готово.
Подсчет объектов: 100% (5/5), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (3/3), готово.
Запись объектов: 100% (4/4), 4.21 КиБ | 4.21 МиБ/с, готово.
Всего 4 (изменений 1), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Alinoos/lab06.git
   d63b2a6..7643b18  master -> master
