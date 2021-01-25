# Greeting Kata

[Original source here](https://github.com/testdouble/contributing-tests/wiki/Greeting-Kata)

## How to install

```
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
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