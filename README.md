# Word-Count

## Aim:

To create a python code for counting the number of words in a sentence or paragraph.

## Algorithm:
 1. Define a function count_words.
 2. Use words function to to read the text and and split them into words.
 3. Use the function user_text to get the input from the user.
 4. The function word_count is used to count the number of words.
 5. Print the number of the words.
 6. Get the output and end the program.

## Program:
```
def count_words(text):
  words = text.strip().split()
  return len(words)
user_text = input("Enter a sentence or paragraph: ")

word_count = count_words(user_text)
print("The number of words in your text is:", word_count)
```

## Output:

![Screenshot 2024-07-16 202412](https://github.com/user-attachments/assets/cc89e6ab-38da-46c2-b324-be26e4e262fc)

## Result:
Thus the python program to count number of words in a sentence or paragraph is excecuted successfully.
