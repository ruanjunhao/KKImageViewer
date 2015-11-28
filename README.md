# KKImageViewer
带舒适切换动画效果的图片浏览器,快速集成到项目中,瞬间高大上有米有\n
 ![image](https://github.com/KKKiller/KKImageViewer/raw/all.gif)
一.快速加入单张可放大缩小图片,可选择原图缩放,也可以进行圆角处理,适用于头像等\n
1.头像\n
KKTapImageView *headImgView1 = [[KKTapImageView alloc]initWithFrame:CGRectMake(headImageFlag, 150, 100, 100)];
2.原图\n
KKTapImageView *headImgView1 = [[KKTapImageView alloc]initWithFrame:CGRectMake(140, 150, 100, 100)];
 ![image](https://github.com/KKKiller/KKImageViewer/raw/head.gif)

二.集成一组图片到任何位置,图片间可进行左右切换,图片放大缩小带动画\n
 ![image](https://github.com/KKKiller/KKImageViewer/raw/anyPositon.gif)

三.在tableView的每个cell中集成一组图片,切关闭时缩小至对应的cell\n
 ![image](https://github.com/KKKiller/KKImageViewer/raw/tableView.gif)