---
layout: post
title: GLAMR Machine Learning
subtitle: Experiments in New Zealand and Australia
excerpt_separator: <!--more-->
tags: [tech, GLAMR, machine-learning, AI, data-science, metadata, webinars]
---

{{ page.title }}: {{ page.subtitle }}
================

<p class="meta">04 November 2020</p>

Notes from a webinar on machine learning experiments in GLAMR.

<!--more-->
The three talks covered recent AI initiatives at key cultural institutions in Australia and New Zealand. Common themes included: 
- measuring result accuracy
- identification of data incompatible with AI processes 
- data cleansing 
- ethical implications

The session was organised by AI4LAM chapter in Australia and New Zealand and co-hosted by [Alexis Tindall](https://twitter.com/lexistindall) and [Ingrid Mason](https://twitter.com/1n9r1d).

## Auckland War Memorial Museum
[Adam Moriarty](https://twitter.com/adamrmor) heads up a relatively new team with the aim to help _people find connections with the collections_. They have been working on a number of research projects that facilitated the bigger discussions about what is possible and what is ethical with machine learning.

### Colourising B&W photos
Taking black and white photos from the collection and putting it through an algorithm to generate a colour version of the image.

- [Computers Colouring the Collections](https://medium.com/amlabs/computers-colouring-the-collections-a32054295b1e)
- [Algorithm](https://demos.algorithmia.com/colorize-photos)

### Sentiment Analysis
Analysing a transcribed World War 1 Diary using
IBM Watson (free tier) to track emotions throughout the text.

- [Tone Analyser](https://www.ibm.com/watson/services/tone-analyzer/)

### Auto-tagging collections
_Is it better to have an AI created and captioned record online than no record at all?_

- [AI and Museum Collections.](https://medium.com/amlabs/ai-and-museum-collections-c74bdb724c07)
- [Tool](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/?v=18.05)

### Chatbot
- [Carbine. The Image Tagging Horse.](https://medium.com/amlabs/carbine-the-image-tagging-horse-be62a7089027)

### Ethics
- [Can Museums afford the real cost of the gig economy?](https://medium.com/amlabs/should-museums-use-the-gig-economy-54ceca876319)
- [A Crisis of Capacity – How can Museums use Machine Learning, the Gig economy and the power of the crowd to tackle our backlogs.](https://mw19.mwconf.org/proposal/a-crisis-of-capacity-how-can-museums-use-machine-learning-the-gig-economy-and-the-power-of-the-crowd-to-tackle-our-backlogs/)

## Trove - National Library of Australia
Julia Hickie & Mark Raadgever

### Adding place to trove data
Magazines pose a different challenge to newspapers in that most are centrally published in Sydney and Melbourne. This means that the Marc place of publication can not be relied on as a trusted source of place. The National Library used machine learning to automate the process of assigning place metadata to magazines.

It's worth noting that duplicate place names were not handled with automation.

- [Jupyter Notebook](https://jupyter.org/)
- [SpaCy](https://spacy.io/)
- [Australian Placename Gazetter](https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/76695)

## National Archives
Tatiana Antsoupova

A trial to map documents to retention and disposal schedule functions using text mining resulted in 66% accuracy however, machine learning algorithms resulted in 73-85% accuracy.

- [More human than human? Artificial intelligence in the archive](https://www.tandfonline.com/doi/full/10.1080/01576895.2018.1502088)

## Further Reading
- [Recording of session](https://youtu.be/ilvxiKbJxwo) on YouTube
- [#AI4LAM](https://twitter.com/hashtag/AI4LAM) hashtag on twitter
- [Event Details](https://www.eventbrite.com/e/glamr-machine-learning-experiments-in-new-zealand-and-australia-tickets-124952888453#) on Eventbrite
- [AI4LAM](https://sites.google.com/view/ai4lam) website
