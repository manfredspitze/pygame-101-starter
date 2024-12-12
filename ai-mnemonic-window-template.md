A helpful mnemonic device for your students to remember the sequence of code needed to create a basic game window template in Pygame.

**"I Set Up Games"**

This stands for:

- **I** - **Initialize Pygame**: `pygame.init()`
- **S** - **Set up the screen/window**: `pygame.display.set_mode((width, height))`
- **U** - **Update the display**: `pygame.display.flip()`
- **G** - **Game loop**: Set up the main loop to keep the game running.
- **A** - **Activate events**: Use `pygame.event.get()` to capture events (like quitting).
- **M** - **Maintain the game window**: Use `screen.fill()` to change background color.
- **E** - **Exit**: Close the game when the quit event happens (`pygame.quit()`).

---

### How the mnemonic works:

- **"I"**: Start by initializing Pygame so that all necessary modules are ready.
- **"Set Up"**: Set the window size with `pygame.display.set_mode()`.
- **"Games"**: Loop through the game events and update the screen, keeping the game window running.

