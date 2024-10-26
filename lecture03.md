## 1.APサーバーについて調べる
- 名前：Puma
- バージョン：6.4.2
  
![899FF3E9-3EB9-403E-8DF9-1B3F8374354E_4_5005_c](https://github.com/user-attachments/assets/12289414-eaa5-459f-9026-e48e87499480)

### APサーバー終了時のアクセス確認
アクセスできませんでした

![56633A98-322E-48E4-B47F-0A033EB020A5_1_201_a](https://github.com/user-attachments/assets/b6e01636-4ed5-413f-90fb-21f652b32e86)

### APサーバー再起動

![70F12A4F-2347-42F3-BE5D-49B11DEF2D97_1_201_a](https://github.com/user-attachments/assets/f8b73486-5e8e-4d58-97bc-fd7cd6a18de1)

## 2.DBサーバーについて調べる
- 名前：MySQL
- バージョン：8.4.2

![A5F9640A-557D-4AAD-8558-50873EE0F954_4_5005_c](https://github.com/user-attachments/assets/a2bf2632-579d-4470-a68b-1c90b888ccb9)

### DBサーバー終了時のアクセス確認
アクセスできませんでした

![40B1C52D-14A1-49C7-8667-CE86761F991B_1_105_c](https://github.com/user-attachments/assets/c5ac8058-bfc4-467b-bbbb-7fd6b4993adb)

## Railsの構成管理ツール
- 名前：Bundler

## 今回の課題から学んだこと、感じたこと
- サンプルアプリケーションを起動して、ブラウザで接続した
- puma の起動•停止コマンド
  - systemd　による起動　sudo systemctl start puma.service
  - systemd　による停止　sudo systemctl stop puma.service
  - 他にも、pumactl コマンドを使う方法、kill コマンドを使う方法がある
- MySQL の起動・停止コマンド
  - sudo service mysqld start
  - sudo service mysqld stop
- 画像を相対パスで記述して Markdown に埋め込んだ
- Cloud9 が使えないので ec2 での作業でしたが、調べながらなんとかサンプルアプリケーションの起動と接続ができました。接続できた時は、とても嬉しかったです。
- 苦労しましたが、自分の手を動かすことを繰り返していけば、分からなかったことが段々と腑に落ちるような感じがしました。
