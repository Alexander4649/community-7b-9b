応用課題フェーズ
* 課題7b グループ作成機能
* 課題8b グループ入退会機能
* 課題9b グループメール機能

【&nbsp;】：半角スペースと同じサイズの空白
【&thinsp;】：&nbsp;の空白より小さい空白
【&ensp;】：半角スペースより間隔がやや広い空白
【&emsp;】：全角スペースとほぼ同じサイズの空白

〜〜〜課題8b グループ入退会〜〜〜
* routes設定
resources :groups, except: [:destroy] do
    get "join" => "groups#join"
  end

* 