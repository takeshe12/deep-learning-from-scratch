# chapter1 Python入門

- pythonの基礎も学べるのでとても助かる。
  - 仕事でpythonコードは読むが書かないため勉強になる
- 以前python3はいれたようで、pip3でnumpyとmatplotlibを入れただけで環境構築は済んだ

## 文法

- 乗算が楽だと感じた

```python
>>> 3 ** 2
9
```

- Booleanは先頭大文字じゃないとダメなのね。

```
python
>>> type(true)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'true' is not defined
>>> type(True)
<class 'bool'>
```

## NumPy

- ブロードキャスト　行列計算が非常に楽にできる

## Matplotlib

- あまりに簡単で綺麗にplotできるので驚いた
- legend()は凡例
