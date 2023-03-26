### Hi there 👋

<!--
**santosh892/santosh892** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on NFT 
- 🌱 I’m currently learning 
- 👯 I’m looking to collaborate on crypto
- 🤔 I’m looking for help with 
- 💬 Ask me about anything
- 📫 How to reach me: check www.Robinhood58NFT.com
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


https://opensea.io/collection/robinhood58

:wink:



import time

# Define the frames of the animation
frames = [
    "  O  ",
    "/-|-\\",
    "/ \\ "
]

# Define a function to clear the terminal screen
def clear_screen():
    print(chr(27) + "[2J")

# Define a function to display a single frame
def display_frame(frame):
    clear_screen()
    print(frame)

# Loop through the frames indefinitely to create the animation
while True:
    for frame in frames:
        display_frame(frame)
        time.sleep(0.2)

