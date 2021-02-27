---
layout: app
title: "desktopgame.github.io"
permalink: /NextSynth
app_name: NextSynth
app_desc: NextSynthはAndroidで動作するMIDIシーケンサーです。
app_image: /assets/images/next_synth_logo.png
app_image_alt: NextSynthアプリアイコン
---
# 概要
NextSynthはUSB経由で接続されたMIDI機器にMIDIメッセージを送信できます。  
本アプリ本体はDAWソフトのようなピアノロール画面を備えており、指定されたノートをMIDIメッセージとして送信できます。
![編集画面](assets/images/next_synth_edit.png)


# 使い方
ノートを打ち込むためには、プロジェクトを作成する必要があります。  
プロジェクトはNextSynthの開始画面で作成/削除することができます。
![スタート画面](assets/images/next_synth_start.png)

名前をつけてプロジェクトを作成します。
![プロジェクト名入力画面](assets/images/next_synth_input_title.png)

プロジェクトは以下のようにタイル形式で表示されます。  
このタイルをダブルタップすることで編集画面へ遷移します。
![プロジェクト一覧画面](assets/images/next_synth_projects.png)

編集画面です。  
ダブルタップでノートを作成することができ、ノートをタップすると選択状態になります。  
選択状態になったノートはまとめてドラッグ、リサイズが可能です。
![編集画面](assets/images/next_synth_edit.png)


ノートを作成した様子です。  
ノートが存在する状態で再生ボタンを押すと、接続中のMIDI機器にMIDIメッセージが送信されます。
![編集画面2](assets/images/next_synth_edit2.png)

複数のトラックを編集している場合は、他のトラックを別の色で表示します。
![編集画面3](assets/images/next_synth_onionskin.png)

MIDIメッセージを送信するためには、事前にMIDI機器を接続状態にしておく必要があります。

![編集画面4](assets/images/next_synth_settings.png)

また、トラックごとに送信対象のMIDI機器を選択可能です。

![編集画面5](assets/images/next_synth_track.png)

# ソースコード
NextSynthのソースコードは以下に置かれています。  
[NextSynth](https://github.com/desktopgame/next_synth)