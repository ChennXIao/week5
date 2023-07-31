# week5

### SQL CRUD
- 使⽤ INSERT 指令新增⼀筆資料到 member 資料表中，這筆資料的 username 和
password 欄位必須是 test。接著繼續新增⾄少 4 筆隨意的資料。
<img width="733" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/1df5d22d-803f-4d61-ae09-7ee8ddf3ae63">

- 使⽤ SELECT 指令取得所有在 member 資料表中的會員資料。
<img width="542" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/1a9f6b55-114e-459c-aaf2-0ddde472acc1">

- 使⽤ SELECT 指令取得所有在 member 資料表中的會員資料，並按照 time 欄位，由
近到遠排序。
<img width="546" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/0f65939c-2ef1-4a53-a88c-4ed98a1fba62">

- 使⽤ SELECT 指令取得 member 資料表中第 2 到第 4 筆共三筆資料，並按照 time 欄
位，由近到遠排序。
<img width="526" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/c18ffbc5-c931-4a6c-bbdc-47e5ae1e5e7e">

- 使⽤ SELECT 指令取得欄位 username 是 test 的會員資料。
<img width="522" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/41428115-6fa6-47d9-89da-738e9a28a0fd">

- 使⽤ SELECT 指令取得欄位 username 是 test、且欄位 password 也是 test 的資料。
<img width="527" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/bd6b0830-2735-466c-b298-43981f1d9403">

- 使⽤ UPDATE 指令更新欄位 username 是 test 的會員資料，將資料中的 name 欄位改
成 test2。
<img width="537" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/aee30ed1-514e-43fc-a8f0-78d95581a2dc">

---
### SQL Aggregate Functions
- 取得 member 資料表中，總共有幾筆資料 ( 幾位會員 )。
<img width="272" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/437b9ae1-29ce-4efa-a0ab-739437ac8377">

- 取得 member 資料表中，所有會員 follower_count 欄位的總和。

<img width="330" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/e4f77463-2100-483d-9b7f-a1cfe9729871">

- 取得 member 資料表中，所有會員 follower_count 欄位的平均數。
<img width="327" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/7b56f69c-fdfc-45f1-8fd2-17a3f535261b">

---
### SQL JOIN

- 使⽤ SELECT 搭配 JOIN 語法，取得所有留⾔，結果須包含留⾔者的姓名。
<img width="942" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/2673e74e-6b71-48e4-9599-0ebfc9744e02">

- 使⽤ SELECT 搭配 JOIN 語法，取得 member 資料表中欄位 username 是 test 的所有
留⾔，資料中須包含留⾔者的姓名。
<img width="943" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/99b516e0-dd07-49e6-a13b-eda59a7fd237">

- 使⽤ SELECT、SQL Aggregate Functions 搭配 JOIN 語法，取得 member 資料表中
欄位 username 是 test 的所有留⾔平均按讚數。
<img width="820" alt="image" src="https://github.com/ChennXIao/week5/assets/61040179/712909a6-ec95-467e-b407-f75f8465d2b7">

---




