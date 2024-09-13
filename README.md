# cwh-seaborn

CoursewareHubのカスタムイメージとして[seaborn](https://github.com/mwaskom/seaborn)を利用するための[repo2docker](https://github.com/jupyterhub/repo2docker)の構成ファイル。

CoursewareHubでデフォルトのsingle-userサーバとして利用するコンテナイメージ [niicloudoperation/notebook](https://hub.docker.com/r/niicloudoperation/notebook/) にもseabornはインストールされているが、このレポジトリから構築したカスタムイメージはseabornを利用するのに必要なもののみで構成されるめイメージサイズを小さくすることができる。


