```mermaid
graph LR
    actor User
    actor Librarian

    subgraph 图书管理系统
        UC1[(借阅图书)]
        UC2[(归还图书)]
        UC3[(查询图书信息)]
        UC4[(添加图书)]
        UC5[(删除图书)]
        UC6[(修改图书信息)]
        UC7[(注册用户)]
        UC8[(注销用户)]
    end

    User -->> UC1
    User -->> UC2
    User -->> UC3
    User -->> UC7
    User -->> UC8

    Librarian -->> UC1
    Librarian -->> UC2
    Librarian -->> UC3
    Librarian -->> UC4
    Librarian -->> UC5
    Librarian -->> UC6
```
