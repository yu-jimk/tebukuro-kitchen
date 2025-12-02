# てぶくろキッチン

<img width="1200" height="630" alt="thumbnail" src="https://github.com/user-attachments/assets/3869b81a-84f4-4b26-9651-d780a3f9caf3" />

## ■ アプリ概要
てぶくろキッチンは、音声認識を利用して操作できるハンズフリー型レシピアプリです。

料理中に手が汚れていたり、画面に触れない状況でも、「次へ」「戻って」「材料を教えて」と話しかけるだけで、レシピの閲覧や調理手順の確認ができます。

従来のレシピアプリでは、調理のたびにスマートフォンを操作する必要がありましたが、本アプリでは音声だけで操作が完結するため、よりスムーズで安全な調理体験が可能になります。
料理初心者から日常的に料理をする人まで、幅広いユーザーに向けたアプリです。

## ■ アプリへの想い
このアプリは、「料理中の“ちょっとした不便”をなくしたい」という思いから開発しました。
実際に料理をしていると、手が汚れてスマホを触りにくかったり、画面を見るために動作を止めてしまったりする場面が多くあります。

そこで、「話しかけるだけでレシピを操作できたら、もっと快適に料理ができるのではないか」と考え、音声認識による操作機能を取り入れました。
誰でも直感的に使えて、料理に集中できるアプリを目指して、使いやすさを重視して開発しています。

## ■ アプリのURL

<img width="315" height="315" alt="QR_158903" src="https://github.com/user-attachments/assets/11de5c74-78c9-4526-8067-e180747dfb00" />

https://tebukuro-kitchen.vercel.app/

※スマートフォンからの利用をおすすめします

## ■ 主な画面

<table>
  <tr>
    <td align="center">ホーム画面</td>
    <td align="center">レシピ一覧画面</td>
    <td align="center">調理画面</td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c24175e3-867b-44c5-bf77-d06bf293c23f" width="250">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/d39213b6-7d95-436e-aa1e-4db3a047f7b6" width="250">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/98e47826-791d-442c-8859-e7d850fd1b1a" width="250">
    </td>
  </tr>
</table>

## ■ 使用技術

| 項目             | 内容 |
|----------------------|------|
| フロントエンド       | Next.js / TypeScript / TailwindCSS |
| バックエンド         | Supabase |
| データベース         | Supabase (PostgreSQL) |
| 認証                 | Supabase Auth |
| 音声認識             | react-speech-recognition |
| バリデーション       | zod |
| データフェッチ       | SWR |
| 外部API / サービス   | Youtube API / Google Cloud Text-to-Speech API |
| UI / アイコン        | MUI / react-icons |
| デザイン             | Figma |
| デプロイ             | Vercel |
| 開発環境 / ツール    | ESLint / Prettier / Husky |

## ■ ER図
<img width="2270" height="1410" alt="Image" src="https://github.com/user-attachments/assets/062b7526-834c-42be-8c0a-398755d3129c" />

## ■ 今後の展望
- 複数レシピの同時進行機能  
  主菜と副菜など、複数のレシピを同時に表示・管理し、タイミングを見ながら並行して調理できる機能を追加。
  
- 外部レシピサービスとの連携  
  既存レシピサービスと連携し、より多くのレシピを扱えるようにする。

- AIによる料理相談機能  
  火加減や電子レンジのワット数換算など、初心者が迷いやすいポイントをAIに相談できる機能を追加。

- 画面の自動スリープ対策  
  調理中に画面が暗くならないようにする機能を実装。

- 開発環境の整備・テスト・CI/CDの導入  
  開発環境を整理し、テストの自動化やCI/CDを導入することで、品質と開発効率の向上を目指す。

- 本格リリースに向けたレシピデータ整備  
  公開用のレシピを事前に十分な数用意し、安定した運用を目指す。
