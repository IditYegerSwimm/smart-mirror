# smart-mirror

This is a website for making your mirror a SMART mirror.
In order to use it, you should attach a simple tablet to a mirror. Then, open this one-page website on your tablet's browser and give it arguments in the url. You should define your browser to fill the screen entirely and define the screen to stay turned on all the time.
This website creates a grid on the browser's window with a transperant border. Each cell of the grid can contain one element. You can leave cells empty if you wish. You can decide which elements you want to show in which cell. 

## The elements that are available are: 
- Digital clock
- Analog clock
- A random article from Wikipedia
- Weather forecast

## The arguments that you can assign to the url:

**rows** - Specify a number between 1 to 4 which will be the number of rows of the grid

**cols** - Specify a number between 1 to 4 which will be the number of coloums of the grid

**digclock** - Specify a number between 1 to the rows*cols that you've entered above to select the digital clock's cell. A number outside of those boundries will specify that the digital clock should not be displayed

**anclock** - Specify a number between 1 to the rows*cols that you've entered above to select the analog clock's cell. A number outside of those boundries will specify that the analog clock should not be displayed

**wiki** - Specify a number between 1 to the rows*cols that you've entered above to select the wikipedia's random article cell. A number outside of those boundries will specify that no article should be displayed

**weather** - Specify a number between 1 to the rows*cols that you've entered above to select the weather forecast's cell. A number outside of those boundries will specify that no weather forecast should be displayed. In order for this function to work, the site should run using a secure connection (https)

## A url example:
https://idity.github.io/smart-mirror/?rows=2&cols=2&digclock=1&anclock2=2&wiki=3&weather=4


**You are welcome to add more features to this website.**

