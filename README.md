# JavaReturnWithMethod
メソッドでリターンがある場合

## 処理
multiメソッドを作って計算した値をリターンで戻す。

## コード
```
public class Return {

	public static void main(String[] args) {
		int num = multi(7, 8);
		System.out.println(num);

	}


	public static int multi(int x, int y) {
		return x * y;

	}
}
```

## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 統合開発環境(IDE) | Eclipse 4.7.0 Oxygen |
| 開発言語 | Java8 |
