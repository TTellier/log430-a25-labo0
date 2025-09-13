# Labo 00 – Infrastructure (Git, Docker, CI/CD)
LOG 430 Thomas Tellier

## Question 1

Pytest indique le titre du test qui ne fonctionne pas, 
l'extrait du test est affiché
Les valeurs du test sont affiché
Le chemin du fichier et le numéro de ligne est affiché

__________________________________________ test_division ________________________________________________

    def test_division():
        my_calculator = Calculator()
>       assert my_calculator.division(10, 2) == 6
E       assert 5.0 == 6
E        +  where 5.0 = division(10, 2)
E        +    where division = <src.calculator.Calculator object at 0x000001D0B4D180D0>.division

src\tests\test_calculator.py:27: AssertionError

==================================== short test summary info ======================================
FAILED src/tests/test_calculator.py::test_division - assert 5.0 == 6
==================================== 1 failed, 5 passed in 0.32s ======================================


## Question 2
