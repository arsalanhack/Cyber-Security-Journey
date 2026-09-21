# The Linux Command line by William Shotts

**Chapter 4 - Manipulating files and directories**

**2026-09-6**

I learned about wildcards today.

In my own words:

- Wildcards are special characters in the command line that let you match multiple files or directories without typing exact names. Basically, they are a selection feature for choosing many files at once.

Wildcards I learned:

- '\*' # select all files
- '?' # match exactly one character.
- '[characters]' # Match any character that is a member of the set of characters.
- '[!characters]' # Match any character that is not a member of the set of characters.
- '[[:class:]]' # Match any character that is a member of a specified class.
  - With that, I learned the common character classes.

Wildcards seem difficult to remember, but I am sure that after a bit of practice they will be easy to remember.

**2026-09-7**

Going further into Wildcards.
I learned the commonly used characters classes.

Character classes:

1. [:alnum:] # Matches any alphanumerical character.
2. [:alpha:] # Matches any alphabetical character.
3. [:digit:] # Matches any numerical.
4. [:lower:] # Matches any lowercase letter.
5. [:upper:] # Matches any uppercase letter.

Wildcard examples:

1. '*' -> all files
2. 'g*' -> Any file beginning with g
3. 'b*' -> .txt Any file beginning with b followed by any characters and ending with .txt
4. 'Data???' -> Any file beginning with Data followed by exactly three characters
5. '[abc]*' -> Any file beginning with either an a, a b, or a c
6. 'BACKUP.[0-9][0-9][0-9]' -> Any file beginning with BACKUP. followed by exactly three numerals
7. '[[:upper:]]*' -> Any file beginning with an uppercase letter
8. '[![:digit:]]*' -> Any file not beginning with a numeral
9. '*[[:lower:]123]' -> Any file ending with a lowercase letter or the numerals 1, 2, or 3
