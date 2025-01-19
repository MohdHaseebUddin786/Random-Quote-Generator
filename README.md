# Python-2
'''

Welcome to GDB Online.
GDB online is an online compiler and debugger tool for C, C++, Python, Java, PHP, Ruby, Perl,
C#, OCaml, VB, Swift, Pascal, Fortran, Haskell, Objective-C, Assembly, HTML, CSS, JS, SQLite, Prolog.
Code, Compile, Run and Debug online from anywhere in world.

'''
import random

def display_random_quote():
    quotes = [
       "Dream, dream, dream. Dreams transform into thoughts and thoughts result in action.",
        "You have to dream before your dreams can come true.",
        "If you want to shine like a sun, first burn like a sun.",
        "Man needs difficulties in life because they are necessary to enjoy success.",
        "Don’t take rest after your first victory because if you fail in second, more lips are waiting to say that your first victory was just luck.",
        "All of us do not have equal talent. But, all of us have an equal opportunity to develop our talents.",
        "Confidence and hard work is the best medicine to kill the disease called failure. It will make you a successful person.",
        "Thinking should become your capital asset, no matter whatever ups and downs you come across in your life.",
        "Small aim is a crime; have great aim.",
        "To succeed in your mission, you must have single-minded devotion to your goal.",
    ]
    
    selected_quote = random.choice(quotes)
    print("\n Motivational Quote")
    print("By Dr. A.P.J Kalam Sir")
    print(selected_quote)

# Run the function
display_random_quote()
