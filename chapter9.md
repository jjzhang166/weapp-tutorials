#第九章 组件进阶

我们在之前的第七章介绍了小程序的组件，虽然小程序为开发者提供了一系列功能丰富的基础组件，但是还远远不太够，我们还需要对基础组件进行合理的组合，得到更加方便我们使用的组合组件。

小程序目前并不支持组件化,不能自定义组件，我们只能通过把封装的组件和样式放到单独的文件中，方便大家移植使用。

这一章我们就展示几种常见的组合组件。创建新的工程，在`app.wxss`中定义一些公共的样式:
```css

page {
  background-color: #f8f8f8;
  font-size: 32rpx;
}
.page__hd {
    padding: 80rpx;
}
.page__bd {
    padding-bottom: 80rpx;
}
.page__bd_spacing {
    padding-left: 30rpx;
    padding-right: 30rpx;
}

.page__ft{
    padding-bottom: 20rpx;
    text-align: center;
}

.page__title {
    text-align: left;
    font-size: 40rpx;
    font-weight: 400;
}

.page__desc {
    margin-top: 10rpx;
    color: #888888;
    text-align: left;
    font-size: 28rpx;
}
```
