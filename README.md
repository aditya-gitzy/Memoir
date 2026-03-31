# Memoir 🌙
*A look back at us.*

Ever tried reading your downloaded Instagram chat history? It's a mess. You get a folder full of backwards HTML files that look like cold server logs, making it impossible to actually sit down and reminisce. 

Memoir fixes that. It takes your raw `message_X.html` files, parses the text, flips them into chronological order, and wraps them in a delicate, glassmorphism UI. It’s designed to feel less like reading a database and more like flipping through a diary of the time you’ve spent with someone.

### What makes it special
- **It breathes:** A soft, frosted-glass design with an interactive, ambient background and a smooth dark/light mode toggle.
- **Paced reading:** It automatically parses timestamps and injects elegant date-dividers, breaking up endless walls of text into readable "chapters" of days and weeks.
- **Contextual Search:** Pinpoint that exact inside joke or memory. You can isolate your timeline to only show messages containing specific words, or highlight those words within the full flow of the conversation.
- **100% Private & Local:** These are your private memories. Memoir is a static file. There are no servers, no databases, and no APIs. Your chat files never leave your computer—everything is parsed and rendered directly in your browser.

### How to relive your memories
1. **Get your data:** Request your data download from Instagram. Make sure you select the **HTML format** (not JSON).
2. **Locate the chat:** Unzip your Instagram data, navigate to your messages, and open the specific chat folder you want to read. You'll see files named `message_1.html`, `message_2.html`, etc.
3. **Open Memoir:** Simply open `index.html` in any modern web browser. 
4. **Load them up:** Click "Choose Files", select **all** the `message_X.html` files from that folder, and hit the format button.
5. Grab a coffee, scroll back to day one, and enjoy. 

### Tech Stack
Built purely with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies.

### License & Copyright
© 2026 Aditya Lande. All rights reserved.

Memoir is a personal portfolio project. While you are totally welcome to poke around the code to see how the local DOM parsing or the CSS glassmorphism effects are built, please do not clone this repository to republish, rebrand, or monetize it as your own application.
