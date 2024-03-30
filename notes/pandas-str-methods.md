# Pandas `str` accessor methods

Here's the updated list of all `str` accessor methods in pandas that support regex, along with additional details and a few more methods:

### Matching and Searching

`contains(pattern, case=False, na=False, regex=True)`: Checks if a string contains a pattern using regex.

`match(pattern, case=True, na=False, regex=True)`: Searches for a pattern at the beginning of a string.

`rmatch(pattern, case=True, na=False, regex=True)`: Searches for a pattern at the end of a string.

`startswith(pattern, case=False, na=False, regex=True)`: Checks if a string starts with a pattern.

`endswith(pattern, case=False, na=False, regex=True)`: Checks if a string ends with a pattern.

### Extraction and Replacement

`cat(other, sep='', na=None)`: Concatenates strings, can be used with capture groups from regex extraction.

`capitalize(inplace=False)`: Capitalizes the first letter of each word.

`center(width, fillchar=' ', inplace=False)`: Centers a string within a specified width.

`count(pat, na=None)`: Counts occurrences of a pattern.

`decode(encoding=None, errors='strict')`: Decodes a string from bytes.

`encode(encoding='utf-8', errors='strict')`: Encodes a string to bytes.

`endswith(pattern, case=False, na=False, regex=True)`: Checks if a string ends with a pattern.

`extract(pat, flags=0, expand=False)`: Extracts parts of a string matched by a regex pattern. Returns a DataFrame or Series depending on `expand`.

`extractall(pat, flags=0)`: Extracts all non-overlapping matches of a pattern. Returns a list of matched groups.

`find(pat, start=0, end=None, na=None)`: Returns the index of the first occurrence of a pattern.

`findall(pat, flags=0)`: Returns all non-overlapping matches of a pattern. Returns a list of matched groups.

`finditer(pat, flags=0)`: Returns an iterator yielding match objects.

`index(pat, start=0, end=None, na=None)`: Returns the index of the first occurrence of a pattern.

`isalnum()`: Checks if all characters are alphanumeric.

`isalpha()`: Checks if all characters are alphabetic.

`isdigit()`: Checks if all characters are digits.

`islower()`: Checks if all characters are lowercase.

`isnumeric()`: Checks if all characters are numeric.

`isspace()`: Checks if all characters are whitespace.

`istitle()`: Checks if a string is titlecased.

`isupper()`: Checks if all characters are uppercase.

`join(other, na=None)`: Joins elements of a list or array with a string separator.

`len(self)`: Returns the length of the string.

`ljust(width, fillchar=' ', inplace=False)`: Left-justifies a string within a specified width.

`lower(inplace=False)`: Converts all characters to lowercase.

`lstrip(chars=None, inplace=False)`: Removes leading characters from a string.

`normalize(form='NFC', inplace=False)`: Normalizes the string with a given normalization form.

`pad(width, side='left', fillchar=' ', inplace=False)`: Pads a string to a certain width with a given fill character.

`partition(sep, expand=False)`: Partitions a string at the first occurrence of a separator. Returns a tuple of (prefix, separator, suffix).

`repeat(reps)`: Repeats a string a specified number of times.

`replace(pat, repl, n=-1, case=False, regex=True, inplace=False)`: Replaces occurrences of a pattern with a replacement string.

`rfind(pat, start=0, end=None, na=None)`: Returns the index of the last occurrence of a pattern.

`rindex(pat, start=0, end=None, na=None)`: Returns the index of the last occurrence of a pattern.

`rjust(width, fillchar=' ', inplace=False)`: Right-justifies a string within a specified width.

`rpartition(sep, expand=False)`: Partitions a string at the last occurrence

`split(pat, expand=False, regex=None)`: 