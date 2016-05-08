# chainer-gogh-other-example

fork元: [mattya/chainer-gogh](https://github.com/mattya/chainer-gogh)

このリポジトリは、以下の投稿のデータ、結果を残したものです。

- [Chainerでの画風を変換するアルゴリズム実装をカジュアルに試す | Qiita](http://qiita.com/daisukelab/items/d08fb878b87c94218dfb)

詳しくは上記をご覧ください。
プログラム自体はfork前から変更はありません。

## 実行コマンドライン
	$ python chainer-gogh.py -m vgg -i mytry_images/damn_cat.png -s mytry_images/Kandinsky_compositionVIII_right.jpg -o result1_Kandinsky

	$ python chainer-gogh.py -m vgg -i mytry_images/damn_cat.png -s mytry_images/Degas_dancers.jpg -o result2_Degas

	$ python chainer-gogh.py -i mytry_images/damn_cat.png -s mytry_images/Degas_dancers.jpg -o result3_Degas_NIN


-

最後になりますが、
- 成果を公開していただいたPreferred Research様に感謝致します。
- スタイル画像はこちらからダウンロードさせて頂きました。ありがとうございます。<br>[Earl Art Gallery | http://art.pro.tok2.com](http://art.pro.tok2.com)
