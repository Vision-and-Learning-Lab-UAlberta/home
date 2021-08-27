## Installation

You need to first install Hugo, please follow [Hugo website](https://gohugo.io/getting-started/installing/) to install Hugo.
If you are using Windows, note that you need to install [the extended version of Hugo](https://gohugo.io/getting-started/installing/#chocolatey-windows).


## Edit the content on the website
You can follow the instruction on https://academic-demo.netlify.app/ to check how to edit each of the specific section.

Everything you want to edit is located in `./content` folder, here I give a few examples for you to understand how is everything works.

### Your personal page

If you are a new member in our lab, you may want to create a personal page for yourself by copying one of the existing folder under `./content/authors`. For example, you are copying `./content/authors/jiyang`, then you only need to do 2 things to start. First, you want to replace `avatar.png` with your own photo (other format like `.jpg` is also supported). You also need to change the content in `_index.md`, it is a very straightforward markdown file.


### Your project/publication page

Congratulations to have new publications! Similar to your personal page, you can copy an existing folder under `./content/publication` or `./content/projects` to start. The process is very similar to how you can do with your personal page: edit the content in `index.md` with your updates.


## Live Demo

In your terminal/command line tool, go to the home folder of this repo, then use 

> hugo server

to start a local live server, you may check your website at http://localhost:1313/ (bind address 127.0.0.1).

This live server is not actually fully live, if you just change some contents in files like `index.md`, it is updated immediately without the need of restarting the server. However, if you do create a new subfolder under `./content/authors` or under `./content/publication`, sometime it just breaks, in that case, all you need to do is restart the server from your terminal/command line.

## Deployment

Once you are satisfied with your editing, you can build the website for deployment by using

> hugo

You will see something like the following

```
Start building sites …
hugo v0.87.0-B0C541E4+extended windows/amd64 BuildDate=2021-08-03T10:57:28Z VendorInfo=gohugoio

                   | EN
-------------------+------
  Pages            | 623
  Paginator pages  |  30
  Non-page files   | 126
  Static files     |  26
  Processed images |  65
  Aliases          |  21
  Sitemaps         |   1
  Cleaned          |   0

Total in 646 ms
```

Once the building process is finished, the website content is ready in `./public`.

***Now you can commit your change to the repo and push it to GitHub!***

You can wait for the website auto update (processed monthly), or you can reach to Ji on Slack to see the changes immediately on the publicly available website https://vision-and-learning-lab-ualberta.github.io/.

## End

If you have any further questions, please reach to Ji on Slack for assistance!