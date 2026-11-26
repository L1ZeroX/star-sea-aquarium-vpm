# 星海水槽のVCC配布

VCCの **Settings → Packages → Add Repository** で、次のURLを追加してください。

```
https://raw.githubusercontent.com/L1ZeroX/star-sea-aquarium-vpm/main/index.json
```

Unityを閉じて、対象のワールドの **Manage Project** で **星海水槽 (Star Sea Aquarium)** を選びます。初回は追加、次回からはバージョンを更新します。Unityを開き直すと水槽のファイルが適用されます。

設置済みの水槽は、その場に置いたままで更新できます。ワールドを既存のBlueprint IDで再アップロードすると、そのワールドで育てた魚とコインを引き続き使えます。別ワールドへの移動には、ゲーム内の引き継ぎコードを使います。

別ワールドへ丸ごと移すときは、両方の水槽を1.16.0以降に更新してください。筐体下の **引き継ぎ** からコードを発行し、移行先に貼り付けます。魚のレベルやエンチャント、ステージ、探索、給餌、実績などのセーブを引き継ぎます。確定前のセーブは **引き継ぎ前のコード** に残ります。

魚の **Lv.表示** は、Lv.1〜9が白、Lv.10〜19がミントグリーン、Lv.20〜29がオレンジ、Lv.30がピンクです。エンチャントの名前とレア度には従来の色が付きます。

新規に設置するときは、Unityの **Window → TextMeshPro → Import TMP Essential Resources** を実行し、パッケージ内の `Assets/StarSeaAquarium/Personal aquarium.prefab` を配置してください。

確認環境はUnity 2022.3.22f1、VRChat SDK - Worlds 3.10.6です。同梱フォントのライセンスはパッケージ内の `Assets/StarSeaAquarium/Panel/OFL.txt` に記載しています。
