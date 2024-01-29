# created on January 2024
# @author:          Zahra Firoz
# @email:           zahraf@uw.edu
# @website:         https://
# @organization:    Geo 458a Lab number 2, University of Washington, Seattle
# @description:     A demo of collecting data from YouTube.

#words
var words = [
  {text: "Beautiful", weight: 13},
  {text: "Afghan", weight: 10.5},
  {text: "Mountains", weight: 9.4},
  /* ... */
];

$('#demo').jQCloud(words);


%%shell
sudo apt -y update
sudo apt install -y wget curl unzip
wget http://archive.ubuntu.com/ubuntu/pool/main/libu/libu2f-host/libu2f-udev_1.1.4-1_all.deb
dpkg -i libu2f-udev_1.1.4-1_all.deb
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
dpkg -i google-chrome-stable_current_amd64.deb

pip install selenium chromedriver_autoinstaller


#Analysis and Understanding

##The topic as well as the parameters you have used for search;
  The topic that I chose for this lab was a deep dive into the topics and themes that surround Afghanistan and the countries geography. As an Afghan American I know full well that the media coverage and the commentary on Afghanistan is usually far from positive.

##Why do you want to make this comparison;
  Since I visit Afghanistan every year I have seen firsthand the beauty of the lands and the impressive geography that this country lies on. The main hope for this research is being able to show the topics that are highlighted in regards to Afghanistan and a country that is so often painted as a villain, but holds such a deep and powerful history and so much amazing geography. Moreover, this will also touch on technology and access that we so often take for granted in countries such as America. Everywhere has a geography and information systems that should be in place however in countries such as Afghanistan where technology is often reserved for a select few elite that can afford it, it is our job as geographers to acknowledge this gap and the many issues that come with geography becoming such a digitized domain, especially in regards to communities with little to no access to technology. 

##Compare the word clouds and discuss the difference or similarity among the word clouds;
  The word clouds that were produced based on this study were very similar to one another with little to no variation. There were more varrying results in the twitter as it is easier to produce a tweet than a video and therefore can have differing results. The most ccommon word was Afghanistan and geography which could be expected.

##What might be the possible reasons for the patterns you observed;
  There are a multitude of reasons that patterns can be formed on the web. Youtube is often the go to video platform for quick understanding and therefore would be most commonly featuring content that is being searched for or watched the most. Every website has an algorithm and that is made to keep people coming back and intrigued with the content provided by the website. There is also the idea of forcing content pushed by organizations, companies, brands, governments, and so on in order to put a narrative out there. This means that the most viewed, liked, interacted with, etc, content is being forced onto people in hopes that they engage and it keeps building therefore making brands and companys money, and putting the narrative that these higher ups and people in power want out there. 

##How your research could be improved in the future;
  More data is always a great way to improve research, by adding more files more websites and hosts we can ensure a smaller gap of error in our findings and draw more distinct and accurate conclusions. I would also like to work the other way around and instead of finding the most prominent content find the content that is being pushed to the back and hard to find and why that is. There is also so much room for growth in terms of the platforms we used in this study, we could use apps and VPN's next time to see how this word cloud changes as the web thinks we are in different parts of the world. This would be a great way to understand how physical geography works with these systems to promote certain topics and themes. 
  
##Anything you find from the map or data that is different from your expectation before the exercise, or anything that stands out to you;
  I was honestly surprised that I was able to find as much as I did. I knew that there was not going to be a vast array of finds with such a niche topic such as geography and GIS in Afghanistan but nonetheless it was interesting to see what is out there and the information that is available for anyone to interperet. I am saddened to see that there is not as much recent study and available content as a lot of what was found way a few years old at the least but again, this was to be expected. 
