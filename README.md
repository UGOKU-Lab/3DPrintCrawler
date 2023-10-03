# 3DPrintCrawlerについて
タミヤのラダーチェーンとギアボックス、3Dプリントパーツのみで製作したクローラユニットです。  
使用するネジ類もタミヤのセットの付属品のみで完結します。  
ラダーチェーンに履板をパッチっとはめる方式なので履板形状を自由に設計できます。

本リポジトリはみなさんにより早くデータを提供するため、README含め不完全な状態で公開する、β版的な位置づけである点をご了承ください。
ご意見や改善案のある方は、Twitter、Issues、プルリクなどで問い合わせ及び提案お願いします。
次期Versionの開発に生かします。

<img src="https://user-images.githubusercontent.com/27545627/228853636-29e21a2e-c506-415f-b6e8-14e3bbe4be2f.png" width="500px"> <img src="https://user-images.githubusercontent.com/27545627/228853704-808b0868-2ea2-4d46-b55f-a8b53bc408fb.png" width="500px">

# 製作に必要なタミヤの部品
1ユニット製作するのに、それぞれ1セットずつ必要になります。

- 楽しい工作シリーズ（パーツ）No.142 ラダーチェーン＆スプロケットセット  
https://www.tamiya.com/japan/products/70142/index.html

- テクニクラフトシリーズ No.7　4速パワーギヤボックスHE  
https://www.tamiya.com/japan/products/72007/index.html

# データの説明
- フォルダ「stl」：すぐにプリントしたい方向けに各パーツをstlで置いてあります。
- フォルダ「step」：組み立ての確認用、データ編集用です。左右接続したアセンブリのデータと履板のデータをstepで置いてあります。

## データ留意事項
- 履板をプリントする際はアセンブリファイル内のものではなく、個別のデータをご使用ください。プリント用に調整してあります。きつすぎたり、ゆるすぎたりする場合はstepから編集してください。
- アセンブリファイルに含まれる基板はMultiBoardMiniという作者が開発している汎用基板です。こちらについてはデータ公開準備中です。

# 3Dプリント
プリントには250x250サイズ程度の3Dプリンタが必要になります。より普及している220x220サイズのプリンタではプリントできないのでご注意ください。（後日220x220サイズのプリンタでもプリント可能な全長短縮版もアップ予定ですのでもう少々お待ちください。）
すべての部品において充填率は15%ほどで問題ないと思います。
## main-flame
250x250サイズのプリンタでも収めるためには斜めに配置する必要があります。
手前の工具穴、左右接続パーツ挿入部、長穴にはサポートが不要なためサポートブロッカーを配置します。
左右接続パーツ挿入部は条件によりフィラメントが垂れ下がることがありますが、その場合はやすり等で除去してください。おそらくサポート材を外すより楽です。

<img src="https://user-images.githubusercontent.com/27545627/229107219-d3fb3b1d-b367-4703-b30e-47b1f0fc8430.png" width="500px"><img src="https://user-images.githubusercontent.com/27545627/229107858-cdce1d53-ec5e-467c-9672-2c0a841121db.png" width="500px">

## track-shoe
サポート材は不要ですが、接地面積が小さいため外れやすいです。外れる場合はBrimを使いましょう。外れるリスクをとるか、Brimを除去する手間をとるかといったかんじです。

<img src="https://user-images.githubusercontent.com/27545627/229108441-a90e394f-45e0-4bb4-a4e2-bddfd192d152.png" width="500px">

## その他パーツ
その他のパーツは積層方向が正しければ特段留意点はありません。

# 組み立て
## 使用工具
- ＋ドライバーNo.2・2本（1本は細軸が望ましい）
- ナットドライバ 5.5
- ニッパー

## 組み立て参考図
- スプロケットとクランクプレートの固定：3×8mmタッピングビス（ラダーチェーン付属）　　
- ギアボックス固定：3×10mmタッピングビス（ギヤボックス付属）
- アイドラシャフト固定：3×12mmタッピングビス（ラダーチェーン付属）
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/cd8ea3dc-18a9-4bdb-ab63-537413527758" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/6b52ac2e-49dc-4629-8ad1-bbc718be4c46" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/2aea14ea-298b-4129-934f-56cb2e95d067" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/7d3d1193-fd5c-4afd-8138-8c068c410209" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/8adcf50c-cfe9-413f-87d0-5329c3ca804c" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/471bc2ca-bfef-4471-ad0c-18074a562fd0" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/1e77ca79-f89c-4431-b7db-10061b217158" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/e99b57ea-ad1d-43d2-a853-91a01ba6455e" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/1f10a8be-8486-47be-a1c4-ffdf55aa20d5" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/eb563d45-eec9-487a-a9e0-928741e93c30" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/d1e2f600-72d4-4f73-abcb-1b461b835604" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/5bbbda6e-5040-4c3b-a44e-ac1b8345f4f9" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/2242e55f-36c3-4315-a024-ae8d8fab5f6d" width="300px">
<img src="https://github.com/TomohiroAoki/3DPrintCrawler/assets/27545627/35ff3196-e249-4363-b850-03ab1f82e5a2" width="300px">






# ライセンス
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/deed.ja">クリエイティブ・コモンズ 表示 4.0 国際 ライセンス</a>の下に提供されています。

本データおよび本データにより製作したクローラーは良識の範囲で自由に非営利、営利問わず使用できます。また、改変、再配布も可能です。
ただし、再配布の際には「3DPrintCrawler」と本リポジトリのリンクを掲載してください。  
また、本データにより製作したクローラーを公の場で使用、SNS等で紹介する場合はなるべく「#3DPrintCrawler」と本リポジトリのリンクを掲載してください。  
また、本データにより生じた損害等の一切の責任を負いかねますので、ご了承ください。

# 今後の展望
今回はInventor（学生ライセンス）でデータを作成[^1]しましたが、次期バージョンはFreeCADなどフリーかつオープンソースの3DCADでデータを作成し、だれでもネイティブで編集できるようにしようと考えています。
また、将来的には寸法を入力するとそのサイズの3Dプリントクローラの3Dモデルが自動生成されるツールにまで発展させたいと考えています。
[^1]:データは学生時代に製作したものです。社会人になった今となってはInventorのライセンスを購入しないと編集もできません。
# 最後に
本作品は作者の元インターン先でもある**株式会社CuboRex**のクローラユニット「**CuGo**」シリーズにもインスピレーションを受けています。  
また、株式会社タミヤの製品があってこそ実現できました。  
さらに、3Dプリント履板をタミヤのラダーチェーンにはめるというアイデアは研究室にあった機体より得たものです。  
この場をお借りして株式会社CuboRex、株式会社タミヤ、そして先述の機体を製作した研究室の先輩に敬意を表します。
