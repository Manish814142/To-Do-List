# To-Do-List
TodoList-EJS-MONGO-NODE.JS

To-Do List project is an application specially built to keep track of errands or tasks that need to be done. This application will be like a task keeper where the user would be able to enter the tasks that they need to do. Once they are done with their tasks they can also remove them from the list.


## installation & use
npm install after downloading files.

If you would like to download the repo and run the app locally on localhost 3000 (or any port you specify).

## tools, libraries used & why I chose to use it
The following table shows my rationale behind building this app, and why I chose to use the frameworks and tools that I did.

<table>
  <tbody>
    <tr>
        <th>Tool</th>
        <th>Why I chose it</th>
    </tr>
    <tr>
        <td>Node.js</td>
        <td>
            <ul>
                <li>popular and well-documented</li>
                <li>uses JS as main application</li>
                <li>robust framework</li>
            </ul>
        </td>
    </tr>
    <tr>
      <td>Express.js</td>
      <td>makes it easier to handle http requests</td>
    </tr>
    <tr>
      <td>MongoDB cloud</td>
      <td>
        <ul>
          <li>noSQL DBs like MongoDB are easier to scale</li>
          <li>not much inter-document relationships need to be made for the purposes of this app</li>
          <li>well-documented</li>
          <li>free cloud database</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>body-parser</td>
      <td>helps with requests from client-side e.g. add item, delete item</td>
      </tr>
    <tr>
      <td>ejs</td>
      <td>saves a lot of lines of code, especially given that I need to rewrite the same code so many times when creating new to-do lists</td>
    </tr>
    <tr>
      <td>lodash</td>
      <td>makes string formatting a lot easier</td>
    </tr>
  </tbody>
</table>

## functionality
By default, when you come to the page, you are welcomed to the home page, or default to-do list. Its title is the date of the day you access the page. It is prepopulated with 3 to-do items, as you can see below:



### adding items to a list
You can add items to a to-do list by simply inputing the new item name into the last box, and then pressing the "+" or the enter key, like so:


### deleting items from a list
You can delete items to a to-do list by simply clicking the box next to the item name, like so:


### creating new lists
New to-do lists are created when a new parameter name for a list is inputed into the URL. For example, I created a new list called "new-list".

On the backend, a new to-do list collection is created in the database.


As such, you can navigate back to the page later and find the items still there. Any changes you make will be made forever.

Note also that the same adding and deleting items functionality works for these new lists as well.

## reference
Special thanks- The Complete 2023 Web Development Bootcamp by Angela Yu
