## Features
- User asks for recommendations based on games they've played and enjoyed
- History of games played and enjoyed stored as context
- Chatbot chooses recommendations based on genre, ratings, game attributes and review sentiment
- User rates the suggestion after playing to refine recommendations further
- Should be tailored to the user - user accounts needed
- Web app
  
## Technologies
- Python - Flask backend
- Web scraping of Google reviews using Selenium
- Sentiment analysis - SpaCy for its efficiency and features
- Chatbot using ChatterBot
- Frontend using ReactJS
- APIs: MobyGames API or IGDB
  
## Potential issues
- Scraping Google reviews. It would need to avoid collecting any PII like name of reviewer - ie only the review content
- Ethics of scraping reviews: According to ICO, "Opinions and inferences are also personal data if the individual can be identified from that data, either directly or indirectly, and the information relates to that individual." Does this apply to reviews that are publicly available? How do I ensure I'm not collecting PII?
- If the contents of the review are not stored, but processed for sentiment and then discarded, does that negate the ethical issue?
- If unable to use web scraping, more emphasis on use of MobyGames/IGDB API to compare attributes of games
  
## Overall thoughts
- Use case: Hobbyist game players looking for personalised game recommendations, without any bias from companies trying to advertise.
- Existing solutions: Quantic Foundry video game recommendation engine - "Quantic Foundry is a market research company focused on gamer motivation." Three games enjoyed entered into engine, it outputs recommendations
  
