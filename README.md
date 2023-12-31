<a name="readme-top"></a>

<h1 align="center">
	<img
		width="100"
		alt="NexTechNews"
		src="./images/company_logo-removebg.png">
</h1>

<h3 align="center">
	NexTechNews - The Premier Tech News Aggregator
</h3>

<p align="center">
	<strong>
		<a href="http://34.201.127.165/">Website</a>
	</strong>
</p>

<div style="display: inline-block; background-color: black; padding: 2px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);">
    <!-- Inline styles for the image -->
    <img src="./images/screenshot.png" alt="Homepage" style="width: 100%; height: auto; display: block;">
  </div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#frontend-folder-stucture">Frontend Folder Sructure</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project
NexTechNews is a news aggregator that provides the latest news from the world of technology. It is built using Next.js, Tailwind CSS and NextUI. It uses the NewsAPI to fetch the latest news from various sources. The website is hosted on AWS EC2 instance. (Our website is not fully responsive yet, so please view it on a laptop or desktop for the best experience.)

### Features
* Get Top Headlines from the world of technology
* Search for news by keywords
* Filter news by source
* Sort news by date, popularity and relevancy
* Explore news by date ranges
* Read full article on our website itself
* Switch between light and dark mode
* Get Started button for easy navigation

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [Next.js](https://nextjs.org/)
* [React](https://reactjs.org/)
* [Tailwind CSS](https://tailwindcss.com/)
* [NextUI](https://nextui.org/)
* [NewsAPI](https://www.newsapi.ai/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

Follow these instructions to set up and run the project locally on your machine.

### Prerequisites

* npm

  ```bash
  npm install npm@latest -g
  ```

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/mittal-ishaan/dotflo-assignment.git
    ```

2. Navigate to the project directory:

    ```bash
    cd nextechnews
    ```

3. Create a virtual environment (optional but recommended -- Step 4-5):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On Unix or MacOS:

        ```bash
        source venv/bin/activate
        ```
5. Install the required packages:
    
    ```bash
    npm install
    ```
6. Run the development server:

    ```bash
    npm run dev
    ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Frontend Folder Stucture
```
└── nextechnews/
    ├── public
    │   ├── images/
    ├── src/
    │   ├── app/
    │   │   ├── favicon.ico
    │   │   ├── globals.css
    │   │   ├── layout.jsx
    │   │   ├── providers.jsx
    │   │   └── page.jsx
    │   └── components/
    │       ├── Home/
    │       │   ├── Cards.jsx
    │       │   ├── NewsList.jsx
    │       │   ├── NewsPreview.jsx
    │       │   ├── NewsProviders.jsx
    │       │   ├── ListboxWrapper.jsx
    │       ├──Explore.jsx
    │       ├──icons.jsx
    │       ├──NavBar.jsx
    │       ├──Search.jsx
    │       ├──SearchIcon.jsx
    │       └── Headline.jsx
    ├── .gitignore
    ├── README.md
    ├── jsconfig.json
    ├── .eslintrc.json
    ├── .env.local
    ├── next.config.js
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    └── tailwind.config.js
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap
- [X] Make a basic UI
- [X] Add NewsAPI.ai
- [X] Add search functionality
- [X] Add full article view functionality
- [X] Add filter, sort, date range functionality
- [X] Add dark mode
- [X] Add get started button
- [X] Add responsiveness for laptop and desktop
- [ ] Add responsiveness for mobile and tablet


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Ishaan Mittal - [me210003039@iiti.ac.in](mailto:me210003039@iiti.ac.in)

Github - [https://github.com/mittal-ishaan/dotflo-assignment](https://github.com/mittal-ishaan/dotflo-assignment)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
