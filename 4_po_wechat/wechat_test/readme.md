

【简答题】使用PO设计模式实现企业微信 web版  添加成员，根据题干要求，在【拉勾系统】的答题框提交gitee或者github代码链接。



├── __init__.py      
├── pages    
│   ├── __init__.py    
│   ├── add_members_page.py（添加成员界面，继承base_page下SeleniumDriver）     
│   ├── base_page.py (基类，使用cookie自动登录企业微信，实现构造webdriver)    
│   ├── contact_page.py（通讯录界面，继承base_page下SeleniumDriver）    
│   ├── data.yaml （登录cookies信息存储）    
│   └── main_page.py（主页，继承base_page下SeleniumDriver）    
├── run.py（执行调用文件，执行方法：python run.py）    
├── testcases    
│   ├── __init__.py    
│   └── test_wechat.py    

