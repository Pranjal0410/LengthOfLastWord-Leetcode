
---

# Length of Last Word Finder

This Python program helps you find out how long the last word in a sentence is.

## How it Works

1. The program defines a class called `Solution`.
2. Inside this class, there's a function called `lengthOfLastWord` that takes a string `s` as input.
3. It then goes through the string from the end and counts the number of letters in the last word.

## Usage

1. Make sure you have Python installed on your computer.
2. Open a Python environment or code editor.
3. Copy and paste the provided code into your environment.
4. Use an instance of the `Solution` class to call the `lengthOfLastWord` function, passing the sentence as an argument.

```python
my_solution = Solution()
result = my_solution.lengthOfLastWord("Hello World")
print(result)  # This will print the length of the last word.
```

## Example

If you run the program with the sentence "Hello World", it will return `5` because the last word, "World", has 5 letters.

## Notes

- This program assumes that words are separated by spaces.
- It ignores any spaces at the end of the sentence.

---

Feel free to customize this README file with any additional information or instructions you think might be helpful!
