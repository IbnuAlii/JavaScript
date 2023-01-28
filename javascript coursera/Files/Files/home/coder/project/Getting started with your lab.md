# Getting Started with your Lab Sandbox

## How can I view my HTML files?
If you choose to use a Lab Sandbox to complete your work, you have a few options to enable 
your HTML pages to preview within a lab. Please choose one of the options below.

###Viewing your lab files with the live server

1)Click on Go Live icon at the bottom-right of your lab environment alongside the notification (bell) icon. 
2)You should see the server starting message -"Server is Started at port : 5500"
3)Click on the Browser Preview Icon from the left menu of the lab environment.
4)A browser preview window should open for you and on the address bar type the URL - localhost:5500/
5)You should see all your lab files in the browser preview window. 

###Viewing your lab files with the browser preview

1)Right-click on the HTML file you want to preview and copy the RELATIVE PATH.
2)Click on the Browser Preview Icon from the left menu of the lab environment.
3)A browser preview window should open for you and in the address bar type the URL - localhost:8000/lab/<YOUR_RELATIVE_PATH>
4)Your file content will display.

###Viewing your files in the browser tab for full browser dev tools access: 

 You'll be able to preview your web content using the following path- https://<your lab id>.labs.coursera.org/lab/<YOUR_RELATIVE_FILE_PATH (in a new browser tab for full browser dev tools access).
 
 Input the following "https://<your lab id>.labs.coursera.org/lab/<YOUR_RELATIVE_FILE_PATH" in your URL browser toolbar, replacing <your lab id> with the value you see from the top Lab iframe "Help" icon.

###Bootstrap and JQuery files

Code can also be placed in an external JavaScript and CSS file. If you take this approach, please make sure that you've linked the files correctly together, otherwise you might have some issues trying to figure out why your code isn't working.

- JavaScript code can appear in the head, or the body of your code, or very often in both.
 
- If you get stuck, the console can tell you if it can't find that file, and can lead you down the right path to fixing your code.

To link your JavaScript and CSS file to your HTML file, you can pass the JavaScript filename within the ```<script> </script>``` tag, as shown below:
```
<script src="./FILENAME.js"></script>
```
{:codeblock}

Similarly, to link your CSS file:
```
<link rel="stylesheet" href="./FILENAME.css">
```
{:codeblock}

### For viewing the images in lab files

- For the practice labs where image viewing uses an external image link (URL) in the HTML file: Please view those labs in a browser tab. 
- If you want to view images in live server or with browser preview, please upload your image files directly to your lab sandbox instead, and be sure to change the link of the image to the path where this image is stored within your Sandbox. 
