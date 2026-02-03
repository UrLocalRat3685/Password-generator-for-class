# Password-generator-for-class!!
Sorry for the late turn-in, i've been without wifi for the past few days and have been drafting this project at work T_T
# our awesome password generator will make awesome passwords in 2 different formats!!:
1) **Memorable** passwords made from random English nouns with a digit added to each word. 
2) **Random** passwords made from randomly selected characters (letters, digits, and optional punctuation). 
Each generated password is then saved with the day/date/time it was created into a log file!!

## How to run 

1. Make sure these files are in the same folder: - password_generator.py - top_english_nouns_lower_100000.txt 
2. Run:
bash
   python password_generator.py
3. Follow the on-screen prompts to choose the password type and options.

## Output
- Memorable passwords are saved to `Memorable/Generated_Passwords.txt`
- Random passwords are saved to `Random/Generated_Passwords.txt`

The program will automatically create these folders if they do not already exist!

## Python modules used
- `random`
- `string`
- `datetime`
- `pathlib`
