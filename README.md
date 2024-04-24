# Website Blocker

## Python Website Blocker Project Prerequisites

This project requires a basic understanding of Python, including concepts like defining functions and using loops. To use the Tkinter module, you need to install it using the following command:

```bash
pip install tk
```

## Project File Structure

Let's take a look at the steps involved in creating the Python Website Blocker project:

1. **Importing the Required Library:**

We only require the Tkinter module to create the GUI in Python.

```python
from tkinter import *
```

2. **Creating GUI Window:**

```python
window = Tk()
window.geometry('650x400')
window.minsize(650,400)
window.maxsize(650,400)
window.title("Website Blocker")
heading=Label(window, text ='Website Blocker' , font ='arial')
heading.pack()
```

3. **Host Path and IP Address:**

```python
host_path ='C:\Windows\System32\drivers\etc\hosts'
ip_address = '127.0.0.1'
```

4. **Create Block Function:**

```python
def Blocker():
    # Function code here
```

5. **Unblock Function:**

```python
def Unblock():
    # Function code here
```

6. **Creating Labels and Buttons:**

```python
label1=Label(window, text ='Enter Website :' , font ='arial 13 bold')
label1.place(x=5 ,y=60)
enter_Website = Text(window,font = 'arial',height='2', width = '40')
enter_Website.place(x= 140,y = 60)
```

7. **Main Command:**

```python
window.mainloop()
```

While working with the host file, you need to run the code as an administrator in the command prompt to make changes to the host file. Attempting to run the file directly may result in a "Permission not granted" error.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

