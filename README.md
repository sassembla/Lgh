| pattern | Light > Baking | Obj > Lightmap Static | Scene > Ambient GI | bake result | shadow in lightmap | color | prefabricate |
|:--|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1.0|realtime	|not	|realtime	|Snapshot			|-	|origin		|c	|
|2.0|realtime	|not	|bake		|Snapshot			|-	|origin		|c	|
|3.0|realtime	|static	|bake		|Snapshot, Lightmap	|-	|contrast+	|c	|
|4.0|bake		|static	|bake		|Snapshot, Lightmap	|√	|bright+	|c		|
|5.0|bake		|static	|realtime	|Snapshot, Lightmap	|√	|little dark|c		|
|6.0|realtime	|static	|realtime	|Snapshot, Lightmap	|-	|contrast+	|c		|
|7.0|bake		|not	|bake		|Snapshot			|-	|no light	|c		|
|8.0|bake		|not	|realtime	|Snapshot			|-	|no light	|c		|