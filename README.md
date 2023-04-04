# pokemon-starter-selector
Pokemon Starter Selector:

This application will allow you to select a pokemon starter.

Include these files:
1. home.html
2. about.html
3. styles.css
4. fonts.css
5. about.css
6. app.js

* Connect your app.js, styles.css and fonts.css.

* We will be importing a  pokemon font for this project, so add it locally and connect that font via url 

* add styling choices for home.index to styles.css

* font specifications for style will happen in fonts.css 
    * set the body font to be our pokemon classic font.

Home.html:

The Setup of the file - 
* <header>
    * include an <h1> 
        * “Click a color to choose a starter”
* a <main>
* within the <main>, a <section>
     * 3<articles>
        * each with a class of pokeball and then individually, in-sequence, red, followed by blue and then green
        * sequentially, the first has an id of red-article, second has an id of blue-article and third has an id of green-article
     
* an <article> with an id of image-article and a class of pokemon-image
    * within, an <img> with a class of pokemon-image and an id of pokemon-image.
        * set the image src to match the charmander png, located in the .pngs folder. set the alt text to charmander
* an <article>, class = info, id = pokedex-info-article
    * within, a <p> with a class of pokedex and an id of pokedex-info-p
    * this will be populated with data from an api request
* an <aside>, class = info, id = pokedex-info-article
    * a <p>, class = pokedex, id = pokedex-info-p
    * this will be populated with the relevant information from our submit form api request.
* an empty <aside>, class = error, id  = error-aside
    * this will be populated with data from the form submit api request. 
* an <aside>, class = starter-name
    * within, a <span> with an id of starter-name.
    * feel free to leave this blank for now, it will be populated with on load api data.
* a <section>, class = bottom, id = bottom-section
    * within, an <article> class = about-me, id = about-me
        * an <a> tag with an href that connects to our about.html
    * within <section>, a <form>
        * within the <form> a <select>
            * within the <select four <option>
            * the first <option> has an id of error-option, and a value of “error” this option is to be selected. The text within reads “choose”.
            * <option> 2 will have an id of charmander-option and a value of charmander. The text within reads “Charmander, I choose you!”
            * <option> 3 will have an id of squirtle-option and a value of <squirtle>.  The text within reads “Squirtle, I choose you!”
            * <option> 4, id = bulbasaur-option, value = bulbasaur. The text within reads “Bulbasaur, I choose you!”
        * within the <form>, add an <input> with a type of submit and a value of go.
* This will all be styled with css and populated with data from an api request, done on our css page. 
* set up the app.js to fetch data from our api source for the first pokemon. This will populate the pokemon name into the starter-name span.
* When one of the color articles is clicked, a corresponding image should replace the pokemon image src.
<img width="1440" alt="Screenshot 2023-04-04 at 3 22 04 PM" src="https://user-images.githubusercontent.com/122542471/229911587-d71c1996-d88b-44de-9599-a4b2f1731b3c.png">

<img width="1440" alt="Screenshot 2023-04-04 at 3 22 07 PM" src="https://user-images.githubusercontent.com/122542471/229911661-6d6c08d8-6596-489d-9dc6-cf87582fdcd9.png">

If the value of our select form is left at the initially selected “I choose”, an error message within our aside will appear, a well as a reset button within our form. Set this up in our app.js file.
   
<img width="1440" alt="Screenshot 2023-04-04 at 3 44 15 PM" src="https://user-images.githubusercontent.com/122542471/229911703-39cbad72-668b-473f-8bdb-108c30b0f8bd.png">


Try hitting reset and the error message will disappear.

Select a pokemon from the dropdown menu and press go! 

This will enlarge the selected pokemon’s image and populate our pokedex info section with data from the api.
   
   <img width="1440" alt="Screenshot 2023-04-04 at 3 49 18 PM" src="https://user-images.githubusercontent.com/122542471/229911769-f9d6dbc2-67bc-4acc-9354-67920d3f1ea7.png">
   

We still have our about me page! Check out the link! On hover it should turn orange. Set that up in our style sheet.
   
<img width="1440" alt="Screenshot 2023-04-04 at 3 49 22 PM" src="https://user-images.githubusercontent.com/122542471/229911871-f5dcc5a9-9697-4614-8e3a-3c53b673ff10.png">

<img width="1440" alt="Screenshot 2023-04-04 at 3 50 03 PM" src="https://user-images.githubusercontent.com/122542471/229911918-03de67c1-0c4f-48c4-8251-9236690fb653.png">


Clicking it will lead to our next page, about.html. About.html will be styled using specific instructions from the about.css page.
   
<img width="1440" alt="Screenshot 2023-04-04 at 3 52 47 PM" src="https://user-images.githubusercontent.com/122542471/229912372-15765305-8a87-46a5-8b1b-af25d36d8de8.png">

And, of course, the home link works with our hover settings as well. 
   
<img width="1440" alt="Screenshot 2023-04-04 at 3 52 47 PM" src="https://user-images.githubusercontent.com/122542471/229912048-efadd2c1-9919-4c87-8035-a5a105e58d09.png">

And will bring us back to the first page.

<img width="1440" alt="Screenshot 2023-04-04 at 3 54 44 PM" src="https://user-images.githubusercontent.com/122542471/229912074-8ff6a019-b1c0-4601-a252-af9d0b6d1fea.png">

