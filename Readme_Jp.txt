************************************************************
      Star PassPRNT Web SDK Ver 1.4.0
         Readme_Jp.txt                  スター精密（株）
************************************************************

 1. 概要
 2. 内容
 3. 適用
 4. 著作権
 5. 変更履歴

==========
 1. 概要
==========

  本パッケージは、Star PassPRNT(iOS / Android / Windows UWP)用のWeb SDKです。
  “PassPRNT”とは、外部アプリケーション（以降、”連携アプリ”とする）と
  スターデバイス（以降、”デバイス”とする）の間に配置するアプリケーションです。
  このアプリケーションは、連携アプリからレシートのデザイン、用紙幅、その他に
  関連する情報を受け取ると印字データに変換して、プリンタに送信を行います。
  よって、連携アプリはプリンタとの通信に関わる部分の設計-開発の必要がありません。
  またプリンタステータスの監視や印刷成否の判定も行うため、連携アプリは
  それらの実施も不要となります。

  またレシートデザインは、HTMLレイアウトに対応しているため、
  デバイス独自のコマンド仕様を理解する必要はありません。

  詳細は別紙ドキュメントファイルを参照ください。

==========
 2. 内容
==========

  PassPRNT_Web_SDK_Ver1.4.0
  |
  | Readme_En.txt                       // リリースノート(英語)
  | Readme_Jp.txt                       // リリースノート(日本語)
  | SoftwareLicenseAgreement.pdf        // ソフトウエア使用許諾書(英語)
  | SoftwareLicenseAgreement_jp.pdf     // ソフトウエア使用許諾書(日本語)
  | UsersManual_Android.url             // User Manualへのショートカット
  | UsersManual_iOS.url
  | UsersManual_UWP.url
  +- Samples                            // Star PassPRNT用サンプルプログラム

=============
 3. 適用
=============

  ■ 対象ソフトウェア
   PassPRNT Ver 2.11.0 for iOS / Android / Windows UWP

  ■ 対象プリンタモデル
   Users Manualをご参照ください。

===========
 4. 著作権
===========

  スター精密（株）Copyright 2020-2025

==================================
 5. Star PassPRNT Web SDK 更新履歴
==================================

 Ver 1.4.0
  2025/05/19  : `size`クエリを`384`, `406`, `576`, `832`に変更
                対象OS、対象ソフトウェアを更新

 Ver 1.3.0
  2023/09/07  : `size`クエリに`2w6`と`2w7`を追加
                対象OS、対象ソフトウェアを更新

 Ver 1.2.0
  2023/04/10  : `gap`クエリを追加
                `size`クエリに`1`と`2w5`を追加
                対象OS、対象ソフトウェアを更新

 Ver 1.1.0
  2021/10/29  : ブザー(BU01), メロディースピーカー(mC-Sound)のサポートを追加

 Ver 1.0
  2020/01/23  : 新規リリース
