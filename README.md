# wechat-mini-steps
小程序自定义步骤条组件（根据LinUI改写 https://doc.mini.talelin.com/component/view/steps.html ）

![demoGif](https://github.com/Jidahan/wechat-mini-steps/raw/main/image/demo.gif)


示例代码： [示例代码](https://github.com/Jidahan/wechat-mini-steps/blob/main/pages/buyHouseSteps/buyHouseSteps.wxml)

![demopng](https://github.com/Jidahan/wechat-mini-steps/raw/main/image/demoimg.png)
## l-steps 参数
|key|type[value]|description|
|:----|:---|:----------|
|`direction`|String`column'/'row`|'步骤条排列方向'（由于项目进度原因，本项目只做了column的适配）|
|`active-index`|String[number]|当前进度所在锚点|
|`dot`|Boolean|设置步骤条为点状步骤条|
|`color`|String|点状态下的颜色以及选中的阴影颜色|

## l-step 参数
|key|type[value]|description|
|:----|:---|:----------|
|`year`|String|进度条左侧关于 年 的字段|
|`month`|String|进度条左侧关于 月份 的字段|
|`title`|String|进度条左侧未执行的文字描述|
|`leftText`|String|步骤条上面左侧文字，例：日期。需开启custom|
|`rightText`|String|步骤条上面左侧文字，例：事件。需开启custom|
|`custom`|Boolean|是否开启自定义|