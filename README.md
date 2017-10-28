# lightBox
基于jQuery的图片lightBox插件

# 注释
  data-role="lightbox" 绑定jq插件
	data-source="img/1.png" 放大图地址
	data-group="group-1" 所处图片集
	data-id="1" 图片唯一标识
	data-caption="图片1" 图片描述
  
# 用法
  var lightbox = new lightBox({
		    speed:300,// 运动速度
		    maxWidth:900,//显示最大宽度
		    maxHeight:600,//显示最大高度
		    maskOpacity:.6//遮罩层透明度
		  });
  
