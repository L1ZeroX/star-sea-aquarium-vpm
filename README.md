# 星海水槽のVCC配布

VCCの **Settings → Packages → Add Repository** で、次のURLを追加してください。

```
https://raw.githubusercontent.com/L1ZeroX/star-sea-aquarium-vpm/main/index.json
```

Unityを閉じて、対象のワールドの **Manage Project** で **星海水槽 (Star Sea Aquarium)** を選びます。初回は追加、次回からはバージョンを更新します。Unityを開き直すと水槽のファイルが適用されます。

設置済みの水槽は、その場に置いたままで更新できます。ワールドを既存のBlueprint IDで再アップロードすると、そのワールドで育てた魚とコインを引き続き使えます。別ワールドへの移動には、ゲーム内の引き継ぎコードを使います。

新規に設置するときは、Unityの **Window → TextMeshPro → Import TMP Essential Resources** を実行し、パッケージ内の `Assets/StarSeaAquarium/Personal aquarium.prefab` を配置してください。

確認環境はUnity 2022.3.22f1、VRChat SDK - Worlds 3.10.6です。同梱フォントのライセンスはパッケージ内の `Assets/StarSeaAquarium/Panel/OFL.txt` に記載しています。
