# vv-presence

The idea for this project came from a [reply](https://twitter.com/0xlght/status/1527776487201558528?s=20&t=FWWbsmnnYwjCdYoTCYASNA) to a Jack Butcher [tweet](https://twitter.com/jackbutcher/status/1527774947413721089?s=20&t=FWWbsmnnYwjCdYoTCYASNA).

Inspired by [Sunday FM](sunday.fm), this website will play an endless loop of white noise, encouraging listeners to be present.

## Approach
I wanted to emulate the simple layout of Sunday FM. But use the Visualize Value font family and black and white palette and the visual Jack used in his initial tweet. 

At the time of creating this project, I am approx. 60% through the Foundation section of [The Odin Project](https://theodinproject.com). Using my knowledge of basic HTML and CSS styling and Flexbox, along with some additional internet searching, I have been able to create this project.

## Learnings
This was a good project to undertake at this point in my 'learning to code' journey. I was able to create and style page without any issue. 

Where things got tricky was when it came to embedding audio from a YouTube 24hr stream into the page. After Googling, I found [this](https://www.labnol.org/internet/youtube-audio-player/26740/). After trying to make sense of the article and the code, I inserted the code into my HTML page and edited the VIDEO_ID parameters, meaning the correct YouTube video played. This worked, but I did have a problem, the 'Play' button that was rendered did not suit the Visualize Value aesthetic, but I didn't know how to change it.

After a few days of thinking through the problem, I re-read the article. The author mentions hosting the scripts and images on your local server. I did this, and then re-read the scripts. I then had the idea to use Figma to create 'Play' and 'Pause' images. after creating this, I edited the script to point to the project's Images folder. After refreshing the page, it worked. I then resized the images of play and pause images so they matched the rest of the page. 

Summary of learnings:
- Using, and modifying scripts created by others to solve a problem I was having.
- HTML
- CSS, Flexbox
- Open Graph protocol