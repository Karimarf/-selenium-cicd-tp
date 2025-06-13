## 2.3 analyse du rapport 

avant tout , on observe 4 erreurs en console suite a l'éxécution de la commande: 
    python -m pytest tests/test_selenium.py -v --html=report.html --self-contained-html

```cmd
ERROR tests/test_selenium.py::TestCalculator::test_page_loads - AttributeError: 'NoneType' object has no attribute 'split'
ERROR tests/test_selenium.py::TestCalculator::test_addition - AttributeError: 'NoneType' object has no attribute 'split'
ERROR tests/test_selenium.py::TestCalculator::test_division_by_zero - AttributeError: 'NoneType' object has no attribute 'split'
ERROR tests/test_selenium.py::TestCalculator::test_all_operations - AttributeError: 'NoneType' object has no attribute 'split'
```

en suite en ouvrant la page report.html , on n'a plus d'information concernant les erreurs :
    - fonction test_page_loads
    - test_addition
    - test_division_by_zero
    - test_all_operations