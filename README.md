<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pick Our Next Adventure</title>
 <style>
  body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #1f2933, #2d1b69);
    color: #e5e7eb;
    max-width: 700px;
    margin: auto;
    padding: 2rem;
  }

  h1 {
    color: #6ee7b7; /* soft green */
  }

  h2 {
    color: #93c5fd; /* light blue */
  }

  p {
    color: #fbcfe8; /* light pink */
    line-height: 1.6;
  }

  label {
    display: block;
    margin: 0.4rem 0;
    cursor: pointer;
  }

  a {
    color: #c4b5fd; /* purple */
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  button {
    margin-top: 1.5rem;
    padding: 0.7rem 1.2rem;
    background: #6ee7b7; /* green */
    border: none;
    color: #1f2933;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 6px;
  }

  button:hover {
    background: #93c5fd; /* blue */
  }
</style>

</head>
<body>

<h1>Help Me Pick Our Next Hangout</h1>
<p>Be honest. This directly affects our plans.</p>
<p>
  I’ve really enjoyed getting to know you, and I’m hoping these date ideas give us a better chance to spend time together, get to know each other more, and have some fun along the way.
</p>

<form action="https://formspree.io/f/maqdwnpo" method="POST">

<h2>Competitive</h2>
<label><input type="checkbox" name="competitive" value="Topgolf"> Topgolf</label>
<label><input type="checkbox" name="competitive" value="Bowling / Arcade"> Bowling / Arcade</label>
<label><input type="checkbox" name="competitive" value="Axe Throwing"> Axe Throwing</label>
<label><input type="checkbox" name="competitive" value="Escape Room"> Escape Room</label>
<label><input type="checkbox" name="competitive" value="Main Event"> Main Event</label>

<h2>Fun / Excitement</h2>
<label><input type="checkbox" name="fun" value="Dave & Busters"> Dave & Buster’s</label>
<label><input type="checkbox" name="fun" value="Rage Room"> Rage Room</label>
<label><input type="checkbox" name="fun" value="Trampoline Park"> Trampoline Park</label>
<label><input type="checkbox" name="fun" value="Old Town Walk"> Old Town Walk</label>


<h2>Entertainment</h2>
<label><input type="checkbox" name="entertainment" value="Movie Night"> Movie / Indie Theater</label>
<label><input type="checkbox" name="entertainment" value="Live Music"> Live Music</label>
<label><input type="checkbox" name="entertainment" value="Comedy Show"> Comedy Show</label>
<label><input type="checkbox" name="entertainment" value="BioPark Evening"> BioPark Evening Event</label>

<h2>Creative / Artistic</h2>
<label><input type="checkbox" name="creative" value="Paint War"> Chatter Paint</label>
<label><input type="checkbox" name="creative" value="Pottery Painting"> Pottery Painting</label>
<label><input type="checkbox" name="creative" value="Art Workshop"> Art Workshop</label>
<label><input type="checkbox" name="creative" value="Mural Walk"> Downtown Mural Walk</label>
<label><input type="checkbox" name="creative" value="Kiln It"> Kiln It Studio</label>

<button type="submit">Submit My Picks</button>

</form>

</body>
</html>
