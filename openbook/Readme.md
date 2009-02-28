# openbook.js

openbook.js is a pure javascript implementation of [John Miedema](http://johnmiedema.ca)'s [OpenBook wordpress plugin](http://johnmiedema.ca/openbook-wordpress-plugin/). 

It uses [Open Library Books API](http://openlibrary.org/dev/docs/api/books) to get all the required data with a single AJAX request.

## How to use

Include `jquery.js` and `openbook.js` javascripts in head of the html.

    <script src="http://openlibrary.org:8080/static/js/jquery/jquery.js"></script>
    <script src="http://openlibrary.org:8080/static/js/openbook.js"></script>

And add a div with class `openbook` with `booknumber` attribute set to isbn of the required book.

    <div class="openbook" booknumber="9780864924933"></div>