# wxc-steps

> MinUI 小程序组件 - 步骤条

## Install

``` bash
$ min install @minui/wxc-steps
```

## API

### Steps【props】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`steps`               | [说明]：步骤信息数组。组成对象参见steps数组项。<br>[类型]：`Array`<br>默认值：`[]` <br>|
|`current`             | [说明]：当前进行的步骤位置，从0开始。<br>[类型]：`Number`<br>[默认值]：`0` <br>   |

<br>
### steps 数组项

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`title`           | [说明]：步骤名称。<br>[类型]：`String`<br>默认值：`""` <br>|
|`desc`            | [说明]：步骤描述。<br>[类型]：`String`<br>[默认值]：`""` <br>   |

##  ChangeLog

#### v1.0.2（2017.11.02）

- update .npmignore

#### v1.0.1（2017.10.24）

- 初始版本
