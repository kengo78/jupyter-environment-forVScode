# jupyter-environment-forVScode

## for m1 mac
1. Python3をインストールする
   python3のversion確認方法
   ```
   python3 --version
   ```
   Homebrewを用いてinstall
   ```
   brew install python@3.9
   ```
2. VSCodeでPython3のパスの設定
   VSCodeがデフォルトで用いるVSCodeの設定を開いて、python.defaultInterpreterPathで指定する。

3. VSCodeにPythonとJupyter拡張機能をinstall  
   [Python拡張機能](https://marketplace.visualstudio.com/items?itemName=ms-python.python)  
   [Jupyter拡張機能](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

4. VSCodeのターミナルでPython仮想環境を作る
    仮想環境の作成
   ```
   python3 -m venv env
   ```
   仮想環境のactivate
   ```
   source env/bin/activate
   ```
5. Python3のJupyterモジュールを仮想環境にinstall
    ```
    python --version
    pip --version
    ```
    次のようにしてjupyterモジュールをinstallする
    ```
    pip install jupyter
    ```
6. Jupyter NotebookをVSCodeで開く
    コマンドパレットを開く(表示⇨コマンドパレットor Shift+⌘+P)
    Create New Jupyter Notebookを入力してリターンキー
    あとはその画面で、Jupyter Notebookを利用する。ログは、VSCodeのいつもの方法でファイル保存できる
    