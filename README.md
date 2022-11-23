# Homework Tracker

This is a homework tracker for the <a href="#" target="_blank">#Learn Together training community</a>. The tracker uses localStorage to keep track of checkbox status, so as long as you keep using the same browser, your completions will be tracked.

**Link to live tracker:** <a href="https://rahulkarda.github.io/homework-tracker/" target="_blank">Homework tracker</a>

Image of the Homework Tracker
![Image of the homework tracker](https://github.com/rahulkarda/homework-tracker/blob/master/site_preview.png?raw=true)

## How It's Made:

**Built with:** <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>

The project is primarily built using HTML and CSS. The essential Javascript is the storage of checkbox checked/unchecked status in localStorage, since without that users would not be able to keep track of their progress. 

Javascript is used to keep track of the completed status of individual classes. When all homework is checked off for a particular class, the class is faded to indicate that it has been completed, giving visual feedback and making it easier to scroll through the list and spot incomplete homework. It is also possible to mark an entire class complete or incomplete with a single checkbox, which is useful for anyone who starts using the tracker after they have completed some of the homework.

## Optimizations

- hide completed
- backup and load completion status
- optional tracking of push work
- improve the tooltips

## Lessons Learned:

The process of adding new homework is cumbersome, but we don't want to introduce any breaking changes that would affect current users. If we had spent more time in the beginning considering what the updating process would involve, we would have opted for a database and HTML template.

## How to Contribute

If you spot any errors in the tracker, please fork the repo and create a pull request, or you can also simply open an issue.

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2022-present, Rahul Karda
