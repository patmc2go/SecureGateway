---

copyright:
  years: 2015, 2017
lastupdated: "2017-04-10"

---

# ゲートウェイの追加

ゲートウェイは、特定のネットワークまたは環境を識別するための手段であると考えることができます。これは、Secure Gateway クライアントが Secure Gateway サーバーとの接続を確立するために使用するものであり、複数のリソース定義、つまり宛先を含むことができます。

![Secure Gateway ダッシュボード](./images/newDashboard.png?raw=true "Secure Gateway ダッシュボード")

Secure Gateway ダッシュボードで「ゲートウェイの追加」ボタンをクリックして、「ゲートウェイの追加」パネルを開きます。

![ゲートウェイの追加](./images/addGateway.png?raw=true "ゲートウェイの追加")

このパネルで入力が必須なのはゲートウェイ名のみです。デフォルトでは、「`セキュリティー・トークンを必要とする`」および「`トークン有効期限`」の両方とも選択されます。

クライアントを接続するためにセキュリティー・トークンが必要であると設定すると、Secure Gateway クライアントを開始するたびにゲートウェイ ID とセキュリティー・トークンの両方を指定することが必要になります。「`セキュリティー・トークンを必要`」ボックスのチェック・マークを外すと、クライアントが接続するために指定する必要があるのはゲートウェイ ID のみになります。

セキュリティー・トークンのデフォルトの有効期限は、作成されてから 90 日です。期限日付を変更するには、「`トークン有効期限`」ボックスにチェック・マークを付けたままでテキスト・フィールドを編集して、トークンの有効期限が切れるまでの日数 (最小 1、最大 365) を指定します。期限切れにならないトークンを作成するには、「`トークン有効期限`」ボックスのチェック・マークを外します。  

ゲートウェイの作成を完了するには、「ゲートウェイの追加」をクリックします。ゲートウェイが作成されると、ページは自動的に新規ゲートウェイにナビゲートします。

![新規ゲートウェイ](./images/newGateway.png?raw=true "新規ゲートウェイ")

これでゲートウェイが新しく作成されたので、[最初のクライアントを接続](./securegateway_client.html)できます。