
# <p align="center"> **Jate Text Editor**
#### <p align="center">Unit 19 PWA Homework:
 
</p>

<p align="center">
  <img width="300" height="300" src="/client/src/images/logo.png">
</p>

## Description

This program is a text editor that runs in a browser window. It is a single application that meets the PWA(Progressive Web Application) criteria and features a number of data persistence techniques that can also serves as redundancy, in such that, when a browser doesnt support it. In other words, this application will function offline.

This application consists of methods that are used for retrieving and storing data to an IndexedDB database, and uses a package called `idb`. The package `idb` is a lightweight wrapper which is used in tandem with the indexedDB API and database. The API used for storing and retrieving data is also used by companies like Google and Mozilla.



## Usage

```c++
The main gist of this program
is being able to create notes 
or code snippets with or without an internet connection
so with reliability
you can retrieve them for later use.
```

So this application - 

```md

  * Uses IndexedDB to create an object store and includes both GET and PUT methods

  * works without an internet connection

  * Automatically saves content inside the text editor when the DOM window is unfocused

  * is Bundled with webpack

  * can Create a service worker with workbox that Caches static assets

  * uses babel in order to use async / await

  * generates `manifest.json` using the `WebpackPwaManifest` plug-in

  * is installed as a Progressive Web Application

```

The following animation demonstrates the application functionality:

![Demonstration of the finished Unit 19 Homework being used in the browser and then installed.](.\client\src\images\assets\00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Unit 19 Homework with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Unit 19 Homework with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Unit 19 Homework with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)


## Links

[Deploy Link](https://text-jeditor.herokuapp.com/)

[GitHub Link](https://github.com/datfoosteve/textEditor)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Contributions
```md
Stephen Puthenpurackal
Eric Sayer(tutor);
```
## Project/Assignment-Status
```md
Project Status - Currently finished and Closed Until Further Notice
Assignment Status - Submitted

Future Plans: Will come back to it once I figure out what I can use this for.
```
