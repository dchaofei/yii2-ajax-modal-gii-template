# yii2-ajax-modal-gii-template

## 使用方法
- 安装
```bash
composer require dchaofei/yii2-ajaxmodal:dev-master
```
- 配置
```php
'modules' => [
        'gii' => [
            'class' => 'yii\gii\Module',
            'generators' => [
                'crud' => [
                    'class' => 'yii\gii\generators\crud\Generator',
                    'templates' => [
                        'ajax-modal' => '@vendor/dchaofei/yii2-ajaxmodal/gii-template/curd/default',
                    ]
                ]
            ],
        ]
    ],
```
- 之后使用 gii 生成 curd,模板选择 ajax-modal
![](https://raw.githubusercontent.com/dchaofei/images/master/yii2-ajaxmodal/operate.png)

## 示例图片
![](https://raw.githubusercontent.com/dchaofei/images/master/yii2-ajaxmodal/example.gif)
