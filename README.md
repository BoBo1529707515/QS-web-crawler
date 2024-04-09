# QS-web-crawler
本项目用于爬取QS排名中的详细信息，你可以使用这个代码获得由附属excel文件中配套的链接到的相关信息  
提交的附属文件中有2024年QS排名前1000左右的高校相关信息  
**你需要做的更改:**  
1.将excel文件下载到你的本地，并将代码中导入的部分更改为你的路径  
2. 根据自身浏览器版本下载对应的驱动器[edge drive](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/ )  
3.将下载好的驱动器地址复制到代码中对应的位置去  
4.修改最后的保存数据段为你希望的保存地址  
5.在@override for row in range(2, 100):后面的数字你可以根据希望爬取的数量进行调整  
**   **。注意**   **。  
1.代码运行开始，会有cookie部分，请点击  
2.最后的数据文件中，最后一个学校的数据会读两遍，在后面的版本中将修改。  
# QS-web-crawler

This project is used to crawl detailed information from QS rankings. You can use this code to obtain relevant information linked from the accompanying Excel file.

**Changes Needed:**
1. Download the Excel file to your local machine and change the import path in the code to your path.
2. Download the corresponding driver for your browser version from [Edge Driver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/).
3. Copy the downloaded driver's address to the corresponding location in the code.
4. Modify the segment for saving data to your desired saving address.
5. Adjust the number after `@override for row in range(2, 100):` according to the quantity of data you wish to crawl.

**Attention:**
1. At the beginning of code execution, there will be a cookie section. Please click on it.
2. In the final data file, the data for the last school will be read twice. This will be modified in later versions.
