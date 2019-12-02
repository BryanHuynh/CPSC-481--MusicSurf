[Home](https://colinauyeng.github.io/CPSC-481--MusicSurf/) - [Stage1](https://colinauyeng.github.io/CPSC-481--MusicSurf/Stage1) - [Stage2](https://colinauyeng.github.io/CPSC-481--MusicSurf/Stage2) - [Stage3](https://colinauyeng.github.io/CPSC-481--MusicSurf/Stage3) - [Stage4](https://colinauyeng.github.io/CPSC-481--MusicSurf/Stage4) - [Stage5](https://colinauyeng.github.io/CPSC-481--MusicSurf/Stage5)  
## Stage 5: Final Project Iteration

[Final High Fidelity Prototype](https://drive.google.com/file/d/1YGWRNDLZexqBZQJFfyZv6C5ae9IFz7nT/view?usp=sharing)

[Stage 5 Presentation](https://docs.google.com/presentation/d/1r_z5hTgDfi-9M7GlhujWok-vSH9DAdP3jtr8uc9FcOg/edit?usp=sharing)

### Executive Summary

MusicSurf is an innovative music platform that enables its users to explore and organize music in a visual way. Currently, conventional music platforms like Spotify, Apple Music, and Youtube Music rely on lists to display music and black box algorithms to recommend it. However, this restricts users from freely navigating, discovering, and customizing their music listening experience. Our solution has benefits for music labels and music artists looking to distribute their music and find a new audience. MusicSurf is also tailored to music listeners, no matter their music exploration or library organization preferences. To better understand our end-users, we conducted interviews and secondary research. From the interviews, we found that people often find new music through friends and the recommendation algorithm of their prefered music platform. Interviewees also judged platforms based on ease of use and music selection. From our academic research, we learned that automatic grouping systems for music are feasible and that mood based categorization is a complex, but desirable, system for music organization. Based on these findings, we developed MusicSurf, focusing on the design and functionality of the exploration, library, and now playing features. 

For the library page, songs, playlists, and tag groups are displayed as nodes connected in a graph. This allows for the visual and spatial exploration and organization of the music collection at various levels. Additionally, graphs are commonly used to show information, so this should be fairly intuitive for the user. We used colours to differentiate moods and tags, which makes it easy to see how similar two songs are and draws upon existing colour associations. For the now playing page, we placed a graphic music player in the center that integrates album art, the play and skip buttons, and the volume and progress sliders. This circular element matches the theme of circular nodes in the library. There is also a hidden tab on the page to view the song queue, which allows users to access non-essential but useful information. Lastly, the song’s tags are displayed at the bottom of the screen and provide additional information on the song’s mood. For the exploration page, songs are displayed in a hexagon grid, which allows for the structured presentation of many songs that are related in different ways. This layout is clearly distinct from the library to ensure the user knows whether they are exploring music or browsing their collection. We anchored progress and volume bars at the bottom of the explore page to allow users to control their listening without having to navigate to the now playing screen. We also added a help menu, as this page contains several novel elements and users may be confused about the functionalities available. After developing a hi-fi prototype, we received a heuristic evaluation that outlined a few key problems. The first problem was the presence of minor functionality errors, inconsistencies, and bugs, however we were able to quickly address these. The main issue was that users were confused about the features of the explore, library, and now playing pages, as they were novel and not properly labeled or documented. To rectify this, we added supporting documentation and adjusted the layout to make it more intuitive and minimalistic. We also included features that users desired, like profile and friends pages. In the future, we hope to increase the supporting documentation, play with the colours and aesthetics, and continue optimizing the design of MusicSurf. 

### Introduction

Interfaces used to browse music typically follow a single paradigm: Lists. Every music player from Apple Music to Spotify uses a list interface that has been standard for time immemorial.  Lists are an excellent interface when you know what you are looking for and simply want to find it, however we felt the wheel could be reinvented when it comes to discovering new music.

Our group sought to iterate and innovate on the standard list interface to design a platform that empowers the user to visualize their music in a new way. Notably, our design emphasizes exploration and gives tools to the user to more freely discover new types of music. This is done by providing an easy to use interface that lets users “surf” through songs based on chosen parameters (i.e. mood, beats per minute, genre, time period, artist, etc.). Through MusicSurf, we wanted to make the discovery of new music intuitive and exciting, pushing users out of their music comfort zone.


### Design Problem

Current music platforms like Spotify or Youtube Music show music in a standard database style system and give recommendations through auto generated playlists. This means that users are not able to explore music freely and often only find new music due to auto generated recommendations, which they don’t have control over. The main design problem can be boiled down into a simple question. How can we create a music discovery platform that throws away the conventional list-based interfaces currently employed by music apps and provides a more visual way of exploring and organizing music? 

### End-users and Stakeholders
End-users may include regular music listeners who love creating playlists, exploring new music and different kinds of genres. This application also helps users who look for specific kind of music by searching for songs using specific tags related to the kind of songs they are interested in as the app can create Smart Playlist or a Custom Playlist caterring to the user's needs.  

Some stakeholders may include music labels and the artists themselves as they work to create and spread their music to their respective fanbases where all these fans are also considered to be the end-users as well. 

### User Research and Findings
After conducting a series of interviews of frequent music listeners, we were able to understand people's music exploration preferences and thoughts on the platforms they used which turned out to be either Spotify, Apple Music or YouTube Music. 
Some secondary research was conducted to investigate important components of exisiting systems in order to understand the concept of these successful applications. By compiling the data from interviews and user research, a low fidelity prototype of MusicSurf was successfully created, followed by a high-fidelity prototype with greater improvements to the user interface and prototype functionalities such as moving back and forth from screens, searching music, logging in, music controls etc. 

### Design and Justification 


### Heuristic Evaluation and Findings
A heuristic evaluation conducted on this prototype by another team of designers resulted in a series of minor bugs and\technical difficulties which include the prototype's consistency, standards, aesthetic design, button functionalities and color schemes. However, there were some severe problems with the prototype that was addressed as confusions rose with the explore menu and some of the buttons which wasn't labelled correctly. 

<img src="heu_eval.png" alt="eval" class="inline"/>

In order to address these problems, we have created a series of changes in the design that will ensure the user to minimize the bugs faced by users. 

### Design Changes
Now playing page without lyrics tab

<img src="nowplaying.PNG" alt="hi" class="inline"/>

Exploration control menu integrated into the explore page

<img src="explorecontrol.PNG" alt="hi" class="inline"/>

Explore page help documentation

<img src="explorehelp.PNG" alt="hi" class="inline"/>

Profile page

<img src="profile1.PNG" alt="hi" class="inline"/>
<img src="profile2.PNG" alt="hi" class="inline"/>
<img src="profile3.PNG" alt="hi" class="inline"/>

Friends page

<img src="friends1.PNG" alt="hi" class="inline"/>
<img src="friends3.PNG" alt="hi" class="inline"/>
<img src="friends4.PNG" alt="hi" class="inline"/>

Settings page

<img src="settings.PNG" alt="hi" class="inline"/>

### Recommendations for Next Iteration
The goal for the next iteration would be to help users understand how the application can be used with better documentation and guidance, reducing the steps to complete certain tasks, re-organize and optimize the screens for efficiency and adjusting color schemes and layouts for a nicer design. 

### Conclusions

