# Diamond-Hacks
**Members: [Aditi](https://github.com/aditi-3), [Chris](https://github.com/qwer030413), [Jongwon](https://github.com/JongwonLee123)**

## Diamond Stocks
![Website](/Diamond-Stocks/assets/websitepage.png)

### About
During Diamond Hacks, there were 4 tracks that were given to attendees and our group decided to work on tackling loot and ledger where we had to design some sort of application to reinvent shopping and financial transactions. The project we ended up designing was a website that trained users on how to navigate the stock market by providing real life scenarios to determine whether a stock's value would go up or down. These were designed as quizzes for different stocks. Depending on the situation, the user can invest money and depending on what happenned to the stock, the investment would either go down or up by that percentage. After finishing a quiz, the user can look at their history presenting the total networth going up or down for each quiz on a graph.

### Front-end
To create the website, we utilized:
- React
- HTML
- CSS

### Back-end
To create a database to store the quiz data for the history graph we used: 
- postgresql

### Tools
The main tool that made this project unique was Gemini API. To create random questions and pull from real life scenarios for certain stocks, we utilized calls to Gemini and provided prompts to it to generate the questions, answers, and explanations. One problem that appeared was the issue with Gemini not always presenting the same format to be parsed into the quizzes. Therefore, we performed trial and error until we designed a prompt that always presented the output we desired.

### Running the project
In order to run the project:
1. Create a gemini api key 
   1. Link here: [Gemini Page](https://ai.google.dev/gemini-api/docs/pricing)
2. Replace the key into Quiz.tsx line 22 
[](/Diamond-Stocks/assets/api_gemini.png)
3. Create the Postgresql
   1. Follow a guide online
   2. input values into index.ts
[](/Diamond-Stocks/assets/backend.png)
4. Set up front-end
   1. Run `npm i` in the terminal of frontend folder
   2. Run `npm run dev` in the same terminal
   3. Should see image below after
[](/Diamond-Stocks/assets/frontend.png)
1. Set up back-end
   1. Run `npm i` in the terminal of backend folder
   2. Run `npm run dev` in the same terminal
   3. Should see image below after
[](/Diamond-Stocks/assets/backendrun.png)
1. Check the running website! (localhost page)
[](/Diamond-Stocks/assets/websitepage.png)
Still updating informatio!
