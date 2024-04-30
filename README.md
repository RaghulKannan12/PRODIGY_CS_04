# PRODIGY_CS_04
# Simple Keylogger

imagine you're curious about how keyboards work and you want to learn more about it. This code here is like a virtual assistant that observes and records everything you type on your keyboard. It's designed to be quiet and unobtrusive, just quietly taking note of the keys you press without disturbing your activities.

The on_press function is like the brain behind this assistant. Every time you press a key on your keyboard, this function gets triggered. It's programmed to quickly jot down the key you pressed and store it in a log file named "keylog.txt". This log file keeps a record of all the keys you've pressed, allowing you to review them later if you need to.

Now, when you run the main function, it's like activating this virtual assistant. It greets you with a message saying "Keylogger started. Press 'Ctrl + C' to stop." This means the assistant is now quietly observing your keyboard activities in the background.

As you continue your work or browsing, the assistant silently listens for your keystrokes using the Listener function. If you press any keys, it quietly records them in the log file as per the instructions in the on_press function.

If you ever want to stop the assistant from recording your keystrokes, you can simply press "Ctrl + C". This signals to the assistant that you're done with your session, and it gracefully stops recording your keystrokes. It says "Keylogger stopped." as a polite confirmation that it's no longer active.

In summary, this code creates a virtual assistant that quietly observes and records your keyboard activities, allowing you to keep track of the keys you've pressed. It's like having a helpful assistant always by your side, quietly noting down your every keystroke.
