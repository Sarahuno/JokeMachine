Usage
python
from JokeMachine import Dad_Joke

# Fetch a random dad joke
setup, punchline = Dad_Joke()
print(setup)
print(punchline)

# Fetch a random dad joke and print the full joke
full_joke = Dad_Joke(full=True)
print(full_joke)
Documentation
Dad_Joke(full=False)
Fetches a random dad joke from the API.

Arguments
full (bool, optional): If True, returns the full joke with a newline between setup and punchline. If False (default), returns a tuple containing the setup (str) and punchline (str).
Returns
Tuple if full is False: A tuple representing the random joke fetched from the API, containing the setup (str) and punchline (str).
str if full is True: The full joke as a single string with a newline between setup and punchline.
None if the request fails or no jokes are available.
Dependencies
requests
Author
Sarah Akers

Email: Ripsweetener@gmail.com
License
This project is licensed under the MIT License - see the LICENSE file for details.
"""
