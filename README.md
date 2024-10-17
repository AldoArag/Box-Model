# Box-Model
Box Model


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>CSS Learn</title>
<style>
h1 {
  border: 2px dashed red;
  width: 50%;
  font-size: 3rem;
  padding: 0.5em;
}

* {
  margin: 0;
  padding: 0;
}	

/* ... */
h1 {
  border: 2px dashed red;
  width: 400px;
  font-size: 3rem;
  padding: 0.5em;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}	

/* CSS Reset */
* {
	  margin: 0;
	  padding: 0;
	  box-sizing: border-box;
	}	
	
	.container {
	  border: 2px dashed red;
	  font-size: 1.5rem;
	  margin: 1.5em;
	  padding: 1.5em;
	}


    .container {
  border: 2px dashed red;
  font-size: 1.5rem;
  margin-top: 1.5em;
  margin-right: 2em;
  margin-bottom: 2em;
  margin-left: 2em;
  padding: 1.5em;
}


.container {
  border: dashed red;
  border-top: 5px solid green;
  border-right: 5px dotted teal;
  font-size: 1.5rem;
  /* margin-top: 1.5em;
  margin-right: 2em;
  margin-bottom: 2em;
  margin-left: 2em; */
  margin: 1.5em;
  padding: 1.5em 2em 3em 4em;
}



.container {
  border: 10px double red;
  font-size: 1.5rem;
  margin: 1.5em;
  padding: 1.5em 2em 3em 4em;
  outline: 5px solid blue;
}


.container {
  border: 10px double red;
  font-size: 1.5rem;
  margin: 1.5em;
  padding: 1.5em 2em 3em 4em;
  outline: 5px solid blue;
  outline-offset: 10px;
}



.circle {
  margin: 3rem auto;
  background-color: gold;
  border: 2px solid black;
  border-radius: 50%;
  outline: 2px solid red;
  outline-offset: 0.25rem;
  height: 100px;
  width: 100px;´
}


      </style>


  </head>
  <body>
    <header class="container">
        <h1>CSS Box Model</h1>
      </header>
      <main class="container">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia
          laudantium exercitationem corporis quia dolores esse enim?
          Necessitatibus quisquam, magni iste beatae earum et fugiat aut
          delectus porro voluptate, praesentium totam?
        </p>
        <div class="circle">
        </div>
      </main>
  </body>
</html>
