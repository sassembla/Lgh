| pattern | Light > Baking | Obj > Lightmap Static | Scene > Ambient GI | bake result | shadow in lightmap | color | prefab has lightmap |
|:--|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1.0|realtime	|not	|realtime	|Snapshot			|-	|origin		|-	|
|2.0|realtime	|not	|bake		|Snapshot			|-	|origin		|-	|
|3.0|realtime	|static	|bake		|Snapshot, Lightmap	|-	|contrast+	|√	|
|4.0|bake		|static	|bake		|Snapshot, Lightmap	|√	|bright+	|√	|
|5.0|bake		|static	|realtime	|Snapshot, Lightmap	|√	|bright-	|√	|
|6.0|realtime	|static	|realtime	|Snapshot, Lightmap	|-	|contrast+	|√	|
|7.0|bake		|not	|bake		|Snapshot			|-	|no light	|-	|
|8.0|bake		|not	|realtime	|Snapshot			|-	|no light	|-	|