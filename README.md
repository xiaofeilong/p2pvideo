# p2pvideo
使用百度播放器做的带有p2p功能的vod点播。可以直接加入到Eclipse中进行编译。
需要设置百度播放器的AK，SK。

1、初始化p2p模块
VbyteP2PModule.create
2、开始播放时，加载video视频
vodController.load(videoURL,"UHD", 0)
3、结束播放时，卸载
VodController.getInstance().unload();
