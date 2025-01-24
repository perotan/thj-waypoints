# Waypoint and Echo Map -- The Heroes Journey

I often see questions in ooc chats asking where waypoints and echoes are located, so I created a map.
I hope it helps someone.
That said, it’s still in a fairly rough state, and I plan to update it on a whim as errors or new discoveries arise.

![waypoints](https://github.com/perotan/thj-waypoints/blob/main/thj-waypoints.png)

# Features
- I surveyed the locations of waypoints and echoes within zones and marked them on the map.
- The base map emphasizes the position of zone lines relative to the outer shape of each zone.
To avoid unnecessary noise, details about zone terrain and buildings were omitted, as the focus is on waypoints and echoes.
- The size ratios of zones are standardized to allow for advance estimation of running distances (loc 1000 = 7pt).
However, towns and dungeons are scaled up by 2x to prevent them from becoming too small to see.
- A searchable [PDF version](https://github.com/perotan/thj-waypoints/blob/main/thj-waypoints.pdf) is available,
and the map can be edited using Adobe Illustrator.
- The minimum font size is set to 5pt to ensure readability when printed at 300 dpi on A3 paper.

# Recommendation
Some zones, like Nadox, do not have default maps.
I recommend installing [Brewall map files](https://www.eqmaps.info/eq-map-files/).
For zones like Bazzar, where the maps may be outdated, you can overwrite them with THJ files to resolve the issue:

- Delete `maps/Brewall/bazaar.txt`, `bazaar_1.txt`, and `bazaar_2.txt`.
- Copy `maps/bazaar.txt`, `bazaar_1.txt`, `bazaar_2.txt`, and `bazaar_3.txt` into the `Brewall` folder.
- Switch to the `Default` map and then back to the `Brewall` map.

# Maintenance
This PDF retains Adobe Illustrator metadata, allowing for future edits.
The Apple SF Mono font can be downloaded [here](https://developer.apple.com/fonts/).

# Issues
As THJ expands, it will eventually become impossible to fit the map onto A3 paper—it’s already pushing the limits.
Additionally, Illustrator is expensive, so only a limited number of people can edit the file.
Having used Illustrator for over 30 years, my spine instinctively rejects any other vector tools.

# Reference
- [Waypoint list - THJ wiki](https://thj-wiki.web.app/exploration-and-combat/teleport/)
- [Waypoint list - THJ Database Interface](https://www.thjdi.cc/waypoints)
- [Waypoint map - THJ Database Interface](https://www.thjdi.cc/zones)
- [Echo of the Past list - THJ wiki](https://thj-wiki.web.app/exploration-and-combat/echo-of-the-past/)


# In Japanese
# ウェイポイントとエコーの地図

Waypoint と Echo of the Past がどこにあるのかという質問を ooc で目にするので、マップを作成した。
誰かの助けになればうれしい。
ただ、まだかなり荒い状態なので、エラーや発見があれば気分次第でアップデートしていこうと思う。

# 特徴
- Waypoint や Echo がゾーンのどのあたりにあるのかを実際に調査して記載した。
- ベースになる地図そのものはゾーンラインがゾーンの外形のどの位置にあるのかという点を重視し、
ゾーンの地形や建造物の詳細は趣旨のウェイポイントとエコーの情報のノイズになってしまうので出来るだけ書かないようにした。
- ゾーンの大きさの比率を統一し、走る距離を事前に把握できるようにした。(loc 1000 = 7pt)
ただし、街やダンジョンなどはそのままのスケールでは小さすぎて潰れてしまうため倍のサイズにした。
- 検索が出来るように PDF 版を用意した。また Illustrator で編集できるようにした。
- 文字サイズの下限を 5pt として、300dpi のプリンタで A3 用紙に印刷した場合に判読ができるようにした。

# おすすめ
Nadox などデフォルトでマップが用意されていないゾーンがある。
[Brewall さんのマップファイル](https://www.eqmaps.info/eq-map-files/) をインストールすることをお勧めする。
Bazaar など一部のゾーンで時代の異なるマップになってしまうので、その際は THJ のファイルで上書きすることで回避できる。
- `maps/Brewall/bazaar.txt`, `bazaar_1.txt`, `bazaar_2.txt` を削除
- `maps/bazaar.txt`, `bazaar_1.txt`, `bazaar_2.txt`, `bazaar_3.txt` を `Brewall` フォルダにコピー
- `Default` マップに変更、`Brewall` マップに変更

# 保守
この PDF には Adobe Illustrator のメタデータを削除していないので、再編集が可能である。
Apple SF Mono フォントは [こちら](https://developer.apple.com/fonts/) からダウンロードできる。

# 問題
THJ の拡張が進むと A3 には収まらなくなるし、何なら既に限界にきている。
また、Illustrator は高価なので編集できる人は限られている。
私は 30 年以上 Illustrator と付き合っているので、これ以外のベクトル系のツールは脊椎が拒否する。

# 参考
- [Waypoint list - THJ wiki](https://thj-wiki.web.app/exploration-and-combat/teleport/)
- [Waypoint list - THJ Database Interface](https://www.thjdi.cc/waypoints)
- [Waypoint map - THJ Database Interface](https://www.thjdi.cc/zones)
- [Echo of the Past list - THJ wiki](https://thj-wiki.web.app/exploration-and-combat/echo-of-the-past/)
