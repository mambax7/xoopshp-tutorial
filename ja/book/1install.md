# 1.0 Install/Uninstall

No special measures necessary, follow the standard installation process � extract the module folder into the 

/modules 

directory in your XOOPS installation. Install the module through Admin -> System Module -> Modules.

Detailed instructions on installing modules are available in the [**Chapter 2.12 of our XOOPS Operations Manual**](https://www.gitbook.com/book/xoops/xoops-operations-guide/)

Contents

はじめに
このモジュールできること…
モジュール概観
インストール方法
アップグレード方法
サポート
とりあえず使ってみるには
トップページ
コース一覧
学習履歴
問題一覧
結果一覧
問題の解答方法
問題開始方法
ID入力
ヒントボタン
答え合わせ
結果の表示と送信
解答欄の移動
問題の追加方法
問題ファイルの準備
対応する問題ファイル形式
画像や音声などの利用
問題ファイルのアップロード
問題の更新
一般設定
その他
メニュー表記の変更方法
問題中のリンク切れ
ブラウザのクッキー
セキュリティーソフトの利用
教師向け利用のコツ

はじめに
このモジュールできること…
WWW上でHot Potatoesで作成した問題を管理できる
学生にWWW上で問題を受験させることができる
作業状況や問題の記録を把握できる
これらすべてを、機能豊富なXOOPSという環境の中で行うことができるため、フォーラムやニュース、ダウンロードなど他の各種モジュールの機能と組み合わせて、低予算で簡単に授業用ポータルサイトを構築することができます。教師向け利用のコツも参考にしてください。

モジュール概観
トップページ
学習履歴：ユーザの全学習記録を表示します。管理者には全ユーザの記録が表示されます。
コース一覧
問題一覧
List：問題名、登録日時、その他データが表示されます。
結果：記録データがある場合、結果一覧へのリンクが表示されます。
簡易表示
詳細表示
操作：モジュール管理者には記録削除のボタンが表示されます。
操作：モジュール管理者には問題の編集と削除のボタンが表示されます。
学習履歴：当該コースのすべての結果が一覧されます。管理者にはすべてのユーザの結果が表示されますが、一般ユーザには各自の結果のみが表示されます。
モジュール管理メニュー
一般設定：サイト管理者のみが、モジュール全体の基本的な諸設定を行うことができます。
問題管理：モジュール管理者はコースや問題の管理を行うことができます。: Module admins can manage courses and quizzes here.
コース追加
コース一覧
問題追加
問題一覧
インストール方法
INSTALL.txtをお読みください。

アップグレード方法
UPGRADE.txtをお読みください。

サポート
もしこのガイドでは解決しない問題がありましたら、遠慮なく作者へお問い合わせくださるか、サポートフォーラム（http://www.awajis.net/xoopshp/）で質問してください。

とりあえず使ってみるには
まずは、問題管理画面で最低一つはコースを作成してください。
次に、問題名、アップロードする問題ファイル、コース名を選択して、問題を追加してください。
追加した問題の内容を更新するには、問題編集画面で別の問題ファイルを指定してアップロードし、上書きしてください。
モジュール管理者には、問題一覧に「編集」「削除」ボタンが表示されます。
トップページ
Top Page
コース一覧
モジュールのトップページでは、コース名と簡単な内容説明、収録問題数、各自が終了した問題数などを含むコース一覧が表示されます。管理者の場合は、少なくとも一名以上が完了した問題数が表示されます。

各コース名は、そのコースの問題一覧へのリンクが張られており、一覧される問題の問題名をクリックすれば、問題を開始できるようになっています。

User Portfolio
学習履歴
ゲストユーザでなければ、コース名一覧表の右上に「学習履歴」へのリンクが表示されます。ユーザは自分が取り組んだ問題の結果をすべて閲覧できるようになっており、管理者ならばすべてのユーザの学習履歴を閲覧できるようになっています。一覧される問題名は問題へ直接リンクされており、すぐに問題を表示できるようになっています。

学習履歴では、一覧するコース名を指定でき、表の各列先頭のタイトルをクリックすればその項目で並べ替えを行えます。

管理者は、各記録の右に表示されている削除ボタンを押すことによって、その記録を削除することができます。

Admin Portfolio
問題一覧
問題一覧では、問題名、問題ID、登録日時、完了者数、ユーザとサイト全体の最高得点が一覧されます。もしそのユーザが一度でもその問題を完了していれば、操作の欄に「結果」というリンクが表示され、そのユーザのその問題についての全結果を表示することができます。

User Quiz List
この画面にある「学習履歴」ボタンは、表示されているコースだけに関する学習履歴を簡単に表示できるようになっています。

管理者には、各問題に対して「編集」と「削除」というボタンも表示されます。これにより、問題の内容を差し替えたり、問題自体とそのすべての結果を削除できるようになっています。「結果」ボタンは、管理者に対してはその問題に対するすべてのユーザのすべての記録を表示します。

Admin Quiz List
結果一覧
Results View
結果一覧には、基本的な内容のみの簡易表示と、ユーザのホスト名やIPアドレスなどを含む詳細表示という二つの表示モードがあります。一覧の順序は、表の各列先頭のタイトルをクリックして切り替えられます。

管理者の場合、不要な記録をデータベースから削除できるように、各項目に「削除」ボタンが用意されています。

問題の解答方法Taking a quiz
問題を開始する
ユーザは、問題一覧や結果一覧などから、問題名をクリックすることによって問題を開始することができます。ログインをしていないユーザ（ゲスト）の場合は、問題開始前に解答結果は記録もメール送信もされないという確認のダイヤログが表示されます。

ID入力
ID Prompt
次に、ユーザにはID（あるいは問題を作成したときの設定により氏名などと表示される場合もある）を入力するプロンプトが表示されます。実際にはサイトでのユーザ名は自動で記録されていますから、これは余分な情報ともいえますが、場合によっては必要に応じて学生番号などを入力させるのに使うことができます。このプロンプトで何も入力しないと問題を開始することができません。

ヒントボタン
Sample Quiz
問題ファイル作成時にヒント機能がオンになっていると、ヒントボタンが表示されます。このボタンをクリックすると、穴埋め問題の場合は次の一文字を与えてくれます。ヒントボタンを利用すると、総合得点から減点されます。

答え合わせ
解答中、ユーザはいつでも答え合わせをすることができますが、答え合わせの回数が多ければその分減点の対象となります。つまり、最初の答え合わせで全問正解すると、100％というスコアが出るようになっています。答え合わせの結果、合っている部分は太字で表示されるなど明示され、間違っている部分は訂正できるよう改めて解答欄として表示されます。問題の記録は、すべて正答するまでは送信されません。

結果の表示と送信
Feedback
問題が終了すると、新たにウィンドウが開き、そこにスコアなどの情報が表示されます。このとき、ゲスト以外であれば、同じ情報がデータベースに記録されるとともに、ユーザ本人と問題作成者にメールで送信されます。

そのウィンドウのいちばん下には、結果のウィンドウと問題のウィンドウを同時に閉じるための「閉じる」ボタンが用意してあります。

【重要】WWWブラウザで、ポップアップウィンドウを開くことができるように設定しておいてください。そうしておかないと、結果が表示されないばかりか、記録も送信も正常に行えなくなってしまいます。

解答欄の移動
穴埋めタイプの問題などで解答欄を移動する際、マウスを使わなくても、キーボードのtabキーで次の解答欄にカーソルを移動することができます。同様に、シフトキーを押しながらtabキーを押せば、一つ前の解答欄に戻ることができます。この際、既に入力されている文字があればそれはすべて選択状態になっていますので、そのまま何か入力すれば前の答えに置き換わります。代わりに、まずカーソル移動の右矢印キーを押してからタイプすれば、既存の解答に付け加えることができます。

問題の追加方法
問題ファイルの準備
Hot Potatoesの最新版を使って問題ファイルを作成してください。詳しくは、Hot Potatoesのホームページで公開されている資料（http://web.uvic.ca/hrd/hotpot/tutorials6.htm）を参考にしてください。

問題作成時に結果報告用のCGIオプションがオンになっていなくても、このモジュールで問題ファイルがアップロードされる際、CGIでの送信がされるように修正をするようになっています。しかし、この修正は微妙な文字列検索に基づいており完璧とはいえませんので、問題作成時にCGIオプションをオンにしておくことをお薦めします。この際、CGIの各種設定は何もしなくても結構です。

対応する問題ファイル形式
XoopsHPは、Hot Potatoes ver. 6が用意しているすべての問題形式に対応しています（JCloze, JCross, JMix, JMatch, JQuiz）。ドラッグドロップタイプの問題にも対応しています。

古いバージョンのHot Potatoesで作成された問題ファイルは生成されるソースコードの構成が若干異なるため、このモジュールが試みるCGIオプションのに関する自動修正は動作保証できません。作者が調べてみた範囲では、問題開始時のID入力要求が二度繰り返されるという現象が確認できていますが、結果の表示や送信には影響は出ませんでした。

画像や音声などの利用
このモジュールでは、アップロードされる問題ファイルからテキスト形式で書かれたソース部分のみを抽出してデータベースに保存するようになっています。画像や音声データを含む問題を作成するには、まずはそれらのデータをWWW上のどこかに準備しておく必要があります。そして、問題作成時にそれらのデータを取り込むには、http://で始まる完全なURLによって参照するようにしてください。同様に、問題にリンクを埋め込む場合にも完全なURLを用いてください。

Add Quiz
問題ファイルのアップロード
問題管理画面で、まずは問題名を記入し、コース名を選択してから、アップロードする問題ファイルを、ご自分のコンピュータのハードディスクに保存してある問題ファイルから選び指定してください。その後、「問題を追加」ボタンを押してください。成功すれば、追加した問題が問題管理画面の一覧や、ユーザ向けの問題一覧に表示されているはずです。

問題の更新
Preferences
問題の「編集」リンクがあるところから問題の編集モードに入ってください。問題名とコースは直接編集あるいは選択し直すことができますが、問題な異様は確認のために表示はされていても、書き込みはできないようになっています。問題内容を置き換えるには、別の問題ファイルを指定してアップロードし直してください。

一般設定
Preferences
一般設定を行えるのは、サイト管理者のみです。モジュール管理者（モジュールについてのみ管理権限を与えられたグループに属するユーザ）は一般設定の変更はできません。

一般設定の最初の項目は、Hot Potatoesのライセンスの有無です。もしHot Potatoesを利用する正当なライセンスを持っている場合は、ここを「はい」に設定してください。それにより、問題をすべてのユーザに公開しないことも許可されるようになります。言い換えれば、Hot Potatoesの利用条件に抵触しないよう、ライセンス設定が「いいえ」の場合は、システムの設定でXoopsHPモジュールに対するゲストグループのアクセスをオフにしたとしても、自動的にゲストグループはXoopsHPで扱う問題を閲覧できるようになります。

その他、モジュールのトップページのタイトルや説明を変更できるようになっています。

その他
Module Admin
メニュー名を変更する
サイト管理者でログインし（モジュール管理者ではできません）、「管理者メニュー」に行きます。そして、「システム管理」メニューから「モジュール管理」を選択すると、インストールされたモジュールの一覧が表示されます。このリストで、タイトルを好みに変更してください。このタイトルはメインメニューに表示されます。

問題中のリンク切れ
モジュールはアップロードされる問題ファイルのソースを走査し、必要な修正を加えるようになっていますが、それも完全ではありませんので、修正できない部分もあります。その一例が、「目次へ」や「次の問題へ」というボタンなど、問題作成時に埋め込まれた案内のためのリンクです。これらはXOOPS上で表示したときにはリンクが切れてしまいます。

これを避けるための最良の策は、問題作成時にこのようなリンクを自動で埋め込む設定を切ることです。詳しくはHot Potatoesのマニュアルや関連資料を参照してください。

ブラウザのクッキー
このモジュールだけでなく、XOOPSでは全般的にページをまたいで情報を受け渡しするためにクッキー情報を活用します。ブラウザがクッキーを受け入れないようになっていると、機能の大部分は正常に動作しなくなってしまいます。

セキュリティーソフト
NortonやMcAfeeなどのセキュリティーソフトを使用していると、XOOPS利用時に問題が発生することは既知の問題です。不具合が直らないような場合には、ファイヤーウォールやウィルス対策ソフトがインストールされて動作していないか確認してみてください。それらの機能を一時的に切っても問題が引き続き発生するかどうか確かめてみてください。

教師向け利用のコツ
「教師向け利用のコツ」という文書には、教師が授業でXOOPSやXoopsHPを利用するためのコツが書かれています。