## Instagram Bot
The aim is to list all the instagram handles that you follow, that don't follow you back. The implementation is purely done using selenium automation strategy. 

### Libraries used:
* [Selenium](https://selenium-python.readthedocs.io/index.html) : A popular automation tool.
* [webdriver-manager](https://pypi.org/project/webdriver-manager/) : Supporting package.

### Pre-requisites:
### **Chromedriver has to be installed before executing the program**

`>> pip3 install selenium`

`>> pip3 install webdriver-manager`

### Usage:
`>> python instagram_bot.py`

### I/O:

```
Enter Username:$(username)

Enter Password:$(password)


output:
Total unFollowers : $(unfollowers)
<List of unfollowers account ids comes below>
```
