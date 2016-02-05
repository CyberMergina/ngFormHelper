# ngFormHelper
CakePHP × AngularJS


## Example

```php:entry.ctp
    <?= $this->ngForm->input('tel', [
            'type' => 'text',
            'placeholder' => 'tel number',
            'div' => false,
            'maxlength' => 13,
        ],
        [
            'entity' => 'MUser.tel',
            'change' => 'isTel()'
        ]
    ); ?>
```

                                        
```html:index
<input name="data[MUser][tel]" placeholder="tel number" maxlength="13" ng-model="tel" ng-init="tel="0000-00-0000" type="text" value="0000-00-0000" id="MUserTel" required="required" class="ng-pristine ng-untouched ng-valid ng-valid-required ng-valid-maxlength" ng-change="isTel()">
```

## Other Option
Comming Soon...


