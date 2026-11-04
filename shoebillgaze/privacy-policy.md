---
title: ShoebillGaze プライバシーポリシー / Privacy Policy
---

# ShoebillGaze プライバシーポリシー

制定日：2026年11月3日
改定日：2026年11月4日（「開発者への寄付」リンクの追加に伴う改定）
対象：Chrome 拡張機能「ShoebillGaze - ハシビロコウがこちらを見ている拡張機能」（以下「本拡張機能」）
開発者：うめだよ

[English version below](#english)

---

## 1. 基本方針

本拡張機能は、利用者の個人情報や閲覧履歴を収集しません。外部のサーバーへの送信も行いません。本拡張機能が保存するデータは、すべて利用者のブラウザ内（端末内）にのみ保存されます。

本拡張機能の設定画面には、任意の「開発者への寄付」リンクがあります。寄付をされた場合に開発者が受け取る情報の取り扱いは、第7章に記載します。

## 2. 収集する情報

本拡張機能は、次の情報を**収集・送信しません**。

- 氏名、メールアドレス、住所などの個人を特定できる情報
- 閲覧したウェブサイトの URL、ページの内容、入力内容
- 閲覧履歴、検索履歴、Cookie
- 位置情報、端末の識別子
- 利用状況の統計（アクセス解析）

（寄付をされた場合に、Ko-fi および決済サービスを通じて開発者が受け取る情報については、第7章をご覧ください。）

## 3. 端末内に保存する情報

本拡張機能は、動作に必要な次の情報を Chrome の拡張機能用ストレージ（chrome.storage.local）に保存します。これらは利用者の端末内にのみ保存され、開発者を含む第三者に送信されることはありません。また、Chrome の同期機能による他の端末への同期も行いません。

| 情報 | 内容 |
|---|---|
| 表示設定 | 表示の有効／無効、表示サイズ、移動モードの状態 |
| 表示位置 | 画面上のハシビロコウの表示位置（画面の端からの距離） |
| 動作頻度の設定 | 選択した動作頻度、開発者向けの時間倍率 |
| 動作のタイミング | 次に動く予定の時刻、各動作が最後に行われた時刻 |
| 動作の予約情報 | 動作を表示するタブを決めるための一時的な情報（予約の番号、ブラウザ内部のタブ番号、有効期限、動作の種類）。動作の確定または期限切れ（約10秒）で消去され、確定済みの予約の番号のみ最大10分間保持します |
| 動作ログ | 直近20件までの動作の記録（時刻と動作の種類のみ） |

上記には、閲覧中のページに関する情報は含まれません。

## 4. ウェブページへのアクセスについて

本拡張機能は、閲覧中のページの最前面にハシビロコウの画像を表示するため、すべてのウェブサイトで動作します。このためインストール時に、すべてのサイトへのアクセスに関する確認が表示されます。

ページ上で本拡張機能が行うのは、ハシビロコウの画像を追加して表示することだけです。画像の配置のために表示領域の大きさを参照し、表示位置を移動する操作（ドラッグ）の間だけマウスの位置を参照しますが、これらは画像の表示にのみ使い、保存や送信はしません。また、見えていないタブで動作しないよう、そのページが画面に表示されているかどうかを参照します。これも動作の判定にのみ使い、保存や送信はしません。ページの内容、URL、入力内容を読み取ることはありません。

## 5. 第三者への提供

本拡張機能は情報を収集しないため、第三者への提供、販売、譲渡は一切行いません。広告、アクセス解析ツール、外部サービスも使用していません。寄付をされた場合に開発者が受け取る情報も、第三者へ提供、販売、譲渡しません（法令に基づく場合を除きます）。

## 6. 外部との通信

本拡張機能は、インターネット上のサーバーと通信しません。表示する画像はすべて本拡張機能に含まれており、外部から読み込むことはありません。また、外部のプログラムを読み込んで実行することもありません。

設定画面の「開発者への寄付」リンクを押した場合に限り、外部サイト Ko-fi（https://ko-fi.com/umedayo）が新しいタブで開きます。これは通常のリンクとして開くもので、本拡張機能から Ko-fi へ情報を送信することはありません。

## 7. 開発者への寄付について

本拡張機能の設定画面には、任意の「開発者への寄付」リンクがあります。寄付の有無によって、本拡張機能の機能に違いはありません。

寄付の手続きと決済は、Ko-fi および決済サービス（PayPal、Stripe）上で行われます。本拡張機能は、クレジットカード情報などの決済情報を扱わず、寄付をしたかどうかも記録しません。

寄付をされた場合、Ko-fi および決済サービスの仕組みにより、次の情報が開発者に共有されます。

| 共有元 | 開発者に共有される情報 |
|---|---|
| Ko-fi | 寄付の際に入力された表示名、メールアドレス、メッセージ（任意） |
| PayPal で支払った場合 | 氏名、メールアドレス |
| Stripe（カード決済）で支払った場合 | 氏名、メールアドレス、カードに登録された住所の一部など、決済サービスが受取人に通常提供する情報 |

開発者は、これらの情報を次の目的にのみ使用します。

- 寄付へのお礼の連絡
- 寄付に関するお問い合わせ、返金などへの対応
- 法令に基づく記録の保存

Ko-fi、PayPal、Stripe での情報の取り扱いは、各社のプライバシーポリシーに従います。

- Ko-fi：Ko-fi の各ページ下部にある「Privacy Policy」
- PayPal：https://www.paypal.com/jp/webapps/mpp/ua/privacy-full
- Stripe：https://stripe.com/privacy

## 8. 保存した情報の削除

- 動作ログは、開発者モードの「ログ消去」から削除できます。
- 本拡張機能をアンインストールすると、端末内に保存されたすべての情報が Chrome によって削除されます。

## 9. 本ポリシーの変更

本ポリシーの内容は、必要に応じて変更することがあります。変更した場合は、このページで公開し、制定日の下に改定日を記載します。情報の取り扱いを大きく変更する場合は、本拡張機能の更新内容でもお知らせします。

## 10. お問い合わせ

本ポリシーに関するお問い合わせは、次の窓口までお願いします。

https://github.com/umedayo-clunker/privacy-policies/issues

---

<a id="english"></a>

# ShoebillGaze Privacy Policy (English)

Effective date: November 3, 2026
Revised: November 4, 2026 (added the "Donate to the developer" link)
Applies to: the Chrome extension "ShoebillGaze" (the "Extension")
Developer: Umedayo

*The Japanese version above is the original. This English version is a translation.*

## 1. Summary

The Extension does not collect personal information or browsing history, and it does not send any data to external servers. All data the Extension saves is stored only in your browser on your device.

The Extension's settings screen includes an optional "Donate to the developer" link. Section 7 explains how information the developer receives when you donate is handled.

## 2. Information We Do Not Collect

The Extension does **not collect or transmit**:

- Personally identifiable information such as your name, email address, or postal address
- The URLs, content, or form input of the web pages you visit
- Browsing history, search history, or cookies
- Location data or device identifiers
- Usage statistics (analytics)

(For information the developer receives through Ko-fi and payment services when you donate, see Section 7.)

## 3. Information Stored on Your Device

The Extension saves the following information, which it needs to work, in Chrome's extension storage (chrome.storage.local). This information stays on your device and is never sent to the developer or any third party. It is not synced to your other devices through Chrome Sync.

| Information | Details |
|---|---|
| Display settings | Whether the display is on or off, display size, and move mode |
| Display position | Where the shoebill appears on the screen (distance from the screen edges) |
| Frequency settings | Your chosen motion frequency and the developer time-scale setting |
| Motion timing | When the next motion is scheduled and when each motion last occurred |
| Motion reservation | Temporary information used to decide which tab shows a motion (reservation ID, the browser's internal tab number, expiry time, and motion type). It is cleared when the motion is confirmed or expires (about 10 seconds); only the IDs of confirmed reservations are kept, for up to 10 minutes |
| Motion log | The last 20 motions (time and motion type only) |

None of this information relates to the pages you visit.

## 4. Access to Web Pages

The Extension runs on all websites so that it can show the shoebill image on top of the page you are viewing. For this reason, Chrome asks for access to all sites when you install it.

On a page, the Extension only adds and displays the shoebill image. It reads the size of the visible area to position the image, and reads the mouse position only while you drag the image to move it. This information is used only to display the image and is never stored or transmitted. To avoid moving in tabs you cannot see, it also checks whether the page is currently visible on screen; this is used only for that decision and is never stored or transmitted. The Extension does not read page content, URLs, or anything you type.

## 5. Sharing with Third Parties

Because the Extension does not collect information, it never shares, sells, or transfers information to third parties. It does not use advertising, analytics tools, or external services. Information the developer receives when you donate is also never shared, sold, or transferred to third parties, except where required by law.

## 6. Network Communication

The Extension does not communicate with any server on the internet. All images it displays are bundled with the Extension and are not loaded from external sources. It does not load or execute any remote code.

Only when you click the "Donate to the developer" link on the settings screen does the external site Ko-fi (https://ko-fi.com/umedayo) open in a new tab. It opens as an ordinary link, and the Extension does not send any information to Ko-fi.

## 7. Donations to the Developer

The Extension's settings screen includes an optional "Donate to the developer" link. Whether or not you donate does not change any of the Extension's features.

Donations and payments are handled on Ko-fi and payment services (PayPal and Stripe). The Extension does not handle payment information such as card details, and it does not record whether you have donated.

When you donate, the following information is shared with the developer through Ko-fi and the payment services:

| Shared by | Information shared with the developer |
|---|---|
| Ko-fi | The display name, email address, and optional message you enter when donating |
| PayPal (if you pay with PayPal) | Your name and email address |
| Stripe (if you pay by card) | Your name, email address, part of your card's billing address, and other information payment services normally provide to recipients |

The developer uses this information only to:

- Thank you for your donation
- Respond to inquiries, refunds, and other matters related to your donation
- Keep records required by law

Ko-fi, PayPal, and Stripe handle your information under their own privacy policies:

- Ko-fi: "Privacy Policy" at the bottom of each Ko-fi page
- PayPal: https://www.paypal.com/jp/webapps/mpp/ua/privacy-full
- Stripe: https://stripe.com/privacy

## 8. Deleting Stored Information

- You can delete the motion log with "ログ消去" (Clear log) in developer mode.
- When you uninstall the Extension, Chrome deletes all information it stored on your device.

## 9. Changes to This Policy

This policy may be updated when necessary. Changes will be posted on this page, with the revision date added below the effective date. If the way information is handled changes significantly, it will also be announced in the Extension's update notes.

## 10. Contact

For questions about this policy, please contact us here:

https://github.com/umedayo-clunker/privacy-policies/issues
