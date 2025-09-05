# University Search Platform

This is an advanced, client-side web application for searching and exploring universities across the United States. It uses live data from the U.S. Department of Education's College Scorecard API to provide detailed, up-to-date information.

## Live Demo

A live version of this application can be hosted for free on GitHub Pages. Once deployed, it will be available at:

`https://[Your-GitHub-Username].github.io/[Your-Repo-Name]/`

## Features

- **Live University Data**: Pulls the latest information directly from the official College Scorecard API.
- **Advanced Filtering**: Narrow down searches by a wide range of criteria:
    - Name, State, and City
    - Enrollment size
    - Acceptance rate and average SAT scores
    - In-state and out-of-state tuition, and total cost
    - Location setting (Coastal, Urban, Suburban)
    - Specific academic programs (Business, Political Science, Pre-Law)
- **Personalized Recommendations**: A "Find My Perfect School" button that applies a pre-set list of ideal criteria and uses a "Match Score" algorithm to rank the results.
- **Interactive Map**: Displays all search results on an interactive map, with popups for quick details.
- **Detailed Views**: Click on any university to see a comprehensive modal with details on costs, academics, student outcomes, and campus life.
- **Dynamic Sorting**: Instantly re-sort results by Best Match, Name, Cost, Acceptance Rate, and more.
- **Single-File Application**: The entire application is contained within a single `index.html` file, making it incredibly easy to deploy.

## How to Deploy to GitHub Pages

You can host this web application for free on your own GitHub account in just a few minutes.

1.  **Create a Repository**: Create a new public repository on GitHub.
2.  **Upload Files**: Upload the `index.html` and `README.md` files to your new repository.
3.  **Enable GitHub Pages**:
    - Go to your repository's main page on GitHub.
    - Click on the **Settings** tab.
    - In the left sidebar, click on **Pages**.
    - Under "Build and deployment", select the branch you uploaded your files to (e.g., `main`) as the source.
    - Click **Save**.
4.  **Done!**: GitHub will build and deploy your site. After a minute or two, your University Search Platform will be live at the URL shown in the GitHub Pages settings.

## Technical Details

- **Stack**: Vanilla HTML, CSS, and JavaScript (ES6). No frameworks or build tools are required.
- **APIs**:
    - **College Scorecard API**: The primary source for all university data.
- **Libraries**:
    - **Leaflet.js**: Used for the interactive map feature.
    - **Font Awesome**: Used for icons in the user interface.

### A Note on the API Key

For simplicity and ease of deployment on a static host like GitHub Pages, the College Scorecard API key is included directly in the `index.html` file. This is generally not recommended for production applications where the key should be kept secret. However, for a public data API like this one and a client-side-only project, it is a practical approach.