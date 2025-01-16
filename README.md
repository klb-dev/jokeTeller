# Joke Teller
![Joke Teller image](assets/laughingDog.gif)

# Description
A dynamic joke-telling website where users can choose their preferred joke categories. To engage users, it features an animated GIF of a laughing white dog for added inspiration. The site is fully responsive across all devices and integrates a text-to-speech API from the Rapid API marketplace to deliver jokes audibly.
# Tools
- HTML
- CSS
- JavaScript
- APIs (2 - VoiceRSS and JokeAPI)
# Learning
Learning how text-to-speech works was a new experience for me. It took some time to understand how the API functions, and I had to make a few modifications to the SDK. Using JokeAPI was interesting because it supports multiple types of jokes. Instead of grouping all the jokes together and fetching a random one, I chose to create constants for different categories. This allows users to select from five options using radio buttons, making the experience feel more personalized.
<br>
As a self-taught developer, working with different HTML and JavaScript elements has been challenging. I often feel inclined to put everything directly into the HTML, but using JavaScript makes the site more interactive. I'm still getting used to dynamically placing elements into the site using JavaScript.
# Issues
I initially struggled with getting the `tellJoke()` function to work properly when incorporating multiple URLs. It worked perfectly with a single URL, but I wanted to give users the option to choose between different joke sources. I thought a `switch` statement would be a good solution, but I kept encountering 404 errors. Even though the `console.log` showed the correct URL for each case, the function still couldn't connect to the site. After some thought, I decided to use variables for the different URLs and implement a ternary statement directly in the `fetch()` call. This turned out to be a much simpler solution, though it took me a couple of hours to figure it out. Along the way, I also learned that the `await` keyword needs to be in the top portion of an `async` function. I had initially tried placing `await` inside the `switch` statement, which led to more errors.
<br>
Challenges like these help deepen my understanding of JavaScript. I view them not as failures but as opportunities to enhance my coding skills.
# Author
**Blue Byrd Development** ![Blue Byrd Development logo](assets/favicon.ico)
<br>
*Karen Byrd 2025*
