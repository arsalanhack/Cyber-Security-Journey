# Cheatsheet — Commands from *The Linux Command Line*

## Navigation
```bash
cd ..          # go up one directory
pwd            # print current directory
```

## File Info & Viewing
```bash
file filename  # tells you what type of file it is
less filename  # displays file contents, page by page
open filename  # opens file with its default app (macOS)
type command   # tells you what type of command something is
```

## Listing Files
```bash
ls -l          # long format listing
ls -a          # show hidden files too
```

## Date & Time
```bash
date           # show current date
cal            # show calendar
```

## Wildcards
```bash
'*' # select all files
'?' # match exactly one character.
'[characters]' # Match any character that is a member of the set of characters.
'[!characters]' # Match any character that is not a member of the set of characters.
'[[:class:]]' # Match any character that is a member of a specified class.
    1. [:alnum:] # Matches any alphanumerical character.
    2. [:alpha:] # Matches any alphabetical character.
    3. [:digit:] # Matches any numerical.
    4. [:lower:] # Matches any lowercase letter.
    5. [:upper:] # Matches any uppercase letter.
```

## Misc
```bash
mv ~/... ~/ ... # move directories to other locations
ln /... ~/...   # creates symbolic link