# Waypoint and Echo Map -- The Heroes Journey

![waypoints](https://github.com/perotan/thj-waypoints/blob/main/thj-waypoints.png)

If you find any mistakes or issues, please let me know via Discord (username: pero).

# Features
- The map shows the approximate locations of Waypoints and Echoes in each zone, 
based on the official wiki: 
[Waypoint list](https://thj-wiki.web.app/exploration-and-combat/teleport/) and 
[Echo of the Past](https://thj-wiki.web.app/exploration-and-combat/echo-of-the-past/). 
When unclear, I referred to player discussions in the official Discord and
ultimately confirmed the locations through on-site investigation. 
- The base map prioritizes the placement of zone lines relative to each zone’s outer shape,
omitting details about terrain and buildings to reduce noise in the waypoint and echo information.
- The scale of zone sizes is standardized, enabling players to estimate running distances in advance (loc 1000 = 7pt).
However, towns and dungeons are scaled up by 2x to make them more legible. 
- A searchable [PDF version](https://github.com/perotan/thj-waypoints/blob/main/thj-waypoints.pdf) is available,
and the map can also be re-edited using Illustrator. 
- Minimum font size is set to 5pt, ensuring readability when printed at 300 dpi on A3 paper.

# Recommendation
Some zones, like Nadox, do not have default maps.
I recommend installing [Brewall map files](https://www.eqmaps.info/eq-map-files/).
However, for zones like Bazaar, where maps may be outdated, you can overwrite them with THJ files to avoid issues:

- Delete `maps/Brewall/bazaar.txt`, `bazaar_1.txt`, `bazaar_2.txt`.
- Copy `maps/bazaar.txt`, `bazaar_1.txt`, `bazaar_2.txt`, and `bazaar_3.txt` into the `Brewall` folder.
- Switch to the `Default` map and then back to the `Brewall` map.

# Maintenance
This PDF retains Adobe Illustrator metadata, so further edits are possible.
The Apple SF Mono font can be downloaded [here](https://developer.apple.com/fonts/).

# Issues
As THJ continues to expand, it will eventually be impossible to fit the map onto A3 paper—it’s already at its limits.
Additionally, Illustrator is expensive, limiting the number of people who can edit the map.
After 30 years of using Illustrator, my spine instinctively rejects any other vector tools.

# Reference
- [Waypoint list - THJ wiki](https://thj-wiki.web.app/exploration-and-combat/teleport/)
- [Waypoint list - THJ Database Interface](https://www.thjdi.cc/waypoints)
- [Waypoint map - THJ Database Interface](https://www.thjdi.cc/zones)
- [Echo of the Past list - THJ wiki](https://thj-wiki.web.app/exploration-and-combat/echo-of-the-past/)
- [My blog (Japanese only)](https://perotanz.hatenablog.com/entry/2025/01/25/030242)


# In Japanese
# ウェイポイントとエコーの地図
間違いなど見つけたらDiscordのperoまで。

# 特徴
- Waypoint や Echo がゾーンのどのあたりにあるのか、公式 wiki の
[ここ](https://thj-wiki.web.app/exploration-and-combat/teleport/) と
[ここ](https://thj-wiki.web.app/exploration-and-combat/echo-of-the-past/) をベースにした。
はっきりしない場合は公式 Discord のプレイヤー間の発言から推測し、最終的には実際に現地で調査した。
- ベースになる地図そのものはゾーンラインがゾーンの外形のどの位置にあるのかという点を重視し、
ゾーンの地形や建造物の詳細は趣旨のウェイポイントとエコーの情報のノイズになってしまうので出来るだけ書かないようにした。
- ゾーンの大きさの比率を統一し、走る距離を事前に把握できるようにした。(loc 1000 = 7pt)
ただし、街やダンジョンなどはそのままのスケールでは小さすぎて潰れてしまうため倍のサイズにした。
- 検索が出来るように [PDF 版](https://github.com/perotan/thj-waypoints/blob/main/thj-waypoints.pdf) を用意した。
また Illustrator で再編集できるようにした。
- 文字サイズの下限を 5pt として、300dpi のプリンタで A3 用紙に印刷した場合に判読ができるようにした。

# おすすめ
Nadox などデフォルトでマップが用意されていないゾーンがある。
[Brewall さんのマップファイル](https://www.eqmaps.info/eq-map-files/) をインストールすることをお勧めする。
Bazaar など一部のゾーンで時代の異なるマップになってしまうので、その際は THJ のファイルで上書きすることで回避できる。
- `maps/Brewall/bazaar.txt`, `bazaar_1.txt`, `bazaar_2.txt` を削除
- `maps/bazaar.txt`, `bazaar_1.txt`, `bazaar_2.txt`, `bazaar_3.txt` を `Brewall` フォルダにコピー
- `Default` マップに変更、`Brewall` マップに変更

# 保守
この PDF には Adobe Illustrator のメタデータを削除していないので再編集ができる。
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
- [ブログ](https://perotanz.hatenablog.com/entry/2025/01/25/030242)
