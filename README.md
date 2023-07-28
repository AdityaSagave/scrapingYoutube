# YouTube Scraper 🎞️

This project is a Python script that scrapes information from YouTube videos. It can be used to get the title, views, length, description, and rating of a YouTube video.

## Installation 💾

To install the project, you will need to have Python 3 installed. You can then install the pytube3 package by running the following command in your terminal:


pip install pytube3


## Usage 💡

To use the project, you will need to provide the link to the YouTube video you want to scrape. You can do this by passing the link to the video to the `YouTube()` constructor.

For example, to scrape the information about the video with the link `https://www.youtube.com/watch?v=2FbWhnTUebo`, you would do the following:

python
import pytube

yt = pytube.YouTube("https://www.youtube.com/watch?v=2FbWhnTUebo")

print("Title:", yt.title)
print("Views:", yt.views)
print("Length:", yt.length)
print("Description:", yt.description)
print("Rating:", yt.rating)
```

This will print the information about the YouTube video to the console.

## Other Projects 🔗

This project is part of a series of scraping projects. The other projects in the series will be added one by one

## License 📝

This project is licensed under the MIT License. ⚖️
```

I hope you like it!
