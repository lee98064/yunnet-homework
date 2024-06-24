## YunNET Practice homework

## Frontend

1. Install dependencies

```bash
yarn install
```

2. Run the project

```bash
yarn dev
```

## Backend

1. Install dependencies

```bash
yarn install
```

2. Configure the env file

```bash
cp .env.example .env
```

3. Run the project

```bash
yarn dev
```

## Specification

#### A. 前端部分

- 使用 Nuxt.js
- 提供使用者註冊與登入
- 登入後可以顯示該使用者的 profile
- UI 框架不限，需要有基礎的介面

#### B. 後端部分

- 使用 python 或 node js express
- 建立使用者登入 登出 註冊 API
- 建立使用者 profile 回傳 API，需要登入後才能回傳
- 資料庫使用 mysql，並搭配 ORM 操作資料庫
- 登入部分前端後端可以使用 token 或 session，只要可以記錄登入狀態的方式皆可。

#### C. 部屬部分

- 全部專案使用 docker 打包
- 安裝在虛擬機內並可以正常 host
- 作業系統選用 Linux, 不限發行版本
- 可搭配 reverse proxy
- 也可以架設在其他空間

#### D. 專案管理部分

- 將專案上傳至 github，並要做好 commit ，不可全部塞在一個 commit 內
- 可以放在同一個 repo 內用 folder 分開，也可以分成兩個 repo 存放
- 依照當下要做的功能開設 PR，而不是在 master 分支上開發
