1. How to upload photos?

Pictures are stored in /content/images/gallery. So, just follow github instruction to upload pictures there.

2. How to display pictures on the home page?

edit /content/home/homepage.json.

For example, I uploaded a picture named firstphoto.jpg, and I added something like this to the file.
{
    "title": "First Photo",
    "copy": "This is the first photo that I uploaded.",
    "image": "../images/gallery/firstphoto.jpg"
  },
  
Have a look at /content/home/homepage.json, it is easy to understand.

Next, we are going to change introduction part on home page and other descriptions of the website. 

Once it is done, you will have a starter place you can build your own website.

Please let me know if you have any questions.
