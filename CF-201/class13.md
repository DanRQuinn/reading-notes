# Local Storage and How To Use It On Websites

From:[Local Storage And How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

The classic way to do this is by using a cookie. A cookie is a text file hosted on the user’s computer and connected to the domain that your website runs on. You can store information in them, read them out and delete them. Cookies have a few limitations though:

They add to the load of every document accessed on the domain.
They allow up to only 4 KB of data storage.
Because cookies have been used to spy on people’s surfing behavior, security-conscious people and companies turn them off or request to be asked every time whether a cookie should be set.

You can work around this by using the native JSON.stringify() and JSON.parse() methods:


var car = {};
car.wheels = 4;
car.doors = 2;
car.sound = 'vroom';
car.name = 'Lightning McQueen';
console.log( car );
localStorage.setItem( 'car', JSON.stringify(car) );
console.log( JSON.parse( localStorage.getItem( 'car' ) ) );

During development, you might sometimes get stuck and wonder what is going on. Of course, you can always access the data using the right methods, but sometimes you just want to clear the plate. In Opera, you can do this by going to Preferences → Advanced → Storage, where you will see which domains have local data and how much:

- Why would a developer use local storage for a web application?

They add to the load of every document accessed on the domain.
They allow up to only 4 KB of data storage.
Because cookies have been used to spy on people’s surfing behavior, security-conscious people and companies turn them off or request to be asked every time whether a cookie should be set.

One of the first uses for local storage that I discovered was caching data from the Web when it takes a long time to get it. My World Info entry for the Event Apart 10K challenge shows what I mean by that.

- What information should not be stored in local storage?

Personal user data

- Local storage can store what type of data? How would you convert it to that type before storing?

Strings, youcan work around it using JSON.stringify() and JSON.parse() methods.
