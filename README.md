MorseJs - A javascript object to play Morse Code
================================================

There are many so-called "Morse Code translators" across the Internet. However most of them have the same flaw: Morse Code is not meant to be a written language, rather it is an audible language. This library or object or whatever you want to call it can be used to fill that gap. 

### Usage

Simply include the script on your web page, then execute the object in one of the methods shown here:

    MorseJs.Play(string TextToSend, [int SpeedInWordsPerMinute, int ToneFrequency]);             
    MorseJs.Play("cq cq de n5jlc k");                                                            
    MorseJs.Play("cq cq de n5jlc k", 25);                                                        
    MorseJs.Play("cq cq de n5jlc k", 25, 500); 

### Demo

You can see and play with a live demo on CodePen (which, next to IFTTT and Stack Overflow, very well could be the best site on the Internet. The URL is [https://codepen.io/JoshuaCarroll/pen/QgrdzL](https://codepen.io/JoshuaCarroll/pen/QgrdzL).

#### Contributing

Contributions to this project can be made by using it and providing feedback or by assisting in the programming. Pull requests are very welcome! Please try to follow these simple rules if applicable:

* Submit pull requests to the Development branch.
* Please create a separate Pull Request for every unrelated change you make.
* Make sure your patches are well tested.
* Update the README if applicable.
* Please do not change the version number.
