all predefined variables will be called: "var1"

```python
var1.upper()
```
will convert var1 string to upper case

```python
replace()
var1.replace('sometext', 'replacement')
```
replace text (sometext) in a string to (replacement) in var1

```python
print(This is whats \"gucci\" in verspucci")
```
escaping characters: use \\ to insert "illegal" characters anything following it is 

```python
import re

text = """Berlin is a world of culture, politics, media and science."""

var1 = "[\s]"

result = re.search(var1, text)

print(result.start())
```
shows the starting position of result