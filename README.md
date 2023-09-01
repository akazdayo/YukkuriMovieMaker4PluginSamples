# ゆっくりMovieMaker4 プラグインサンプル集
## プロジェクトの作成方法
.NET7用のクラスライブラリプロジェクトを作成してください。  
### プロジェクトの設定
プロジェクトの作成後、プロジェクトファイルの`<TargetFramework>`を`net7.0-windows10.0.19041.0`に変更し、その下に`<UseWPF>true</UseWPF>`を追加してください。
```xml
<PropertyGroup>
    <TargetFramework>net7.0-windows10.0.19041.0</TargetFramework>
    <UseWPF>true</UseWPF>

    ...省略...

</PropertyGroup>
```
### 参照の追加
1. ソリューションエクスプローラーから`依存関係`を右クリックし、`プロジェクト参照の追加(R)`をクリックします。
1. 参照マネージャーウィンドウ下部の`参照(B)`ボタンをクリックします。
1. YMM4をインストールしているフォルダ内にある`YukkuriMovieMaker.Plugin.dll`と`YukkuriMovieMaker.Controls.dll`を選択し、`OK`ボタンをクリックします。
1. `OK`ボタンをクリックし、参照マネージャーを閉じます。
1. プラグインの実装中に`CS0012: 型'T' は、参照されていないアセンブリに定義されています。アセンブリ 'アセンブリ名, Version=x.x.x.x, Culture=xxx, PublicKeyToken=xxx' に参照を追加する必要があります。`とエラーが表示された場合、必要に応じてYMM4フォルダ内にある`アセンブリ名.dll`を参照に追加してください。
## プラグインの読み込み
ビルド後、`YMM4フォルダ\user\plugin\`フォルダ内に`プラグイン名フォルダ`を作成し、`プラグイン名.dll`を保存してください。  
YMM4フォルダ内に存在しないdllを読み込んでいる場合、そのdllも一緒にコピーしてください。  

プラグインが正常に読み込まれた場合、YMM4の`設定`→`プラグイン`→`プラグイン一覧`にプラグイン名が表示されます。

## サンプル一覧
### 音声読み込みプラグイン
- [SampleAusioSourcePlugin](./SampleSourcePlugin/README.md)

### 映像読み込みプラグイン
- [SampleVideoSourcePlugin](./SampleVideoSourcePlugin/README.md)

### 画像読み込みプラグイン
- [SampleWICImageSourcePlugin](./SampleWICImageSourcePlugin/README.md)

### 立ち絵読み込みプラグイン
- [SampleTachiePlugin](./SampleTachiePlugin/README.md)

### 動画書き出しプラグイン
- [SampleVideoWriterPlugin](./SampleVideoWriterPlugin/README.md)

### 音声エフェクト
- [SampleAudioEffect](./SampleAudioEffect/README.md)

### 映像エフェクト
- [SampleVideoEffects](./SampleVideoEffects/README.md)

### 音声合成プラグイン
- [SampleSAPI5VoicePlugin](./SampleSAPI5VoicePlugin/README.md)

### AIテキスト補完プラグイン
- [SampleTextCompletionPlugin](./SampleTextCompletionPlugin/README.md)

### 多言語化プラグイン
- [SampleLocalizePlugin](./SampleLocalizePlugin/README.md)

