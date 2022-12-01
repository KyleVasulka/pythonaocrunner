# pythonaocrunner
Utility repo to create and run [Advent of Code](https://adventofcode.com/) solutions in Python

This project takes inspiration from [aocrunner](https://github.com/caderek/aocrunner)

# Installation
Clone this repo!
Install [python](https://www.python.org/downloads/)
Install [just](https://github.com/casey/just) command runner

### Set Advent of coders Cookie in .env file.
1. Log into [Advent of coders](https://adventofcode.com/)
2. Right click -> Inspect -> Application tab -> Storage -> Cookies -> https://adventofcode.com -> session
3. Copy session value and put it in the `.env` file

You can verify just is installed by running the command
```
just
```

# Modify Template
Modify the template located in Template/main.py

# Each day 
Run the following `just command` to set up the directory you need each day
```
just day 1
```

You can run your python program by navigating into your day directory and running the python file like normal
```
cd day1
python main.py
```

I like to make another file 'testinput.txt' and fill it with the input AOC gives me to use in my projects!

🎄🎄 GOOD LUCK! 🎄🎄
