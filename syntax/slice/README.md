# slice

sliceでよく使うコマンドや躓きがちなポイントを説明します。
## sliceのコピー
Sliceは配列に対するポインタを含みます。
なので、`=`でコピーすると、同じポインタを参照します。
ポインタを共有したくない場合はcopyを使う必要があります。
## index out of range
lengthを超えて要素にアクセスしようとpanicします。

## 課題
今回の内容を理解する