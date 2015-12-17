#Unreal Engineを触る

  この記事は[KMCアドベントカレンダー](http://www.adventar.org/calendars/809#list-2015-12-12)23日目の記事です
  22日目の記事はhogehogeでした
  
  こんにちは KMC-1回生のid:taiseiです。
  今日はUnreal Engine 4の話を書きます。

## Unreal Engine 4とは

  Unreal Engine 4 とは今年(2015/3)無償化されたゲームエンジンです。
  一つ前のバージョンであるUnreal Engine 3は、リアルタイム3Dにも関わらず2Dアニメーションにしかみえないという「Guilty Gear Xrd -Sign-」というゲームに使われていたり、Unreal Engine 4は「ストリートファイターV」「ファイナルファンタジーVⅡ」「鉄拳7」「キングダムハーツⅢ」「ドラゴンクエストXⅠ」といった国産ソフトが次々と採用を発表する程の実績があります。
  
  Unreal Engine 4はゲーム販売において、四半期の売上が3000ドルを超えた場合に限り、5%のロイヤリティが発生します。およそ30万円ですね。個人、企業で提供されるツールに差異はなく、個人の開発者にとっては非常に強力な開発ツールが降ってきたというわけです。

##特徴

  Unreal Engine 4は強力なレンダラーで非常に綺麗なグラフィックを提供してくれます。裏を返せば、まともに動かすには相応のスペックが必要です。推奨ハードはWindows7/8、 クアッドコアIntelまたはAMDの、2.5GHz以上のプロセッサ、 8GB RAM、 DirectX11対応のグラフィックカードとあります。かなりのハイスペックが要求されていますね。
  また、クロスプラットフォームで、Windows PC、Mac OS X、iOS、Android、VR、Linux、SteamOS、HTML5、デベロッパー登録すればPS4、XBoxOneで使用できます。非常に幅広いですね。
  さらに、Unreal Engine 4はGitHubでソースコードを誰でも閲覧、改変できます。約300万行のc++のソースコードがあるそうです。

##導入した

  UnrealEngine4の公式サイトへ行くと右上にダウンロードと書いてあるので、それを押すとダウンロードできます。EpicGamesのアカウントを登録する必要があります。Windows用とMac用があります。
  ここでダウンロードするのはLauncherです。というのもUnreal Engineの所有者はEpicGamesというゲーム会社で、LauncherにはEpicGamesのゲームのコンテンツも含まれています。Unreal Engine 4をインストールするには、LauncherのタブからUnreal Engine>ライブラリを選び、エンジンスロットを追加すればよいです。ちなみに、チュートリアルというタブには解説動画が、マーケットプレイスにはゲームに使えそうな素材が販売してあります。

  公式のドキュメントに、[Unity引越しガイド](https://docs.unrealengine.com/latest/JPN/GettingStarted/FromUnity/index.html)というものがあります。なんとここではUnityのエディタとUnreal Engine 4のエディタを直接比較しています。