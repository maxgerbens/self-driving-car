CONTENTS OF THIS README
---------------------

 * Description
 * How to use
 * Credits


INTRODUCTION
------------

This project has been made without any libraries, only vanilla JavaScript, HTML and CSS. There is a visualisation of the neurological network used to make the decisions for the AI. The car uses machine learning throught trial-and-error to find the best way to complete the trial.

HOW TO USE
---------------------

Clone or download the repository and open it in [Visual Studio Code](https://code.visualstudio.com/) then open the index.html file using the [Live Server]( https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) plugin.

After that you can experiment using different number of cars used for the machine learning (default is 1000 cars, but most computers can't handle that and therefore optimal to use +- 100 cars.) You probably won't get the optimal route of the care the first try, keep refreshing untill a car reaches the end of the course, then click the save button, and change the amount of cars to 1. This car will take the optimal route and will finish the course always. If you want to retry, click the delete button and try again.

You can change the number of cars in main.js on line 12

Credits
-----------

Credits to:
 * Radu Mariescu-Istodor - https://github.com/gniziemazity
 


