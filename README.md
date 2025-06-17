# SteamHub



## Project Description

SteamHub is a dynamic and responsive web application designed to help users discover movies and TV shows. Inspired by popular streaming interfaces, it leverages The Movie Database (TMDB) API to provide up-to-date information, detailed content pages, and personalized list management.

Users can browse content by popular trends or specific genres, search for titles, and curate their own "My List," "Favorites," and "Bookmarks." The application is built entirely with vanilla HTML, CSS, and JavaScript, focusing on performance and a smooth user experience.

## Live Demo

You can explore a live demo of the application here:
[YOUR_LIVE_DEMO_URL_HERE](YOUR_LIVE_DEMO_URL_HERE) *(Replace with your actual deployed URL)*

## Features

* **Browse Movies & TV Shows:** Discover popular movies and TV shows.
* **Genre-Based Filtering:** Filter content by various genres (e.g., Sci-Fi, Horror, Comedy, Drama, Action & Adventure).
* **Dynamic Genre Toggling:** Sidebar genre lists for Movies and TV Shows can be expanded/collapsed independently, and only one primary category's genres are shown at a time.
* **Search Functionality:** Powerful search to find specific movies or TV shows by title.
* **Detailed Content Pages:** View comprehensive details for each movie/TV show, including:
    * Poster, title, rating, year, runtime/episode info.
    * Plot summary, genres, cast, and director/creator.
    * Action buttons to add to "My List", "Favorites", or "Bookmarks".
    * An embedded YouTube trailer (if available).
    * "You May Also Like" section with recommended content.
* **Personalized Lists:**
    * **My List:** A general watchlist for content you want to keep track of.
    * **Favorites:** Mark your most loved movies and TV shows.
    * **Bookmarks:** Save content for later viewing or reference.
    * All lists persist using browser Local Storage.
* **Responsive Design:** Optimized for seamless viewing and interaction across desktop, tablet, and mobile devices.
* **Loading Spinners & Placeholders:** Provides visual feedback during data fetching and displays informative messages for no results or API key issues.
* **Confirmation Messages:** Brief pop-up notifications confirm when items are added to or removed from lists.

## Screenshots

*(Here, you would add more screenshots. You can drag and drop images directly into your GitHub README editor, or upload them to an `images/` folder in your repo and link them like the example below.)*

![Tvflix Detail Page Screenshot](path/to/your/detail-page-screenshot.png)
*(Example: `images/detail-page.png`)*

![Tvflix Mobile Menu Screenshot](path/to/your/mobile-menu-screenshot.png)
*(Example: `images/mobile-menu.png`)*

## Technologies Used

* **HTML5:** For the basic structure of the web pages.
* **CSS3:** For styling and responsive design.
* **JavaScript (Vanilla JS):** For all interactive functionalities, API calls, and DOM manipulation.
* **The Movie Database (TMDB) API:** Powers all content data (movies, TV shows, details, search, recommendations).
* **Font Awesome:** For icons (e.g., search, star, list, heart, bookmark).

## Setup and Installation

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Boda1607/streamhub.git](https://github.com/Boda1607/streamhub.git)
    cd streamhub
    ```
    

2.  **Get a TMDB API Key:**
    * Go to [The Movie Database (TMDB) website](https://www.themoviedb.org/).
    * Sign up for a free account.
    * Navigate to your **Settings > API** section.
    * Request a new API key (Developer/v3 API).
    * Copy your **API Key (v3 auth)**.

3.  **Insert your API Key into the code:**
    * Open the `index.html` file in your preferred code editor.
    * Find the line `const TMDB_API_KEY = 'YOUR_TMDB_API_KEY';` (around line 777 in the provided code).
    * Replace `'YOUR_TMDB_API_KEY'` with the actual API key you obtained from TMDB.
        ```javascript
        const TMDB_API_KEY = 'YOUR_ACTUAL_TMDB_API_KEY_HERE'; // Example: 'a1b2c3d4e5f6g7h8i9j0k1l2m3n4o5p6'
        ```

4.  **Open in Browser:**
    * Simply open the `index.html` file in your web browser. You can do this by double-clicking the file or by using a "Live Server" extension in your code editor (like VS Code) for easier development.

## Usage

* **Browse:** Use the sidebar to switch between "Movies" and "TV Shows." Click on genres to filter the content displayed in the main grid.
* **Search:** Type into the search bar at the top to find specific titles.
* **Details:** Click on any movie or TV show card to view its detailed page.
* **Manage Lists:** On the detail page, use the list, heart, and bookmark icons to add/remove content from your personalized lists.
* **View Lists:** Click the "My List," "Favorites," or "Bookmarks" buttons in the header to view your curated collections.
* **Mobile Navigation:** On smaller screens, use the hamburger menu icon (☰) to open the sidebar.

## Important Note about the API Key

The TMDB API key in this project is used for public data access and is typically considered low risk. However, it's a general security best practice to:

* **Avoid exposing sensitive API keys directly in client-side code** for production applications. For this demo project, it's directly in the HTML for simplicity.
* **Be mindful of rate limits:** Excessive use of your key (e.g., by many users or automated scripts) might cause TMDB to temporarily block your key if you exceed their request limits.
* If you suspect your API key has been compromised or abused, **regenerate it immediately** from your TMDB account settings.

## Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add new feature'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE). *(It's good practice to create a `LICENSE` file in your repo with the full license text.)*

## Contact

If you have any questions or feedback, feel free to reach out:

* **AbdElRahman:** [https://abdelrahmanz.netlify.app/](https://abdelrahmanz.netlify.app/)
* **GitHub:** [https://github.com/Boda1607](https://github.com/Boda1607)