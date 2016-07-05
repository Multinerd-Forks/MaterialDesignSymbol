#### MaterialDesignSymbol ![CocoaPods Version](https://img.shields.io/cocoapods/v/MaterialDesignSymbol.svg?style=flat) ![Platform](https://img.shields.io/cocoapods/p/MaterialDesignSymbol.svg?style=flat) ![License](https://img.shields.io/cocoapods/l/MaterialDesignSymbol.svg?style=flat)
==============

<img src="https://s3.amazonaws.com/cocoacontrols_production/uploads/control_image/image/6377/_____.png" width="160px">

Icon font library for Swift. Currently supports GoogleMaterialDesignIcons

Googleのマテリアルデザインアイコンをシンボルフォントで呼び出せるライブラリです。詳細な使い方は[こちら](http://qiita.com/tichise/items/9fd290f1cc2af4796826)に記載してます。

#### Licence
font used in this project

Author of the font used in this  project: Google
Link: https://github.com/google/material-design-icons

Creative Commons Attribution 4.0 International (CC BY 4.0)

#### Related products

##### EntypoSymbol
Icon font library for Swift. Currently supports Entypo

https://github.com/tichise/EntypoSymbol


#### Examples

##### Image

```html
import MaterialDesignSymbol

var symbol:MaterialDesignSymbol = MaterialDesignSymbol(text:MaterialDesignIcon.list48px, size:25)
symbol.addAttribute(NSForegroundColorAttributeName, value: UIColor.redColor())
var iconImage:UIImage = symbol.imageWithSize(CGSizeMake(25, 25))
```

##### Text

```html
import MaterialDesignSymbol

titleLabel.font = MaterialDesignFont.fontOfSize(20)
titleLabel.text = MaterialDesignIcon.list48px
```

#### Installation (CocoaPods)
`pod MaterialDesignSymbol`
