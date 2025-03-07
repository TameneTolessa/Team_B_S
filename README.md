# Team Schwessinger (Plant, Fungi, Evolution Lab) page


This is a repository for the [Team Schwessinger lab page](http://https://team-schwessinger.github.io/Team_B_S/). We use Jekyll to run our Github page. We are welcome for other people to contribute to our site not just lab members. Feel free to fork and pull-request!


## Run the page locally

To run locally, follow instruction [here](https://jekyllrb.com/) to install Jekyll then run `jekyll serve` to see in `localhost:4000`. Here is a brief install guidelines.

```bash
sudo gem install jekyll
sudo gem install rouge
jekyll serve
```


## Add posts

It's very easy to add post. All the posts are located in `_posts` folder. It arrangement is based on
date. Each post can be written in markdown format. You just have to state headers before writing: `title`, `description` and `categories`. `description` will be shown when you share on social media like Facebook or twitter. See the following headers:

```
---
title: How to add a post to the website
description: Instructions for adding a post to the Team Schwessinger lab page
categories: everyone
---
```

We have 4 categories: `everyone`, `researchers`, `discussion`, `blog` you can choose and this will be rendered to different location.


## How to add posts


- **Directly edit on Github**, you can simply go to `_posts` and click `New file` then put some markdown file in the format `Year-Month-Day-Post-Name.md` and start writing blog post. Github also allows you to preview it so it's nice for people who don't want to clone the repo. 

- **Clone the repository**, kind of the same as directly add post on Github. You just have to clone the repository. Then add new post file, commit and push to the repo.

The changes will take approximately half a minute to render. You can see the new posts or changes on the [Team Schwessinger](https://team-schwessinger.github.io/Team_B_S/) lab page!


## Add yourself

You can add yourself to the page in `_people` folder just create file name `<firstname>_<lastname>.md` in the folder. We require few line of header before you start writing your own page. See the following for the header

```
---
name: Benjamin Schwessinger
position: pi
avatar: Benjamin-Schwessinger.jpg
twitter: @Schwessinger
joined: 2008
---
```

If you don't have information, just leave it blank. The avatar will bring photo from `images/people` folder and display it on people page. 
For lab position, you can choose position from 4 classes including `postdoc`, `gradstudent` (for Honours and Masters students), `projectstudent` (for undergraduate students), and `staff`. Position will put you into section that you choose.

## Add new publications

All publications from the lab are located in `publications.md`. Please upload new publication on your own!
