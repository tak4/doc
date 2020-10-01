# Chrome Extention


https://developer.chrome.com/extensions

## Sample
https://developer.chrome.com/extensions/samples


## Manifest File
https://developer.chrome.com/extensions/manifest


### コンテキストメニュー追加
Context Menus Sample
Context Menus Sample (with Event Page)

### コンテキストメニュー追加 テキスト選択時に表示
Global Google Search

```javascript
    chrome.contextMenus.create({
      id: locale.id,
      title: locale.title,
      type: 'normal',
      contexts: ['selection'],
    });
```


### 新しいタブを開く
Cookie API Test Extension


### ショートカットキー

Tab Flipper

### リンク先ダウンロード

Download Selected Links

