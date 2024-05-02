## SPFとDKIMとDMARC

```
* SPFは、送信者がドメインの送信を許可されているSMTPサーバーのIPを公開 
www.example.comとして送信可能なIPおよびSMTPサーバーのIPを公開して、許可したIPのみからメール送信可能

* DKIMは、受信者が送信元のドメインが電子メールの送信者であることを確認
skakimoto@cuon.co.jpから届いたメールであることを検証する

* DRMARCは、SPFとDKIMがFAILした場合にどういう操作をするのかを設定する
```
