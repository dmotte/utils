# ublock-filters

[**uBlock Origin**](https://github.com/gorhill/uBlock) is an extremely useful **ad-blocker** browser extension for _Google Chrome_ (and other browsers). Among other things, it lets the user block **specific content** on websites by defining a list of custom filter rules.

Here is my personal filters list to avoid distractions:

```
! 2022-01-27 https://www.youtube.com - disable video suggestions
www.youtube.com##ytd-watch-next-secondary-results-renderer
www.youtube.com##.grid-disabled.ytd-browse.style-scope

! 2021-07-26 https://stackoverflow.com - disable hot network questions
stackoverflow.com###hot-network-questions
```

These rules should be put in the _uBlock Dashboard_ &rarr; **My filters** section, as shown below:

![screen-01](img/screen-01.png)

The results are the following:

![results-01](img/results-01.png)
![results-02](img/results-02.png)
![results-03](img/results-03.png)
