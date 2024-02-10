# Práctica de Buffer Overflow

El archivo BufferOverflow.odt contiene la práctica de Heap Overflow.

# Evaluación de Cuestionarios

El archivo de Cuestionarios.pdf evalúa los cuestionarios y se elige en el que se usará en la práctica final.

# Instrucciones para Realizar los Tests

Para realizar las pruebas unitarias, descarga el archivo zip `lab2-unit-tests-AraGonFer-main (1).zip`. Dentro de este archivo encontrarás otro README con la explicación detallada de lo que debes hacer. Este es el resultado que debería salir.


[==========] Running 6 tests from 3 test suites.
[----------] Global test environment set-up.
[----------] 2 tests from wrapAddFunctionTest
[ RUN      ] wrapAddFunctionTest.NonWrappingNums
[       OK ] wrapAddFunctionTest.NonWrappingNums (0 ms)
[ RUN      ] wrapAddFunctionTest.WrappingNums
[       OK ] wrapAddFunctionTest.WrappingNums (0 ms)
[----------] 2 tests from wrapAddFunctionTest (0 ms total)

[----------] 2 tests from wrapMulFunctionTest
[ RUN      ] wrapMulFunctionTest.NonWrappingMulNums
[       OK ] wrapMulFunctionTest.NonWrappingMulNums (0 ms)
[ RUN      ] wrapMulFunctionTest.WrappingMulNums
[       OK ] wrapMulFunctionTest.WrappingMulNums (0 ms)
[----------] 2 tests from wrapMulFunctionTest (0 ms total)

[----------] 2 tests from wrapShiftFunctionTest
[ RUN      ] wrapShiftFunctionTest.NonWrappingMulBNums
[       OK ] wrapShiftFunctionTest.NonWrappingMulBNums (0 ms)
[ RUN      ] wrapShiftFunctionTest.WrappingMulBNums
[       OK ] wrapShiftFunctionTest.WrappingMulBNums (0 ms)
[----------] 2 tests from wrapShiftFunctionTest (0 ms total)

[----------] Global test environment tear-down
[==========] 6 tests from 3 test suites ran. (0 ms total)
[  PASSED  ] 6 tests.
