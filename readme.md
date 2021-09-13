# CHECK_OPTION_KAREL

FANUC ロボットのオプション機能の有無によってロボットを制御したい場合、当 KAREL プログラムのルーチンが有用です  
以下のルーチンを用いることでオプションに応じた制御を行うことができます

## 使い方

### ROUTINE ChkOption(option_name: STRING): BOOLEAN

検索したいオプション名を引数として与えて下さい  
存在する場合には TRUE を、存在しない場合には FALSE を返します

## 更新履歴

### Version 1.0

作成

## License

Released under the Apache 2.0 License.
