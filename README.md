# Obfuscator
Protect your online privacy by obfustcating social media by the *"deliberate use of ambiguous, confusing, or misleading information to interfere with surveillance and data collection projects"* ([Obfuscation: A User’s Guide for Privacy and Protest](https://mitpress.mit.edu/books/obfuscation), Nissenbaum & Brunton, 2015).

## Goal
In this case, the goal of obfuscation is to protect your (online) privacy. The goal of this tool is to collect real data, mix it so it has no meaning anymore, so it can be used to (automatically) update social media, so your profile gets obfuscated with data so the social media companies don't have a representative profile of you.
You can use obfuscation in combination with ad & tracker blocking, VPN connections, Tor, etc. Check [Privacytools.io](https://www.privacytools.io/) for more tips.

## Setup
The idea is to create an application anyone can host for himself, so you can manage your own sources, social media channels and other settings (language, region, update interval, etc). And, if your app is blocked by a social media company, it will not affect other deployments.

# Main functions
## 1: Collect data
The Obfuscator could periodically collect many different types of data:
* text from RSS feeds;
* links to pictures, e.g. from the [Flickr recent](https://www.flickr.com/services/api/flickr.photos.getRecent.htm) creative commons feed, for instance;
* links to video's, for instance from youtube search for a random word;
* GPS points and routes from [OpenStreetMap Traces](https://www.openstreetmap.org/traces);
* plain text (a list of words or complete epistles) users can paste from wherever;
* tabular data;
* fitness & health data from 'quantified self' devices;
* links to soundbites (e.g. from SoundCloud);
* source code from GitHub;
* personal names;
* domain names;
* e-mail address;
* phone numbers;
* physical addresses;
* etc.

## 2: Obfuscate data
The Obfuscator combines collected data and mixes it into data without any real meaning, but it looks as if it is relevant. 
Example outputs:
* an RSS feed containing radom, but a shomewhat coherent, titles and teasers with a link to a news item from another (real) RSS feed;
* a random photo, video or sound, based on a search for a random word in the users language;
* a file with GPS data: coordinates, date and time, altitude, possibly even heartrate;
* coherent but meaningless text (by using the [Markov chain](https://en.wikipedia.org/wiki/Markov_chain);
* data with user-specified numer of columns and rows with supposedly correlated data, with optional column titles, a fake identifier per row and date/time columns;
* xml style e-health data;
* combination of random source code snipplets;
* fake personal names using the different [personal naming systems](https://en.wikipedia.org/wiki/Personal_name#Naming_conventions);
* a fake domain name and fake e-mail addresses;
* random phone numbers most common formats;
* physical address, based on the results of a search on a map (using a random word or coordinates);

## 3. Use the data
The collected data can be used to:
* send e-mails to yourself with fony content;
* post video's to your timeline;
* update your photostream with pictures with and a random text (and emoticons);
* publish documents, spreadsheets to your online file storage and synchronization service;
* upload sports routes to your health trackers;
* join conversations as a chatbot;
* generate fake data (names, e-mail addresses, physical addresses, phone numbers, etc.) to be used in subscription forms;
* etc.
