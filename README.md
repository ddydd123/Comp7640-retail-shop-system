# COMP7640 Database Systems & Administration
*Group 34*


*This is a README file providing instructions for running the code developed by Group 34.*


# Online Retail Database Application
*The application offers several features, including management of shops and items, the ability to search for items by keywords, purchase items, and cancel orders.*


## Table of Contents
* 1 Installation
* 2 Usage

### 1 Installation
* [Python 3.11.3](https://www.python.org/ftp/python/3.11.3/python-3.11.3-amd64.exe)
* [Python Installation guide](https://hownav.com/1225.html)
* [MySQL Community Server](https://dev.mysql.com/downloads/mysql/)
* [MySQL Community Server Installation guide](https://blog.csdn.net/zxs9999/article/details/68942233) 
* [MySQL Installation Troubleshoot](https://blog.csdn.net/shaoyongzhuo/article/details/120023433)


### 2 Usage
**2.1** To access the directory `F:\pythonProject_retail`, open Command Prompt and enter `py controller.py`. When prompted to log in, use a phone number. The default administrator phone number is `1`.

![1.png](https://s2.loli.net/2023/04/10/PxDV1ByaERzY4sr.png
 "after log in")
 
 
**2.2** Enter `a` to show all shops, each shop has 4 attributes: id, name, rating, location.

![2.png](https://s2.loli.net/2023/04/10/iGp2KN8Q6gLev5f.png)


**2.3** Enter `b` to add a new shop, assuming we input `a 3 Shanghai`. After press Enter, it prompts 'success!'.

![3.png](https://s2.loli.net/2023/04/10/HEuYj7t4JliRoaN.png)


**2.4** To view all items of a shop, enter `c` and input the shop name `apple`. Once the items of the shop are listed, enter `y` to purchase an item. To purchase a specific item, enter the order ID as `1` and the item ID as `3`.

![4.png](https://s2.loli.net/2023/04/10/AkTtufvLF1mPUo7.png)


**2.5** Enter `d` to add a new item to the shop, first we have all information of shops:

![5.png](https://s2.loli.net/2023/04/10/aE9wZbslUTyM3LD.png)

To add a new item, enter `d`, and input the shop ID as `11`, the item name as `11`, and the item price as `13`. Then, input three keywords: `af sg dh`. Press enter to submit the input, and you should see a 'success' message.

![6.png](https://s2.loli.net/2023/04/10/aBQDpfOwL9M7Zqe.png)


**2.6** To search for an item, enter `e` and input the keyword `apple`. Relevant records will be displayed, and you can choose to purchase an item or not. To not purchase an item, simply enter `n`.

![8.png](https://s2.loli.net/2023/04/10/h6YPU8jaRcvLVi2.png)


**2.7** To cancel an order, enter `f`, and input the order ID as `1`. Once the cancellation is successful, you should see a 'success' message.


![9.png](https://s2.loli.net/2023/04/11/wGWTBqtbSNvuLl4.png)


**2.8** Lastly, enter `g` to log out.


![10.png](https://s2.loli.net/2023/04/11/fTYmlxJe8djcB5I.png)

















