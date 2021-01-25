# Greeting Kata

[Original source here](https://github.com/testdouble/contributing-tests/wiki/Greeting-Kata)

## How to install

```
pip install requirements.txt
``` 

## Tips

### Parametrized tests
```python
@pytest.mark.parametrize("test_input, expected", [
    ("Bob", "Hello, Bob.")
])
def test(test_input, expected):
    pass
```