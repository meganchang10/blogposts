# blogposts
My Fitness Blog is a knowledge base containing blog posts on the subject of fitness, health, and well-being to help you meet your fitness goals be it competing in a Tough Mudder, losing 20 pounds before your brother's wedding or just changing your lifestyle to be healthier. 

## API
Each article object will have a JSON response that looks like:

{
  "id" : "23lrkn0nadsn4io01uh",
  "title" : "Parasympathetic Breathing to get the most out of your squat",
  "author" : "Megan Chang",
  "content" : "Your body naturally wants to..."
  "date-created" : 06/27/2018
}

Authorized users can use the API to create a new article, update an existing one, or delete an existing one. To become an authorized user, contact meganchang10@gmail.com. All users can use the API to read articles. The website (insert website) will use this API to pull and display all the articles in the database.


## Prerequisites
To begin, you will need to download the following software:

Congratulations, the website should now be available for viewing at http://localhost:8000/articles/

## Technical Stack
Golang
