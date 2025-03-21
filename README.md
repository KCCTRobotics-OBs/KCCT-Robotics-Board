# KCCT_Roboticsかんばん方式ボード

進捗報告，タスク管理用のリポジトリ**（必ずプロジェクトも必須）**

## Why use repository and projects

- 全員の研究内容，タスク把握
- ドキュメントに残すべき内容の選定，ドキュメントにしやすくするため
- オーバータスク，事務タスクの管理
- Githubになれる

## 使い方

- タスク管理（To Do リスト）
Githubプロジェクトのテンプレートを利用しています。こちらも日々アップデートがあるので
[かんばん方式](https://lychee-redmine.jp/blogs/project/tips-kanban-methodology/)を採用しています．

また，ガントチャートでタスクのリミットを見やすくしています．
![スクリーンショット 2024-10-04 181149](https://github.com/user-attachments/assets/0f502737-e32d-44bf-bf7d-a87def1b96a5)

- 毎週の進捗報告
  毎週の進捗報告はMarkdownで記入してください．テンプレートは[こちら](https://github.com/KobeKosenRobotics/R6_Shimizulab/blob/main/%E3%83%86%E3%83%B3%E3%83%97%E3%83%AC%E3%83%BC%E3%83%88/templete.md)です．

  MarkDown記法に関しては[こちら](https://qiita.com/Qiita/items/c686397e4a0f4f11683d)を参考にしてください．（特殊文字は[こちら](https://qiita.com/inabe49/items/303afa114b0204da8a24)）

### To Doリストの作成

1. プロジェクトに対応したリポジトリであることを確認
2. Issueボタンを押す
   ![スクリーンショット 2024-10-03 143504](https://github.com/user-attachments/assets/8bb27852-78b7-4ada-9ef3-06587009a80f)
3. New issueを押す．
   ![スクリーンショット 2024-10-03 143523](https://github.com/user-attachments/assets/0e82de8c-58f8-491c-ac58-ba278fb41e57)
4. かんばん作成のテンプレートからGet Startを押す．
   ![スクリーンショット 2024-10-03 143549](https://github.com/user-attachments/assets/7a3a1d07-d6c8-4942-b968-9be22ccb9790)
5. 下のような画面が出るので埋める．（タスクはチェックボックス形式で）
   ![スクリーンショット 2024-10-03 143655](https://github.com/user-attachments/assets/2e2173b9-f29e-4ce8-9cb5-64ff94bba0e0)
6. 送信ボタンを押して，issueができていることを確認しする．以下のようなものができる．必要に応じて，右側の設定を行う．（ラベル，クラスター，ステータス，開始日，期限，マイルストーン）
7. Done

※もし，慣れてきて自分の作業リポジトリができた場合（ロボコンの場合はteamの制御リポジトリとか使う場合）
1. 作業したいリポジトリの上側タブでProjectsを選択
![スクリーンショット 2025-03-21 150830](https://github.com/user-attachments/assets/a7587fdd-60fe-475c-be39-7b4c5aca34d6)

2. link a projectを押し，プロジェクト名を入力し，選択
![スクリーンショット 2025-03-21 150840](https://github.com/user-attachments/assets/3818ff54-66ac-4882-8718-c603fa582e91)
![スクリーンショット 2025-03-21 150854](https://github.com/user-attachments/assets/9db661eb-5713-4d36-a5f5-9b59df126b9a)

3. これでISSUEを作った際にProjectに飛ぶようになる（またプロジェクトのカードからも変更できる）

### To Doリストの確認，タスクの進捗入力

1. リポジトリの上のタブからprojectsタブを押すと以下の画面になるので，見たいプロジェクトを押す．
   ![スクリーンショット 2024-10-03 144130](https://github.com/user-attachments/assets/7936e9c6-cb43-42d8-8b0f-5413c6b9cb4f)
2. Kanbanが出てくるので，ToDoのカラムの中から自分の現在行っているタスクを探して，選択する．
   ![スクリーンショット 2024-10-03 144142](https://github.com/user-attachments/assets/316daf5d-6307-4e49-9f45-841672187069)
3. 必要に応じて右側の項目を変更したり，チェックボックスにマークを付けていく．
   ![スクリーンショット 2024-10-04 180209](https://github.com/user-attachments/assets/34db6ae7-3321-4298-86fa-316daec97a8c)
4. 進捗が出次第，コメントに手入力していく．（ベストプラティクス：チェックボックスを記入したタスクに関してコメントをつけていく，画像とかデータがあるとGood!）
   ![スクリーンショット 2024-10-04 175951](https://github.com/user-attachments/assets/ddb85327-5f04-45fc-ae54-516fc87a4d90)
5. そのタスクのカードが終了次第，issueをクローズにする．（そうするとカードがDoneに移動します．）
   ![スクリーンショット 2024-10-04 175951-copy](https://github.com/user-attachments/assets/614253f8-8846-487c-af18-fa0705f268ea)

## 注意

- 毎週の進捗報告のために，作業したらgithubのissueを更新するように！！（ToDoカードやissueのコメント，ラベル等）
- できるだけ，ほかの人のタスクの確認もするように

# みなさんでクリーンなを送れるように頑張っていきましょう！！
