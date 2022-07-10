### Excalidraw

@excalidraw/excalidrawからforkしたパッケージです。

日本語の手書きフォント JKG-Mを適用しました。

### Installation

インストールは本家を参照下さい。
@excalidraw/excalidraw
=>
@shareupjp/excalidraw

#### 変更内容

- 文字入力欄に日本語手書き適用アイコン追加
- SVGエクスポートにJKG-M適用

#### 追記(2022-0422)
- ヘルプボタンをクリックすると、エラー(Can't find translation for helpDialog.toggleElementLock)
- locales/jp-JP.json(helpDialog->toggleElementLock)の定義を追加。

#### 追記(2022-0710)
- @excalidraw/excalidraw version 0.12.0 対応
- 上記2022-0422で追加したlocales/jp-JP.json(helpDialog->toggleElementLock)の定義を本家で対応したので、独自追加した分を削除しました。

