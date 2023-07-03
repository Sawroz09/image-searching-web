# image-searching-web
html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="picture.css" />
    <title>Image Search App JS API</title>
  </head>
  <body>
    <h1>Image Search website</h1>
    <form action="">
      <input type="text" id="search-input" placeholder="Search for images" />
      <button id="search-button">Search</button>
    </form>
    <div class="search-results">
      <div class="search-result">
        <img
          src="https://images.unsplash.com/photo-1686846192802-6baeda1b0771?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=764&q=80"
          alt="EVENING ROAD"
        />
        <a
          href="https://unsplash.com/photos/a-group-of-people-walking-across-a-cross-walk-gx5kmlplWwE"
          target="_blank"
          >EVENING ROAD</a
        >
      </div>
      <div class="search-result">
        <img
          src="https://images.unsplash.com/photo-1686846192802-6baeda1b0771?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=764&q=80"
          alt="EVENING ROAD"
        />
        <a
          href="https://unsplash.com/photos/a-group-of-people-walking-across-a-cross-walk-gx5kmlplWwE"
          target="_blank"
          >EVENING ROAD</a
        >
      </div>
      <div class="search-result">
        <img
          src="https://images.unsplash.com/photo-1686846192802-6baeda1b0771?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=764&q=80"
          alt="EVENING ROAD"
        />
        <a
          href="https://unsplash.com/photos/a-group-of-people-walking-across-a-cross-walk-gx5kmlplWwE"
          target="_blank"
          >EVENING ROAD</a
        >
      </div>
    </div>

    <button id="show-more-button">Show more</button>

    <script src="picture.js"></script>
  </body>
</html>
