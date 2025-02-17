# admcode_tp1_Ex07
# Resultados Test:
a/Local/Microsoft/WindowsApps/python3.10.exe "c:/Users/lucag/OneDrive/Escritorio/Facu/Francia/CPE/Administration Système et gestion de codes1/EJ7/calculator_package/test/test_complex_calculator.py"
test_division_por_cero (__main__.TestSimpleComplexCalculator)
Prueba la división por cero. ... 2025-02-17 06:37:13,918 - ERROR - Error de división: El denominador es cero.
2025-02-17 06:37:13,918 - ERROR - Error de división: No se puede dividir por cero
2025-02-17 06:37:13,918 - INFO - Pruebas completadas.
ok
test_division_valida (__main__.TestSimpleComplexCalculator)
Prueba una división válida. ... 2025-02-17 06:37:13,921 - INFO - División exitosa: [1, 1] / [1, 0] = [1.0, 1.0]
2025-02-17 06:37:13,921 - INFO - Pruebas completadas.
ok
test_entradas_invalidas (__main__.TestSimpleComplexCalculator)
Prueba el manejo de entradas inválidas. ... 2025-02-17 06:37:13,921 - ERROR - Los argumentos deben ser listas, pero se recibieron tipos incorrectos.
2025-02-17 06:37:13,921 - ERROR - Error al sumar no lista y [4, 5]: Los argumentos deben ser listas
2025-02-17 06:37:13,921 - ERROR - Todos los elementos deben ser números enteros o flotantes.
2025-02-17 06:37:13,921 - ERROR - Error al sumar [1, 'a'] y [4, 5]: Todos los elementos deben ser números enteros o flotantes
2025-02-17 06:37:13,921 - ERROR - Los números complejos deben ser listas de dos elementos.
2025-02-17 06:37:13,921 - ERROR - Error al sumar [1] y [4, 5]: Los números complejos deben ser listas de dos elementos     
2025-02-17 06:37:13,921 - INFO - Pruebas completadas.
ok
test_formato_complejo (__main__.TestSimpleComplexCalculator)
Prueba el formateo de números complejos. ... 2025-02-17 06:37:13,921 - ERROR - Los elementos de [1, 'a'] deben ser números enteros o flotantes.
2025-02-17 06:37:13,925 - ERROR - Formato inválido para número complejo: [1]
2025-02-17 06:37:13,925 - ERROR - Formato inválido para número complejo: no lista
2025-02-17 06:37:13,925 - INFO - Pruebas completadas.
ok
test_operaciones_con_enteros (__main__.TestSimpleComplexCalculator)
Prueba las operaciones básicas con números enteros. ... 2025-02-17 06:37:13,925 - INFO - Suma exitosa: [4, 5] + [2, 3] = [6, 8]
2025-02-17 06:37:13,925 - INFO - Resta exitosa: [4, 5] - [2, 3] = [2, 2]
2025-02-17 06:37:13,925 - INFO - Multiplicación exitosa: [4, 5] * [2, 3] = [-7, 22]
2025-02-17 06:37:13,925 - INFO - Pruebas completadas.
ok
test_operaciones_con_flotantes (__main__.TestSimpleComplexCalculator)
Prueba las operaciones básicas con números flotantes. ... 2025-02-17 06:37:13,929 - INFO - Suma exitosa: [4.67, 5.89] + [2.0, 3.0] = [6.67, 8.89]
2025-02-17 06:37:13,929 - INFO - Resta exitosa: [4.67, 5.89] - [2.0, 3.0] = [2.67, 2.8899999999999997]
2025-02-17 06:37:13,929 - INFO - Pruebas completadas.
ok
test_operaciones_con_tipos_mixtos (__main__.TestSimpleComplexCalculator)
Prueba las operaciones con mezcla de enteros y flotantes. ... 2025-02-17 06:37:13,929 - INFO - Suma exitosa: [1, 2.5] + [3.5, 4] = [4.5, 6.5]
2025-02-17 06:37:13,929 - INFO - Pruebas completadas.
ok
test_validacion_tipos_especificos (__main__.TestSimpleComplexCalculator)
Prueba validaciones específicas de tipos. ... 2025-02-17 06:37:13,929 - ERROR - Todos los elementos deben ser números enteros o flotantes.
2025-02-17 06:37:13,929 - ERROR - Error al sumar [None, 1] y [4, 5]: Todos los elementos deben ser números enteros o flotantes
2025-02-17 06:37:13,929 - ERROR - Todos los elementos deben ser números enteros o flotantes.
2025-02-17 06:37:13,932 - ERROR - Error al sumar [True, False] y [4, 5]: Todos los elementos deben ser números enteros o flotantes
2025-02-17 06:37:13,932 - ERROR - Todos los elementos deben ser números enteros o flotantes.
2025-02-17 06:37:13,932 - ERROR - Error al sumar [(1+2j), 3] y [4, 5]: Todos los elementos deben ser números enteros o flotantes
2025-02-17 06:37:13,932 - INFO - Pruebas completadas.
ok

----------------------------------------------------------------------
Ran 8 tests in 0.014s
