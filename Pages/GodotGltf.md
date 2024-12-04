# BlenderからエクスポートしたglTFをGodotで使う

## Backface Cullingする

デフォルトだと両面を描画するので、レンダーエンジンをEEVEEに切り替えた上でマテリアルタブからBackface Cullingを有効化する。

## テクスチャ読み込み

読み込んだテクスチャはデフォルトでVRAM Compressed形式でインポートされるので表示が変な部分ができる可能性がある。
適宜Basis Universal等に変更する。
