# サンプル GFM ドキュメント

このリポジトリは [HideTake761/LeetCode](^1^) を参考にしています。  
詳しくは [GitHub Docs](https://docs.github.com/) をチェックしてね！

## Pythonの例

以下は、リストの中の最大値を求めるシンプルなPythonコードです：

```python
def find_max(numbers):
    if not numbers:
        return None
    return max(numbers)

print(find_max([3, 7, 2, 9, 5]))
