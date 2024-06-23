---
date: 2024-06-23
title: "New project: MyBang!"
categories:
    - development
tags: 
    - projects
    - mybang
---
MyBang! is a handy service for abbreviating website addresses and searches, inspired by the bangs ideas in DuckDuckGo. It makes it easy to create your own abbreviations and jump straight to search results.

## Idea and inspiration
The original DuckDuckGo search engine allows you to refer to different websites using short cuts called bangs. A bang is, in its original form, an exclamation point and a shortcut. Bangs allow you to use a shortcut starting with the exclamation point instead of typing the full address of a site. For example, instead of writing the full address "google.com", you can just write "!g" and it will redirect you to Google. If you add a query string to that as well, you can go straight to the search results page.

## Problems with the DuckDuckGo
The main problem with the original service is that it doesn't allow users to add or edit bangs. They have a certain set of preset abbreviations that are very difficult to change or add to (it's either impossible or can take up to several months). This limits the possibilities and is not always convenient.

## How MyBang! works
MyBang! service works on a similar principle. In the browser's query string, instead of the full website address, you enter bang - an exclamation point and a shortcut. A search string can be added after the shortcut.

Try it yourself! Copy this string into your browser address bar: `bang.bedware.software/!yama notebook` or `bang.bedware.software/!learn python`.

The `bang.bedware.software/` prefix can be removed by making MyBang! the default search engine in the browser.

However, unlike the original service, in MyBang! you will have the ability to create your own bangs and customize them to your needs. There are no restrictions.

## My current implementation
I have currently created an MVP that uses a static list in a YAML file. This list is read when the application loads and allows me to use my own bangs. I have already set this service as the default search engine in my browser and have been actively using it for over half a year.

## Future Plans
My goal is to make a complete web service with a beautiful interface and advanced functionality. Here are some of the features I plan to add:
* Ability to register users and authorization (possibly via cryptocurrency wallet).
* Ability to add, delete and edit bangs.
    * Through the interface.
    * Through a request
* Dashboard with statistics (personal)
* Leaderboards for bangs (public, shared)

## Conclusion
MyBang! will be a great tool for those who often use search on various sites and want to make this process faster and more convenient.


I hope you enjoy my project and find it useful. Stay in touch and stay tuned for updates!

GitHub: https://github.com/bedware-software/mybang
