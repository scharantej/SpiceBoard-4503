## Flask Application Design

### HTML Files

**index.html**

- Main landing page for the Dune: Imperium website.
- Features high-quality images, engaging animations, and concise, captivating text.
- Utilizes a color scheme inspired by the Dune universe.
- Highlights the game's features and appeals to potential players.

**_partials/_header.html**

- Partial for the header section of all pages.
- Contains the navigation bar and any other global elements.

**_partials/_footer.html**

- Partial for the footer section of all pages.
- Contains information such as copyright and contact details.

### Routes

**@app.route('/')**

- Route for the main landing page.
- Renders the **index.html** template.

**@app.route('/about')**

- Route for the about page.
- Provides additional information about the game, its creators, and the Dune universe.

**@app.route('/rules')**

- Route for the rules page.
- Provides a detailed explanation of the game's rules and gameplay.

**@app.route('/buy')**

- Route for the buy page.
- Provides links to purchase the game online or in local game stores.

**@app.route('/contact')**

- Route for the contact page.
- Allows users to contact the game's creators or ask questions about the game.