# Company Profile (Japanese)

![slide01](https://cloud.githubusercontent.com/assets/4939774/20208734/7f2d6b74-a833-11e6-9181-fa88747e01e0.png)

- Quipper は教育サービスとプラットフォームを提供している会社です
- 2010 年に、元 DeNA 共同創業者の渡辺雅之がロンドンで創業しました

![slide02](https://cloud.githubusercontent.com/assets/4939774/20208738/8173d800-a833-11e6-8e9d-3ec4a2af006e.png)

- Quipper は "Distributors of Wisdom" というビジョンを掲げています
- 日本語だと「世界の果てまで最高の学びを届けよう」
- CEO 渡辺が学生時代に発展途上国でボランティア活動をしていたときの体験がもとになっています
- 生まれ育った環境で満足な教育を受けられず、貧困から抜け出せない人たちがいる現実を知り、問題を解決したいと考えました
- インターネットとモバイルデバイスを通じて、誰でも、世界のどこにいても良質な教育を受けられるようにする

![slide03](https://cloud.githubusercontent.com/assets/14937062/20047069/e77fb7a6-a4f3-11e6-9c28-380fae0925d4.png)

- オフィスは世界五ヶ所にあります: ロンドン、東京、フィリピンのマニラ、インドネシアのジャカルタ、メキシコシティ
- 最近ベトナムのホーチミンにも拠点ができました
- 社員は全体で 500 名を超えました。インドネシアの国中に 12 のブランチオフィス（支店）ができて、セールス（営業）が 300 人以上います
　※資料の220はpermanentsとcontractorsのみの数字、500はoutsourcersを含んだ数字
- プロダクト開発を行うチームは全体で 50 名弱です。半数以上がエンジニアで、エンジニアの半数以上が web エンジニア（サーバサイド）です
- 参考：2016年9月末時点

|| Web | iOS/Android | SRE | Design | Total |
| --- | --- | --- | --- | --- | --- |
| London | 4 | 0 | 0 | 1 | 5 |
| Tokyo | 8 | 7 | 3 | 3 | 21 |
| Manila | 8 | 2 | 0 | 2 | 12 |
| Jakarta | 2 | 0 | 0 | 2 | 4 |
| Mexico City | 1 | 0 | 0 | 0 | 1 |
| Total | 23 | 9 | 3 | 8 | 43 |

- プロダクト開発チームはロンドン・東京・マニラが多いです。他のオフィスにもエンジニアとデザイナーが若干名います
- プロダクト開発チームだけでなく、サービスに関わるほとんどの人が GitHub と Slack を使って日々コミュニケーションをしています

![slide04](https://cloud.githubusercontent.com/assets/4939774/20208741/836ab91c-a833-11e6-971e-472e5b39c4e0.png)

- 2015 年 4 月にリクルートマーケティングパートナーズに買収され、完全子会社になりました
- リクルートマーケティングパートナーズは、ゼクシィ・カーセンサーなどの紙媒体メディアや、スタディサプリという教育サービスを提供しています
- 2016 年の 2 月に、受験サプリというサービスを Quipper プラットフォームへ移管しました。プロダクト開発やサービス運営を Quipper と RMP が共同で行っています
- 買収に至った経緯は、 RMP 社長の山口が、渡辺と同じ「最高の教育を、必要とする全ての人に、リーズナブルな価格で届けたい」という想いを持っていたからです。山口が立ち上げた受験サプリと、渡辺が立ち上げた Quipper を統合し、全世界に向けて提供していくために、リクルートグループに join しました

![slide05](https://cloud.githubusercontent.com/assets/14937062/20047173/f9534104-a4f4-11e6-8883-9fc4403277fd.png)

- Quipper が提供しているプロダクトは以下の三つです。 Quipper School、 Quipper Video、スタディサプリ
- Quipper School は、先生が宿題を管理しやすくするサービスです。学校の先生はとても忙しく、宿題の回収や採点などに時間がかかり、負担がかかっていたので、それを解決するために作りました。オンラインで完結し、採点も自動で行われるため、先生の負担を減らせます
- Quipper Video は、生徒が有名講師の講義動画を視聴できるサービスです。定額料金で見放題で、演習問題もあります
- Quipper School はフィリピンを中心にインドネシアやメキシコでサービスを提供しています。 Quipper Video はインドネシアを中心にフィリピン・メキシコでサービスを提供しています
- スタディサプリは Quipper School と Quipper Video の日本版で、サービス名称は違いますが中身は Quipper のサービスとほぼ同じです
- 開発スタイルは [GitHub Flow](https://guides.github.com/introduction/flow/) で、変更は原則すべて Pull Request でコードレビューを行っています
- 特徴として、海外版と日本版などで、ソースコードのリポジトリを分けていません。エンジニアは全員が同じリポジトリにコミットし、国をまたいで相互にレビューします。機能やビジュアルの違いはビルド時のオプションなどで切り替えています

## Appendix

- 2016年9月末よりQuipper日本オフィスのプロダクトチームでブログを始めたので、是非ご覧ください
　http://quipper.hatenablog.com/entry/2016/09/29/124325