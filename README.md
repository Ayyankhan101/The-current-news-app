# The Current

"The Current" is a modern, responsive news application built with Next.js, designed to deliver up-to-date news articles from various sources. It provides a seamless browsing experience, allowing users to search for specific news topics and explore headlines.

## Features

*   **Dynamic News Fetching:** Fetches real-time news articles using the NewsAPI.
*   **Search Functionality:** Allows users to search for news articles based on keywords.
*   **Responsive Design:** Optimized for viewing on various devices, from desktops to mobile phones.
*   **Clean User Interface:** A modern and intuitive design for an enhanced user experience.

## Technologies Used

*   **Next.js:** React framework for production.
*   **React:** JavaScript library for building user interfaces.
*   **Tailwind CSS:** A utility-first CSS framework for rapid UI development.
*   **TypeScript:** A typed superset of JavaScript that compiles to plain JavaScript.
*   **NewsAPI:** For fetching news content.

## Getting Started

Follow these steps to get "The Current" up and running on your local machine.

### Prerequisites

Make sure you have the following installed:

*   Node.js (LTS version recommended)
*   npm or Yarn

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/the-current.git
    cd the-current
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

### API Key Configuration

This application relies on the [NewsAPI](https://newsapi.org/) to fetch news articles. You will need to obtain a free API key and configure it.

1.  **Get your API Key:**
    *   Go to [NewsAPI.org](https://newsapi.org/register) and register for a free developer API key.

2.  **Create a `.env.local` file:**
    *   In the root directory of your project, create a new file named `.env.local`.

3.  **Add your API key to the `.env.local` file:**
    *   Open the `.env.local` file and add the following line, replacing `YOUR_NEWSAPI_KEY` with the actual API key you obtained:

    ```
    NEXT_PUBLIC_NEWS_API_KEY=YOUR_NEWSAPI_KEY
    ```

    *   **Important:** Do not commit your `.env.local` file to version control. It's already included in `.gitignore`.

### Running the Development Server

Once the API key is configured, you can run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.