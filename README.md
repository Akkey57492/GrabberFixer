# 説明
Grabberを起動してしまいましたか?<br>
そんな時はこのFixerを使ってみましょう。<br>
最近のGrabberには、変更後のパスワードを抜くようなプログラムも仕込まれていたりします。<br>
これは、Discordに使われているJavaScriptが改ざんされていることが原因です。<br>
このツールは、改ざんされたJavaScriptを修正して、アカウントの復帰を手伝います。

# 仕組み
まずFixerを起動すると...<br>
・Discord<br>
・Discord PTB<br>
・Discord Canary<br>
のJavaScriptのプログラムを確認します。<br>
そのJavaScriptのプログラムが改ざんされていた場合は、修正を開始します。<br>
・注: もし改ざんされていない場合はFixerはその旨を通知して終了します。<br>
修正する内容としては、正規のJavaScriptに置き換えるだけです。<br>
この時、いったんDiscordアプリを落としてから行います。<br>

# BetterDiscord
ほとんどの場合BetterDiscordのasarファイルも改ざんされています。<br>
そのため、Fixerはこのasarファイルも確認して、改ざんされていた場合は修正します。<br>

# 通知
もしすべての修正が終了すると、いくつかの情報が通知されます。<br>
WebhookのURLやWebhookの名前、サーバーのID等です。<br>
