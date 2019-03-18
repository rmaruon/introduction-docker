プロダクションへの導入方法


新規開発なら最初からDockerで開発していきましょう。  

既存のVMからの移行であればステップを踏んで行くのが良いでしょう。

1. ローカル環境のDocker化
    - まずはローカル環境での導入から行います
    - チームの開発環境をDockerで統一し、Dockerに慣れていくところから始めていきましょう
2. テスト/CIへの導入
    - 次にテスト/CI環境への導入を行います
    - また、CIを導入してないのであればDockerとの相性が良いのでこの機会に導入するのもありでしょう。
3. ステージングへの導入
    - 本番へいきなり導入する前にステージング環境でDockerの動作を確認しましょう
4. 本番への導入
    - 最後に本番環境への導入を行いましょう