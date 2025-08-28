# Friends-List
This is a practice for logic programming
# Friends List & Raffle

## Project Description
This project is a simple web application built with **HTML, CSS, and JavaScript**.  
It allows the user to:  
- Register a list of friends.  
- Display the list of registered friends on the screen.  
- Randomly select one friend from the list.  

The main goal is to practice **basic JavaScript**, **DOM manipulation**, and **array handling**.

---

## Features
- Add friends to a list using a text input.  
- Validate that the input is not empty before adding.  
- Display the list of friends dynamically in the interface.  
- Randomly pick a friend from the list.  
- Show the raffle result on the screen.  

---

## Application
Main code used in the project:

```html
<h2>Add Friends</h2>
<input type="text" id="nombre" placeholder="Type a name">
<button onclick="addFriends()">Add Friend</button>

<ul id="listaAmigos"></ul>

<hr>

<h2>Raffle</h2>
<button onclick="sortearAmigo()">Draw Friend</button>
<p id="resultado"></p>




