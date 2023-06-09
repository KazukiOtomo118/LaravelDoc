# LaravelDoc

## よく使うやつ
```
php artisan make:controller XxxController
```

```
php artisan make:model XxxModel
```

```
php artisan make:migration create_xxxxs_table --create=xxxxs
```
構造を変更したい場合、--tableオプション を指定する。
```
php artisan make:migration add_column_to_tests_table --table=tests
```

```
php artisan migrate
```


## サーバ起動コマンド
```
$ php artisan serve
```

## テストの実行
```
$ ./vendor/bin/phpunit
```
