<img src="./images/triplango_cover.png" />

<div align="center">
  <div>
    <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logoColor=000&logo=react" alt="React" />
    <img src="https://img.shields.io/badge/Vercel-000.svg?style=for-the-badge&logo=vercel&logoColor=fff" alt="Vercel" />
    <img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=fff" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=fff" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/shadcn%2Fui-000?style=for-the-badge&logo=shadcnui&logoColor=fff" alt="shadcn/ui" />
    <img src="https://img.shields.io/badge/ESLint-4b32c3?style=for-the-badge&logo=eslint&logoColor=fff" alt="ESLint" />
    <img src="https://img.shields.io/badge/Prettier-f7b93e?style=for-the-badge&logo=prettier&logoColor=fff" alt="Prettier" />
    <img src="https://img.shields.io/badge/Firestore-FF9A00?style=for-the-badge&logo=firebase&logoColor=fff" alt="Firestore" />
    <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=fff" alt="Axios" />
    <img src="https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=fff" alt="React Router" />
    <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=fff" alt="Gemini" />
    <img src="https://img.shields.io/badge/Place%20API-4285F4?style=for-the-badge&logo=googlecloud&logoColor=fff" alt="Place API" />
    <img src="https://img.shields.io/badge/Place%20Photo%20API-4285F4?style=for-the-badge&logo=googlecloud&logoColor=fff" alt="Place Photo API" />
  </div>

  <h3 align="center">AI Travel Planner App</h3>

  <div align="center">
    AI が提案する旅行計画を自動生成するアプリ
  </div>
</div>

## 📋 <a name="table">もくじ</a>

1. 🤖 [はじめに](#intro)
2. 🔗 [URL](#url)
3. 💻 [画面一覧](#screen_list)
4. 🚀 [アプリの利用サンプル](#example)
5. 🤸 [終わりに](#outro)

## <a name="intro">🤖 はじめに</a>

あなたの旅行計画作成をサポートするアプリ、triplanGo を紹介します。

triplanGo は、目的地、日数、人数、予算という要望を選択するだけで、すばやく旅行プランを自動生成することができるアプリです。

## <a name="url">🔗 URL</a>

triplanGo | AI Travel Planner    
https://triplango.vercel.app

## <a name="screen_list">💻 画面一覧</a>

```
triplango  
  │     
  ├─　ランディングページ  
  │  
  ├─　ログイン関連  
  │      ログインモーダル  
  │  
  ├─　旅行計画作成ページ  
  │  
  └─　保存済みの旅行計画ページ  
        │
        └─　旅行計画詳細ページ  
```

### ログイン不要画面

#### ランディングページ 

|未ログインの場合|ログイン済みの場合 |
|---|---|
|<img src="./images/landing_page_before_login.png" width="360px" />|<img src="./images/landing_page_after_login.png" width="360px" />|

### ログイン関連

```
ログイン関連  
　　ログインモーダル  
```

|ログインモーダル |
|---|
|<img src="./images/login_modal.png" width="360px" /> |

#### ログアウト

##### ヘッダのユーザアバターをクリックしてメニューからログアウト

<img src="./images/logout.png" width="360px" />

### 各ページ

```
旅行計画作成ページ  

保存済みの旅行計画ページ  
  │
  └─　旅行計画詳細ページ  
```

#### 旅行計画作成ページ 

|未入力 |入力済み |
|---|---|
|<img src="./images/create_trip_page.png" width="360px" /> |<img src="./images/entered_forms_of_create_trip_page.png" width="360px" /> |

#### 保存済みの旅行計画ページ    

<img src="./images/my_trips_page.png" width="360px" />

##### 旅行計画詳細ページ  

<img src="./images/view_trip_details_page.png" width="360px" />

|ホテル詳細 |スポット詳細 |
|---|---|
|<img src="./images/hotel_details_page.png" width="360px" />|<img src="./images/spot_details_page.png" width="360px" />|

## <a name="example">アプリの利用サンプル</a>

### triplanGo 操作デモ

#### 旅行計画を生成する

<!-- ./movies/triplango_create_trip.mp4 -->
<video src="https://github.com/user-attachments/assets/22356df3-e7ff-4667-af96-0820cd24190f" controls="true"></video>

#### 保存済みの旅行計画を見る

<!-- ./movies/triplango_my_trips.mp4 -->
<video src="https://github.com/user-attachments/assets/7be9ded2-7946-47e7-94aa-07f3b9d5118c" controls="true"></video>

## <a name="outro">🤸 おわりに</a>

すばやく旅行プランを自動生成するアプリ triplanGo を紹介しました。

現状の形としては、旅行計画の生成、結果の閲覧のみの機能ですが、内容を編集したり他の人と共有したりする機能を拡充させていけば、より旅行計画を緻密に立てられるアプリになります。
