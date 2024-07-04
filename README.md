# number_guess_game
We have successfully created the Number Guessing Game with the help of  Tkinter Module and Random Module of  Python. We learned about these modules and their inbuilt functions during the project.

# Importing the Required Libraries for  Python Number Guessing Game
import tkinter as tk
from tkinter import *
import random

# Creating the  GUI Window:
win = tk.Tk()
win.geometry("750x750")
win.title("PythonGeeks")

#Creating the Labels, Entry Boxes and Button:
Entry(win, textvariable=guess, width=3,font=('Ubuntu', 50), relief=GROOVE).place(relx=0.5, rely=0.3, anchor=CENTER)
 
Entry(win, textvariable=hint, width=50,font=('Courier', 15), relief=GROOVE,bg='orange').place(relx=0.5, rely=0.7, anchor=CENTER)
 
Entry(win, text=final_score, width=2,font=('Ubuntu', 24), relief=GROOVE).place(relx=0.61, rely=0.85, anchor=CENTER)
 
Label(win, text='I challenge you to guess the number ',font=("Courier", 25)).place(relx=0.5, rely=0.09, anchor=CENTER)
 
Label(win, text='Score out of 5',font=("Courier", 25)).place(relx=0.3, rely=0.85, anchor=CENTER)
 
Button(win, width=8, text='CHECK', font=('Courier', 25), command=fun, relief=GROOVE,bg='light blue').place(relx=0.5, rely=0.5, anchor=CENTER)

#  Create The Main Function – Execution of the game:
hint = StringVar()
score = IntVar()
final_score= IntVar()
guess= IntVar()

# Python Number Guessing Game Output
![image](https://github.com/Arpitkumar001/number_guess_game/assets/174322102/6885f7f7-9a3b-4829-b15f-a566c651349b)
