# JokeMachine

A Python library to fetch dad jokes from a list of 3000 jokes.

## Installation

You can install JokeMachine via pip:

```bash
pip install JokeMachine
```





```python
from JokeMachine import Dad_Joke

# Fetch a random dad joke
setup, punchline = Dad_Joke()
print(setup)
print(punchline)

# Fetch a random dad joke and print the full joke
full_joke = Dad_Joke(full=True)
print(full_joke)
```
# Documentation
 ## `Dad_Joke()`
Fetches a random dad joke from the API.

**Arguments**
* `full` (bool, optional): If `True`, returns the full joke with a newline between setup and punchline. 
* `str` if `full` is `None`: The full joke as a single string with a newline between setup and punchline.
* `None` if the request fails or no jokes are available.

**Returns**

* `Tuple` if `full` is `None` (Default): A tuple representing the random joke fetched from the API, containing the setup (str) and punchline (str).
* `str` if `full` is `True`: The full joke as a single string with a newline between setup and punchline.
* None if the request fails or no jokes are available.

# Dependencies   
* `requests`


# Author
 Sarah Andersson

* Email Ripsweetener@gmail.com




