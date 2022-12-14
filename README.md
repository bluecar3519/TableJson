# TableJson


# Introduction     

This project is about taking a JavaScript Object Notation (JSON) object Array to build a webpage's Hypertext Markup Language (HTML) table. In JSON object Array, the key fields make up the header in the table. The keys do not have to be identical in each JSON object in the Array. This program will Iterate through the Array of each object key and put it into a set. Set Data Structure will only let you add elements if not contained in the Set when the program iterates through array objects again to add data to the table. After the program gathers the necessary information to build the table, it will insert the webpage. I have a  separate JavaScrip file called database.js, which stores the JSON information. This program is just a prototype, but in the future, the data can put in a database. I  recommend using a  MySQL database. See below insert table.

## JSON Database

## Table HTML     
```HTML

            <table id="table_student" class="display">
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Age</th>
                        <th>Dept</th>
                        <th>Score</th>
                        <th>Grade</th>
                      </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Pete Johnson</td>
                        <td>18</td>
                        <td>CSE</td>
                        <td>90</td>
                        <td></td>
                      </tr>
                      <tr>
                        <td>Tom Smith</td>
                        <td>23</td>
                        <td>HIS</td>
                        <td>87</td>
                        <td></td>
                      </tr>
                        <tr>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td>10</td>
                      </tr>
                </tbody>
            </table>

```
# Run the Application

## Download Packages

```
$ npm install
```

## Start the web server

```
$ npm run devStart
```
## API's   

<img src="https://github.com/bluecar3519/GettingStarted/blob/main/RepositoriesImages/TableJson/raw_api.png" alt="Raw API" height="500" width="600">

```
http://localhost:3000/raw
```

<img src="https://github.com/bluecar3519/GettingStarted/blob/main/RepositoriesImages/TableJson/home_api.png" alt="Home API" height="400" width="650">

```
http://localhost:3000/home
```

<img src="https://github.com/bluecar3519/GettingStarted/blob/main/RepositoriesImages/TableJson/save_api.png" alt="Save API" height="200" width="500">

```
http://localhost:3000/save
```

## Local File   

When you click on the Html file in your local directory the browser will open.         

<img src="https://github.com/bluecar3519/GettingStarted/blob/main/RepositoriesImages/TableJson/local_file.png" alt="Local File" height="400" width="650">



# JavaScrip Libraries      
* [JQuery](https://jquery.com/)   
* [DataTable](https://datatables.net/)   
* [JQuery UI](https://jqueryui.com/)   
* [Bootstrap](https://getbootstrap.com/)   

# Tutorials    

## Set    
[Object.keys()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)

## Class
* [Class basic syntax](https://javascript.info/class)
* [JavaScript Getters and Setters](https://www.javascripttutorial.net/es6/javascript-getters-and-setters/)

# Problems   
* [How to access variables from another file using JavaScript](https://www.geeksforgeeks.org/how-to-access-variables-from-another-file-using-javascript/)   
* [How to fix "cannot use import statement outside a module](https://flaviocopes.com/fix-cannot-use-import-outside-module/)
* [JavaScript Modules with Import/Export Syntax (ES6) - JavaScript Tutorial](https://www.youtube.com/watch?v=s9kNndJLOjg)
* [Debug node js vscode using inspect! Learn to use a debugger with node. Tutorial in javascript](https://www.youtube.com/watch?v=FMsNsSHhRC8)
* [Write a line into a .txt file with Node.js](https://stackoverflow.com/questions/33418777/write-a-line-into-a-txt-file-with-node-js)       
