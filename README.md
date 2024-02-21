# Local Web

Description: Collect and present information from a variety of sources for offline use. 


### Project Scope

 - This is a large project composed of several smaller projects. 
     - The idea is to collect as much useful information from the internet via popular information sources (ie Wikipedia, YouTube, Medium, GitHub, etc) and store it in a much more simplified format like HTML/CSS.
         - The overall streamlining should make the content and linking resemble Web 1.0.
     - From there, this main repo will be able to serve up that information for people who are going to be without internet for a long period of time.
     - This is not meant to be a doomsday repo or prepper survivalist data store (though that information may be available at some point). It is more of a compressed library of knowledge and media I find interesting.
 - Data sources:
     - Medium
     - Wikimedia
     - GitHub
         - Will focus primarily on popular or interesting NPM, Python, C/C++, Go, and rust packages and projects.
     - YouTube
         - Focus will mainly be on educational or instructional materials
     - Library of Congress
     - Project Gutenburg
     - Zlib
 - Submodules and projects:
     - Each data source will have its own repo that will endeavor to download the data in a format that remains under GitHub's file size limit of 100MB (we are avoiding using Git LFS because it's a hassle to deal with and manage).
     - Ideally file formats:
         - Webpages: HTML (+ associated CSS files)
         - Raw text: txt or PDF
         - Images: PNG (ideally SVG if possible)
         - Code: respective file extensions
         - Video: MP4
         - Audio: MP3 or WAV
 - Overall Storage requirements/expectations
     - Max hard drive space considered is 4 TB:
         - All text based data should fit well within a 1 TB hard drive.
         - Image data should fit within a 1 TB hard drive.
         - Video data should fit within a 1 TB hard drive.
         - Audio data should fit within a 1 TB hard drive.
     - Min hard drive space considered is 1 TB:
         - The ideal ratio of storage use would minimize larger data sources (image, audio, and video) and prioritize the smaller ones (text).
         - That said, the likely ratio of storage used up will probably be as follows:
             - Text: 33%
             - Image: 25%
             - Audio: 20%
             - Video: 22%
         - Note that the above is not a forecast representing the actual data usage but the targeted ratios we hope to see once data collection starts.
     - Current ACTUAL storage stats:
         - Total Storage (in GB): 
         - Text:
             - % Total Usage:
             - Size (in GB):
             - Number of files:
         - Image:
             - % Total Usage:
             - Size (in GB):
             - Number of files:
         - Audio:
             - % Total Usage:
             - Size (in GB):
             - Number of files:
         - Video:
             - % Total Usage:
             - Size (in GB):
             - Number of files:



### Submodules

 - Medium Webscraper
     - [Github](https://github.com/dmmagdal/MediumScraper.git)
 - Wikipedia Webscraper
     - [Github]()
 - GitHub Webscraper
     - [Github]()
 - YouTube Webscraper
     - [Github]()