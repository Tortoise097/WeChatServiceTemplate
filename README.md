# WeChatServiceTemplate
Wellcome!
This is the course project for 2021-Software-Engineering-PKU

我说一下我的想法：
这个app每人使用的时候应该是提供以下信息（发起拼团请求）：
1、要拼什么牌子的奶茶
2、自己的位置（几号楼 or 教学楼）
3、拼团目标（凑包邮还是凑满减，目标不同拼团策略不同）
4、自己想买多少钱（向上浮动两块钱，因为如果要凑单可能会加个小料之类的）

然后app会自动匹配符合条件的人，距离近的优先，让 这些人开始拼团

拼团会选出一个团长（实际去美团下单付钱的人），剩下几个人再付钱给团长

然后主界面应该是以列表形式显示 在哪里，有多少人在拼团，因为现在还是考虑用手机端操作，不知道手机端用web效果怎么样，所以可能会优先选微信小程序开发（而且微信小程序方便付款……比如拼团呀那个我不知道你用过没有，是通过团长上传收款码，团员扫码进行付款然后上传付款截图凭证这样的方法来的）

感觉可能不会搞成活点地图那个样子，虽然那样子比较好看，但是感觉实用性不强。因为点奶茶的地点是离散的，比如哪个宿舍楼、哪个教学楼之类的，如果用地图GPS，会具体到楼内，但是这个定位又是比较平面的，而且如果人多的话，显示成地图的时候，感觉会卡？如果只是文字显示的话感觉就没问题。

以上大概就想这么多。

try git 自动登录1