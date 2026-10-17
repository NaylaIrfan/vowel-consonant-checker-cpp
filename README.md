# vowel-consonant-checker-cpp

# Vowel or Consonant Checker (C++)

A beginner-friendly C++ program that checks whether a character entered by the user is a vowel or a consonant.

## About

The program reads a single character and first checks whether it is a letter. If it is, the program checks whether it is one of the five vowels (`a`, `e`, `i`, `o`, `u`, in small or capital form). Any other letter is a consonant. If the character is not a letter (a digit or symbol), the program says so.

## Example

```
Enter a character: E
E is a vowel.
```

```
Enter a character: m
m is a consonant.
```

```
Enter a character: 7
7 is not an alphabet.
```

## How It Works

1. Read one character using `cin >> ch`.
2. Check whether it is a letter (`a` to `z` or `A` to `Z`).
3. If it is a letter:
   - If it is `a`, `e`, `i`, `o` or `u` (small or capital), print that it is a vowel.
   - Otherwise, print that it is a consonant.
4. If it is not a letter, print that it is not an alphabet.

## Shorter Version

The code can also be written using `isalpha()`, `tolower()` and a `switch` statement from `<cctype>`. This way only the five lowercase vowels need to be listed.

## Things to Note

- Both uppercase and lowercase letters work.
- `cin >> ch` reads only one character. If you type `abc`, only `a` is used.
- Digits, spaces and symbols are reported as "not an alphabet" instead of being called consonants.

## Concepts Used

- `char` data type
- Input and output (`cin`, `cout`)
- `if` / `else if` / `else` conditions
- Logical operators (`&&`, `||`)
- ASCII comparison of characters
- `switch` statement, `isalpha()` and `tolower()` (in the shorter version)

## How to Run

Make sure a C++ compiler such as `g++` is installed.

```bash
# Compile
g++ vowel_or_consonant.cpp -o vowel_or_consonant

# Run (Linux / macOS)
./vowel_or_consonant

# Run (Windows)
vowel_or_consonant.exe
```

## Project Structure

```
vowel-or-consonant-cpp/
├── README.md
└── vowel_or_consonant.cpp
```

## Author

NAYLA IRFAN
B.Tech CSE

## License

This project is free to use for learning purposes.
