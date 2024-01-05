# media-production-pipeline

This is an attempt to document and outline a bare-bones, minimal-overhead pipeline for generating multimedia content and sharing it across a limited handful of useful networks.

There are effectively five steps, each of which leverages the previous steps.

## Pipeline

This process is the result of an attempt to keep myself accountable to writing more devblog-style tips and other "things I've learned / stuff I use" content.

### GitHub

The first action is typically GitHub. Most of this content is technically-oriented and invovles some degree of software engineering. Even topics that don't (such as this one) will have some sort of a writeup (Markdown, more often than not) that benefits from version control.

### Dev.to

This is basically where my dev blog lives now. It's nicely compatible with Markdown and works well with other networks. The signal-to-noise isn't too low and it's a responsive & streamlined experience. This effectively generates an authoritative publication of the README content from the GitHub project, which it cites, including other helpful diagrams; explanations; and other walkthroughs.

### Twitch.tv

Once I've used the article to better articulate and structure my thoughts about the technology involved, I set up a basic three-display single-camera stream configuration and broadcast a live version. This is typically a single-take that averages to 30 minutes (really 20-40). I can pull on the GitHub code and Dev.to content (like memes) but really this is me going through and recreating the development process so viewers can follow along as the softare is written. I find that's a much more helpful way to share thoughts and growth. OBS Studio is the tool of choice here.

### YouTube

With the right settings, Twitch will store a VOD you can download and process. In the interest of spending as little time as possible on production, I don't add any cuts or scene transitions or anything else--it's just "download from Twitch" followed by "upload to YouTube", but with one intermediate step I find I can't avoid.

Specifically, in OpenShot and Audacity, I splice off the audio channel for some processing. This typically looks something like 1) noise reduction, 2) normalization, 3) click removal, and 4) pass filtering. Otherwise the YouTube content just isn't as consumable and I find it to be very annoying to listen to myself when I have to crank up the volume! It would be nice if more of these was included in the YouTube upload processing, but it isn't.

### Twitter

Once the YouTube content is up, I'm ready to share the content on a general-purpose social network. This typically involves a link to the YouTube upload and the Dev.to article, both of which have excellent integration. The YouTube channel can link back to the Twith stream, and the Dev.to article already has a link to the GitHub. This provides a good record and means from which to share and broadcast any content follow-on (like comments or sequels), and is where most of the sharing and exposure takes place.

## Conclusions

I find the "compression ratio"--that is, the time you spend to make one unit (say, minute) of video--can vary wildly in general. The purpose of this particualr pipeline is to get that ratio as low as possible while still sharing not-entirely-devoid-of-value content. For purposes of consumption, I find this means a YouTube video between 20-40 minutes, which takes an extra 30 minutes to process. That comes from an article that is probably 1000-2000 words in length and takes 1-2 hours to write up. The original GitHub project (depending on the topic) is where there is the most variance, but if I'm effectively recreating something I've already learned or done this could be as little as 1-2 hours for something I'm okay sharing in public (e.g., polish).

All in all, this means a half-day's work for a single publication, from start to finish (not including any learning time or other research for the initial project / technology), which honestly isn't bad at all.


