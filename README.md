# -
Практические работы по мдк
import tkinter as tk
from tkinter import*
window = Tk()
window.title = ("Repository")
window.geometry = "1700*1500"
frame = Frame(window, padx = 10, pady =10)
frame.pack(expand = True)

l1 = Label(frame, text = "Enter your e-mail")
l1.grid(row = 1, column = 1)
l2 = Label(frame, text = "Create a Password")
l2.grid(row = 2, column = 1)
l3 = Label(frame, text = "Enter a username")
l3.grid(row = 4, column = 1)
l4 = Label(frame, text = "Would you like to receive product updates and announcements via e-mail?")
l4.grid(row = 6, column = 1)

e1 = Entry(frame)
e1.grid(row = 3, column = 1)
e2 = Entry(frame)
e2.grid(row = 5, column = 1)
e3 = Entry(frame)
e3.grid(row = 7, column = 1)
e4 = Entry(frame)
e4.grid(row = 9, column = 1)

continue_btn = Button (frame, text = "Continue")
continue_btn.grid(row = 18, column = 1)
continue_btn = Button (frame, text = "Apply for your GitHub stident benefits")
continue_btn.grid(row = 18, column = 3)

window.mainloop()
