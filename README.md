# GPTales

Welcome to GPTales, an enthralling anthology of AI-crafted narratives spanning a variety of genres from the realms of fantasy to the mysteries of science fiction.

## Description

In this unique intersection of technology and creativity, GPTales presents a collection of stories generated by advanced AI models. These narratives delve into an array of worlds, exploring the breadth and depth of storytelling as it comes to life through the power of artificial intelligence.

## Project Structure

This repository is structured in the following way:

📂
├── **_genres**
│   ├── Fantasy.md
│   ├── SciFi.md
│   ├── Mystery.md
│   └── Drama.md
├── **_layouts**
│   ├── default.html
│   └── post.html
├── **_posts**
│   ├── Story1.md
│   ├── Story2.md
│   └── ...
├── **_config.yml**
├── **assets**
│   └── **css**
│       └── styles.css
└── **index.html**

## How It Works

Each story is represented by a markdown file under `_posts`. The genre of the story is set using the `genre` field in the front matter of the markdown file. The list of available genres is derived from the markdown files under `_genres`. Each genre is represented by a markdown file with a `name` field in the front matter.

When you navigate to the home page of the site, it lists all genres and their respective stories.

To add a new story, create a new markdown file under `_posts` with the appropriate `genre` set in the front matter. If you are adding a story in a new genre, remember to create a new markdown file for that genre under `_genres`.

## Contribute

We welcome and appreciate any contributions. Feel free to submit pull requests for new AI-generated stories, improvements on existing ones, or bug fixes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the terms of the MIT license.
