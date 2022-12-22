# MovieScrapper

// For cheerio installation
npm i cheerio

// For axios installation
npm i axios

// How the program works
(1) The user/client should enter the url of the movie (eg. https://entzhood.com.ng/mp4-movie-download-avatar-the-way-of-water-2022-hollywood-movie-download/)
(2) The program first checks if the site is from "entzhood"
(3) Next, the program fetches the source code, scrap the source code to get the title, image, description and links of the website.
(4) Lastly, it returns the scrapped data in form of JSON Data.

// How to use the program
(1) Make sure to have NodeJs installed on your OS.
(2) Run the "npm install" command to install the necessary packages needed to run the program (For first time unless the application would not run)
(3) Run the program using the "node index" command.
(4) Enter the url of the movie

Vue-la the application does the rest of the work.