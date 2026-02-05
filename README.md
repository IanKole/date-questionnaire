<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pick Our Next Adventure</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #e5e7eb;
      max-width: 700px;
      margin: auto;
      padding: 2rem;
    }
    h1, h2 {
      color: #38bdf8;
    }
    label {
      display: block;
      margin: 0.4rem 0;
      cursor: pointer;
    }
    button {
      margin-top: 1.5rem;
      padding: 0.7rem 1.2rem;
      background: #38bdf8;
      border: none;
      color: #0f172a;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 6px;
    }
  </style>
</head>
<body>

<h1>Help Me Pick Our Next Hangout</h1>
<p>Be honest. This directly affects our plans.</p>

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
