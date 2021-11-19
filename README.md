# 383Project - Frontend React Technical Test

## Background
Bullring Birmingham will be hosting their annual Autumn Fashion Fix event in the coming weeks. In a bid to drum up some excitement around the event, they want to create a “social wall” where they can post examples of latest trends as well as collate relevant pieces of social media from Twitter and Instagram. This wall will be viewable on mobile, tablet, as well as being pulled through to their main website via an iframe.

Our custom built analytics and content aggregation tool called Juicer has been configured to collect social posts tagged with the hashtag “#aff” and make it available via an API. 

An admin area has already been created by the Back End Developer to consume this stream, provide moderation tools, as well as adding a function for Bullring to add their own custom messages (either with or without an image). It then provides a normalised data structure via the basic endpoint below.

http://private-cc77e-aff.apiary-mock.com/posts

## Technical
We primarily use React here at 383. We are also looking out for libraries such as Redux. 
But feel free to use which ever tools you feel fit the needs of the task.

## The Task

Using the data source, your task is to create a static page which calls for the data, formats it as necessary and display posts in a grid like structure (think Pinterest) as per the rough wireframe provided on the last page. 

## Requirements

Page should be fully responsive to accommodate any screen width, from mobile up to desktop.
Updating/refreshing doesn’t need to be live or automated, but there should be a “load more”  button to load older posts.

Links within post text should all go somewhere in another window.
There should be a filter to narrow down the type of posts displayed if the user is only interested in “Instagram” for example. (HINT: types of posts are defined in the “service_name” key for an item in the API response)

The design of the elements is not too important at this stage, as long as they show all the requisite details. Our designer has quickly mocked up the following individual posts to 
give you a visualisation of how the blocks could appear.


## Submission

The resulting repository can either be submitted via GitHub, bitbucket. We also recommend adding run and build instruction to a Readme document.
