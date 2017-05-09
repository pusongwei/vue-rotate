vue单文件组件 图片翻转效果  
可以设置每行每列各n个盒子（每个盒子为一个翻转效果）  
随着盒子数量增多性能下降  
![Image text](https://github.com/pusongwei/vue-rotate/blob/master/img/1.gif)
line:10,                                  //每行盒子个数  
list:5,                                   //每列盒子个数  
num:50,                                   //总盒子数  
bgImg:['bg1','bg2','bg3','bg4','bg5'],    //动态更改背景图的class  
className:[],                             //当前class  
index:0                                   //当前显示背景图的下标  
在父组件中引用：  

import bgImgRotate from '@/components/base/bgimg.vue'  
  
  
components: {  
  bgImgRotate  
}  
在标签中直接写  
<bgImgRotate></bgImgRotate>  
OK！
