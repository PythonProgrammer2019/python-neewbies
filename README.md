# python-neewbies

from tkinter import *

root = Tk()

canvas = Canvas(width=250, height=300, bg='blue')
canvas.pack()
photo = PhotoImage(file='C:\\Users\\kavin_1ic\\Documents\\Pictures\\download.png')
canvas.create_image(0,0, image=photo, anchor=NW)
root.mainloop()
