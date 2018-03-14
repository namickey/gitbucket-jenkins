# gitbucket-jenkins

## 参考サイト  
gitbucketとjenkinsをGitHubPullRequestBuilderを使って連携する  
https://qiita.com/hikaruworld@github/items/ae2cdc1904d7d35ef0b8  

## 環境
同一サーバ、同一ポートで、gitbucketとjenkinsが起動している状態。  
* 172.17.0.2:8080/gitbucket  
* 172.17.0.2:8080/jenkins  

## プラグインの管理
![連携設定1](img/1.png)

## jenkinsの設定
![連携設定2](img/2.png)

## ジョブ設定
![連携設定3](img/3.png)
![連携設定4](img/4.png)
![連携設定5](img/5.png)

## Gitbucket Service Hooks
![連携設定6](img/6.png)
