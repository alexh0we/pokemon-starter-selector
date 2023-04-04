# pokemon-starter-selector
Pokemon Starter Selector:

This application will allow you to select a pokemon starter.

Include these files:
* home.html
* about.html
* styles.css
* fonts.css
* about.css
* app.js

* Connect your app.js, styles.css and fonts.css.

* We will be importing a  pokemon font for this project, so add it locally and connect that font via url 

* add styling choices for home.index to styles.css

* font specifications for style will happen in fonts.css 
    * set the body font to be our pokemon classic font.

Home.html:

The Setup of the file - 
* <header>
    - include an <h1> 
        - “Click a color to choose a starter”
* a <main>
* within the <main>, a <section>
    - 3 <articles>
        - each with a class of pokeball and then individually, in-sequence, red, followed by blue and then green
        - sequentially, the first has an id of red-article, second has an id of blue-article and third has an id of green-article
    - 
* an <article> with an id of image-article and a class of pokemon-image
    - within, an <img> with a class of pokemon-image and an id of pokemon-image.
        - set the image src to match the charmander png, located in the .pngs folder. set the alt text to charmander
* an <article>, class = info, id = pokedex-info-article
    - within, a <p> with a class of pokedex and an id of pokedex-info-p
    - this will be populated with data from an api request
* an <aside>, class = info, id = pokedex-info-article
    - a <p>, class = pokedex, id = pokedex-info-p
    - this will be populated with the relevant information from our submit form api request.
* an empty <aside>, class = error, id  = error-aside
    - this will be populated with data from the form submit api request. 
* an <aside>, class = starter-name
    - within, a <span> with an id of starter-name.
    - feel free to leave this blank for now, it will be populated with on load api data.
* a <section>, class = bottom, id = bottom-section
    - within, an <article> class = about-me, id = about-me
        - an <a> tag with an href that connects to our about.html
    - within <section>, a <form>
        - within the <form> a <select>
            - within the <select four <option>
            - the first <option> has an id of error-option, and a value of “error” this option is to be selected. The text within reads “choose”.
            - <option> 2 will have an id of charmander-option and a value of charmander. The text within reads “Charmander, I choose you!”
            - <option> 3 will have an id of squirtle-option and a value of <squirtle>.  The text within reads “Squirtle, I choose you!”
            - <option> 4, id = bulbasaur-option, value = bulbasaur. The text within reads “Bulbasaur, I choose you!”
        - within the <form>, add an <input> with a type of submit and a value of go.
* This will all be styled with css and populated with data from an api request, done on our css page. 
* set up the app.js to fetch data from our api source for the first pokemon. This will populate the pokemon name into the starter-name span.
* When one of the color articles is clicked, a corresponding image should replace the pokemon image src.
￼
￼

If the value of our select form is left at the initially selected “I choose”, an error message within our aside will appear, a well as a reset button within our form. Set this up in our app.js file.

￼
Try hitting reset and the error message will disappear.

Select a pokemon from the dropdown menu and press go! 

This will enlarge the selected pokemon’s image and populate our pokedex info section with data from the api.

￼

We still have our about me page! Check out the link! On hover it should turn orange. Set that up in our style sheet.

￼

￼
Clicking it will lead to our next page, about.html. About.html will be styled using specific instructions from the about.css page.

￼
And, of course, the home link works with our hover settings as well. 
￼
And will bring us back to the first page.

￼
