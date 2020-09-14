# web-accessibility

## 概要

「コーディングWebアクセシビリティ: WAI-ARIAで実現するマルチデバイス環境のWebアプリケーション」 の書評



## aria-label

```
<!-- aria-label のサンプル>
<button aria-label="戻る"></button>
```

## aria-checked

divタグを使ってcheckboxを再現する場合は、aria-checked属性を使用して、チェックされているかどうか示す。

```
<dit class="toggle" role="checkbox" aria-checked="false" tabindex="0">CHeck<div>
```

## aria-haspopup 
非表示のサブメニューを持つ要素のプロパティ

```
<li>
    <a href="#submenu" aria-haspopup="true" aria-controles="submenu">メインリンク</a>
    <ul id="submenu">
        <li><a href="/somewhere/">サブメニューリンク</a></li>
        <li><a href="/somewhere/else/">もう一つのリンク</a></li>
    </ul>
</li>
```