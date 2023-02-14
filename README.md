# Image in Notebook Example
## To get the correct image link
Usually, GitHub is able to handle relative links within repositories. For example, I can link the image in this file:

![local path test](image.png)

However in some cases this doesn't work, so you need to link to the image from GitHub's CDN, rather than a local file.

Given that, this is what you need to do:

 - Upload image to repository

![image](https://user-images.githubusercontent.com/123095472/218782377-b6c72164-6072-47a4-a53f-8f2aa85c7c88.png)

 - Open image in GitHub and copy the link to the image

![image](https://user-images.githubusercontent.com/123095472/218782754-99e50795-92c8-42ba-be00-4032fc429391.png)

 - Enter the copied link as the path to the image

Since the image is on GitHub's CDN, it will load like any other Web Image, hopefulyl without a hitch.
