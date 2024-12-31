# Netflix GPT Project

🎬 Welcome to Netflix GPT, a Netflix clone that provides users with a familiar interface to browse movies. The application is integrated with TMDB to fetch movie details and with Firebase for authentication. Users can watch trailers on YouTube by clicking on a movie. Additionally, there's a section for specialized movie suggestions, where users can enter their OpenAI key to get personalized movie recommendations.

## About This Project

Netflix GPT offers a seamless movie browsing experience with the following features:

1. **TMDB Integration**: Fetches movie details from The Movie Database (TMDB).

2. **YouTube Trailers**: Watch movie trailers on YouTube with a single click.

3. **Firebase Authentication**: Secure user authentication powered by Firebase.

4. **OpenAI Movie Recommendations**: Enter your OpenAI key for personalized movie suggestions.

## Installation

To run this project locally for development purposes, follow these steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/ashutoshk08/Netflix-GPT.git
   ```

2. Navigate to the project directory:

   ```shell
   cd netflix-gpt
   ```

3. Install dependencies:

   ```shell
   npm install
   ```

4. Create a Firebase project and set up authentication.

5. Configure Firebase in your project by adding your Firebase config details in `src/firebase.js`.

6. Start the development server:

   ```shell
   npm start
   ```

7. Open your web browser and explore the project locally at [http://localhost:3000/](http://localhost:3000/).

## Tech Stack

- **React**: Frontend framework for building user interfaces.
- **TMDB**: Movie database for fetching movie details.
- **Firebase**: Authentication and hosting platform.
- **OpenAI**: Movie recommendation engine.

## Specialized Movie Suggestions

To enable specialized movie suggestions, obtain your OpenAI key and enter it in the designated section of the application.
