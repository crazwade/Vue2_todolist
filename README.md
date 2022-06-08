# Todolist 規格書

# 1. 系統功能架構
使用Vue2架構的「待辦清單」

## 1.1 作業流程說明

待辦清單

    * (操作) 新增 / 刪除 / 修改 / 更改狀態)
    
![image](https://user-images.githubusercontent.com/31063679/172515230-e645da5c-8e25-4882-a203-bd6f758e3c7c.png)


    
# 2. 功能規格說明

## 2.1 資料格式 Object

### Todolist
```json
todolist: [
      {
        id: 0,
        content: '吃晚餐 王品',
        status: 'undone',
      },
      {
        id: 1,
        content: '吃早餐 買7-11',
        status: 'done',
      },
      {
        id: 2,
        content: '吃早餐 買全家',
        status: 'done',
      },
      {
        id: 3,
        content: '吃五餐 買麥當勞',
        status: 'done',
      },
],
```
