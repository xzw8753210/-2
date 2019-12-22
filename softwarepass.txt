getpage: function () {
    wx.navigateTo({
      url: '../index/index'
    })
  },

<view class="cao">
  <view class="hua">护花使者</view>
  <view class="shu">
    <view>
      <text>担任护花使者天数：</text ><text class="tu">{{chong}}</text>
    </view>
      <button bindtap="mu" class="mu">变身</button>
    <button  bindtap='getpage' class="guo" >呵护</button>
    <button  bindtap='getpage2' class="ye">歌唱</button>
  </view>
</view>


.hua{
  font-family: cursive;
  font-style: oblique;
  font-size: 40px;
  font-weight: bold;
  color: greenyellow;
  text-align: center;
  margin:0px
}
.shu{
  font-family: 'Courier New', Courier, monospace;
  text-align: left;
  margin: 20px;
  color: whitesmoke
}
.cao{
  background-image: url(http://m.qpic.cn/psb?/V12N55RO27Yde4/gUM8ZBg5e0KeS0cBTalde5GM1KVFvq9sjwAYxDu8Pw8!/b/dMoAAAAAAAAA&bo=DAMtAgAAAAARFwA!&rf=viewer_4);
  width: 750rpx;
  height: 600px;
  background-size: 100% 100%;
  background-repeat: no-repeat;
  /*background-position-x: 200% */

}
.mu{
  margin: 50px
}
.guo{
   margin: 50px
}
.ye{
 margin: 50px}
.tu{
  font-size: 25px
}
