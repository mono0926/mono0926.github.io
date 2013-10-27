---
layout: post
title: "Mobile Backend Starter for iOSを試してみた"
date: 2013-10-12 18:26
comments: true
categories: iOS google
---

先日iOS版のMobile Backend Starterがリリースされたので、調査。
まずは、[Mobile Backend Starter](https://developers.google.com/cloud/samples/mbs/)に行って、色々眺めてみる。

プッシュ通知の面倒を見てくれるのが目玉だと思うけど、それ以外にも色々できそう。

- Optional server-side coding
- Cloud Datastore
- Push Notifications 
- Event Driven Programming
- User authentication
	- Googleアカウントでの認証
- Per-object access 
- Built to scale
	- スケール対応だけど、GAEと同じプライスモデルで課金される
	
## Getting Started

とりあえずドキュメントのGetting Startedを試してみる。

### [Deploy the Backend](https://developers.google.com/cloud/samples/mbs/deploy_backend)

cloud.google.com(一時URLなのでリンク出来ない)に飛んで、"Try It Now"をクリック。
Projectが出来たら、"Mobile sample app"というリンクをクリック。
数分時間がかかるので、お酒に手を出してしまった（´-ω-｀）

Settingsで「Authentication / Authorization」をOpenにして、以下のyour-project-idを生成したProjectのものに置き換えると、定義されたAPI一覧に飛べる。
https://your-project-id.appspot.com/_ah/api/explorer 

これで、サーバー側の準備が整ったらしい。

### [Run the iOS Sample](https://developers.google.com/cloud/samples/mbs/ios/)

いきなりXcode4.6で作業するようにと書いてあったけど、多分関係ないのでXcode5で作業。


mbs.mono.com


https://your-project-id.appspot.com/admin/configure.jsp
https://boxwood-atom-366.appspot.com/admin/configure.jsp