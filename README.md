# What Can I Do For Wikimedia

##Adding Suggestions
1. Navigate to the file you wish you change - for example, to add 'tech' suggestions, click 'tech.txt'
2. Click the edit (pen) icon in the top right
3. Make your changes. Please be sure to follow the file's standard structure.
4. Submit a pull request

##Server File Structure
The file structure on the server is as follows:
* **assets**
  * style.css <br/>
  * Wikimedia_Community_Logo.png
  * Wikimedia_Community_Logo-140px.png
* **explore** <br/>
  * advocate.php <br/>
  * create.php <br/>
  * index.php <br/>
  * tech.php <br/>
* **schools** <br/>
  * [marked for later use]
* .htaccess <br/>
* index.php (nb. uses file_get_contents on index.html)<br/>

##Suggestion format
```<a href='url here'>Text to be shown</a>?```

##To Do
* Make the suggestion submission process easier

##Notes
* index.html is **THE MOST** hacky way of including something in a webpage and also allowing community input. It uses a PHP 'file_get_contents'. Editing this changes the index of http://www.whatcanidoforwikimedia.org - so only pull request sensible things yeah? :3
