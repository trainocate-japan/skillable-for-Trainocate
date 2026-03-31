# <span style="color: rgba(0, 0, 0, 0.0); font-size: small">skillable-for-Trainocate</span>
# Skillable演習でよくあるトラブル
## トレノケートオリジナルコースの場合
- キーボード入力ができない

	演習を閉じて再接続

	それでもだめなら演習環境の再起動
  
- 演習環境の再起動

	演習ウィンドウ左上の→[⚡(稲妻マーク)]-[Power]-[Reset/Reboot Machine]
  
- 1回のキータイプで文字が2つ入る

	[半角/全角]を1回押す (駄目なら何度か繰り返す)
  
	[半角/全角]を押して日本語モードにしたあと、通知エリアの[あ]をクリックして[A]の英数字モードにすると直る場合もある

- 解像度が下がってしまった場合

	演習環境のディスプレイのプロパティで1024x768以上に設定

- 演習環境のホストから、演習マシンに文字列を貼り付ける手順

1. 演習仮想マシン内部でメモ帳などを起動
1. 演習ウィンドウ左上⚡(稲妻マーク)をクリック
1. [Type Text]-[Type Clipboard Text]を選択
1. 演習仮想マシンのクリップボード経由で文字列が貼り付く (あまり文字数が多いと取りこぼしがある)

※演習環境の設定によっては、表示されたダイアログボックスに文字列を貼り付けてから転送する場合もある

## Azureを使う場合
AzureおよびMicrosoft 365の管理サイトでは多要素認証(MFA: Multi-Factor Authentication)が要求されます。MFAにはMicrosoft Authenticatorを推奨しますが、
トレノケートではTime-Based One Time Password (T-OTP) を利用します。

※コースによってはMFAを使用せず、**一時パスワード** を使う場合もあります。

### Time-Based One Time Passwordの使用
使用する Time-Based One Time Password サイト

[TOTP Token Generator](https://otp.trainocate.jp) 

詳細は以下を参照してください。

[Time-based One Time Password 操作ガイド](https://teachme.jp/69155/manuals/41617696)

### 参考: Microsoft Authenticator
トレノケートのコースでは原則として使用しません。

[Microsoft Authenticator 操作ガイド](https://teachme.jp/69155/manuals/32304844)

