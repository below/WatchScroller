# WatchScroller
A sample to illustrate a WatchKit / IB question

#The Question
Why can the green button on the first page be scrolled vertically? It is small enough not to need any sort of scrolling.

_IMPORTANT_ This only happens on the device (I tried 42mm). In the simulator (42mm), the button stays as intended

#The Answer
It is clearly a bug and I will file it as such. I have added a second controller on the second page which shows the expected behavior. If you reverse the pages, it is obvious that this is a bug of the first page, regardless which controller is used for it.

#Thanks
Icon used is „escalator at the end of a tunnel“ by Kai Schreiber
https://flic.kr/p/i2BT
Used as permitted by CC-BY-SA 2.0 https://creativecommons.org/licenses/by-sa/2.0/