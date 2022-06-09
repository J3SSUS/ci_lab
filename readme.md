# Pasos

1. virtualenv venv --python=python3.8
2. venv\Scripts\activate (for Windows)
3. pip freeze
4. crear requirements.txt
5. pip install -r requirements.txt
6. pytest tests/ . -v
7. pytest tests/test_math_func.py::test_add -v
8. pytest tests/ -v -m number
9. pytest tests/ -v -k "add" -> solo los que contienen la palabra add