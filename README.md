# created on January 2024
# @author:          Zahra Firoz
# @email:           zahrafo@uw.edu
# @website:         https://
# @organization:    Geo 458a Lab number 2, University of Washington, Seattle
# @description:     A demo of collecting data from YouTube.

#words
var words = [
  {text: "Lorem", weight: 13},
  {text: "Ipsum", weight: 10.5},
  {text: "Dolor", weight: 9.4},
  {text: "Sit", weight: 8},
  {text: "Amet", weight: 6.2},
  {text: "Consectetur", weight: 5},
  {text: "Adipiscing", weight: 5},
  /* ... */
];

$('#demo').jQCloud(words);

#links
var words = [
  {text: "Lorem", weight: 13, link: 'http://github.com/mistic100/jQCloud'},
  {text: "Ipsum", weight: 10.5, link: 'http://www.strangeplanet.fr'},
  {text: "Dolor", weight: 9.4, link: 'http://piwigo.org'},
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
