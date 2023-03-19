
# Update to API
The next video will use an API that may no longer work depending on when you are watching the video, specifically: https://type.fit/api/quotes

I have instead created my own version of a Quotes API that contains over 8,000 quotes! It is hosted on GitHub and will be hosted in my own repository to avoid any issues in the future. You can find it here:

https://jacintodesign.github.io/quotes-api/data/quotes.json

You will only need to change part of one line of the code from what you will see in the video, and that is your apiUrl variable. Below is the old code:

// Get Quotes From API
async function getQuotes() {
  ...
  const apiUrl = 'https://type.fit/api/quotes';
  try {
  ...
Which will be replaced with this:

// Get Quotes From API
async function getQuotes() {
  ...
  const apiUrl = 'https://jacintodesign.github.io/quotes-api/data/quotes.json';
  try {
  ...

Lastly, I have updated the quotes-generator project on my GitHub and have updated the final zip file of the project to include the correct API. Enjoy :)
# Sample Requests
https://zenquotes.io/api/quotes - Generate a JSON array of 50 random quotes on each request

https://zenquotes.io/api/today - Generate the quote of the day on each request

https://zenquotes.io/api/random - Generate a random quote on each request