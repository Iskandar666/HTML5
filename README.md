# 荣鸿农业
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<link rel="stylesheet" type="text/css" href="css/style.css">
<script src="js/jquery-3.2.1.min.js" type="text/javascript"></script>
<title>安徽荣鸿农业开发股份有限公司</title>
</head>

<body>
    <header class="header">
    	<div class="topsearch">
        	<form method="post" name="form1" id="form1" action="" class="top_search">
            	<input type="text" name="keyword" id="keyword" class="keyword">
                <input type="submit" name="submit1" id="submit1" value="" class="searchbtn">
            </form>
        </div>
        <div class="top">
        	<div class="logo">
            	<a href="index.html"><img src="images/logo.gif"></a>
            </div>
            <div class="nav">
            	<ul class="ul1">
                	<li class="li_1"><a href="index.html" class="a_1">首页</a></li>
                	<li class="li_1"><a href="index_gywm_1.html" class="a_1">关于我们</a></li>
                	<li class="li_1"><a href="index_xwzx.html" class="a_1">新闻中心</a></li>
                	<li class="li_1"><a class="a_1">项目介绍</a></li>
                	<li class="li_1"><a class="a_1">招标信息</a></li>
                	<li class="li_1"><a class="a_1">精品展示</a></li>
                	<li class="li_1"><a href="index_gyxx.html" class="a_1 po">供应信息<span class="span_1"></span></a></li>
                	<li class="li_1"><a class="a_1">培育技术</a></li>
                	<li class="li_1"><a href="index_rlzy.html" class="a_1">人力资源</a></li>
                	<li class="li_2"><a class="a_1">联系我们</a></li>
                </ul>
            </div>
        </div>
    </header>
    <div class="banner_1">
                <div class="wrapper"><!-- 最外层部分 -->
            <div class="banner"><!-- 轮播部分 -->
              <ul class="imgList"><!-- 图片部分 -->
                <li class="imgOn"><a href="#"><img src="images/banner.jpg"></a></li>
                <li><a href="#"><img src="images/banner2.jpg"></a></li>
                <li><a href="#"><img src="images/banner3.jpg"></a></li>      
              </ul>
              <div class="bg"></div> <!-- 图片底部背景层部分-->
              <ul class="indexList"><!-- 图片右下角序号部分 -->
                <li class="indexOn">1</li>
                <li>3</li>
                <li>4</li>
              </ul>
            </div>
          </div>
          <script type="text/javascript">
          var curIndex = 0; //当前index
             //  alert(imgLen);
             // 定时器自动变换2.5秒每次
          var autoChange = setInterval(function(){ 
            if(curIndex < $(".imgList li").length-1){ 
              curIndex ++; 
            }else{ 
              curIndex = 0;
            }
            //调用变换处理函数
            changeTo(curIndex); 
          },2500);
         
          $(".indexList").find("li").each(function(item){ 
            $(this).hover(function(){ 
              clearInterval(autoChange);
              changeTo(item);
              curIndex = item;
            },function(){ 
              autoChange = setInterval(function(){ 
                if(curIndex < $(".imgList li").length-1){ 
                  curIndex ++; 
                }else{ 
                  curIndex = 0;
                }
                //调用变换处理函数
                changeTo(curIndex); 
              },2500);
            });
          });
          function changeTo(num){ 
            $(".imgList").find("li").removeClass("imgOn").hide().eq(num).fadeIn().addClass("imgOn");
            $(".infoList").find("li").removeClass("infoOn").eq(num).addClass("infoOn");
            $(".indexList").find("li").removeClass("indexOn").eq(num).addClass("indexOn");
          }
          </script>
    </div>
    <div class="i_jplist">
    	<div class="img_cont">
        	<div class="img_1">
                <a class="a_2"><img src="images/hds.png"></a>
                <span class="span_2">红豆杉</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/gh.png"></a>
                <span class="span_2">桂花</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/xyzn.png"></a>
                <span class="span_2">小叶桢楠</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/yh.png"></a>
                <span class="span_2">樱花</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/zw.png"></a>
                <span class="span_2">紫薇</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/hyl.png"></a>
                <span class="span_2">红叶李</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/cl.png"></a>
                <span class="span_2">垂柳</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/hh.png"></a>
                <span class="span_2">合欢</span>
            </div>
        	<div class="img_2">
                <a class="a_2"><img src="images/ls.png"></a>
                <span class="span_2">栾树</span>
                
            </div><div class="img_1">
                <a class="a_2"><img src="images/gk.png"></a>
                <span class="span_2">国愧</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/wj.png"></a>
                <span class="span_2">乌桕</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/whz.png"></a>
                <span class="span_2">无患子</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/twqm.png"></a>
                <span class="span_2">台湾旗木</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/ggnz.png"></a>
                <span class="span_2">高杆女贞</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/hysn.png"></a>
                <span class="span_2">红叶石楠</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/xz.png"></a>
                <span class="span_2">香樟</span>
            </div>
        	<div class="img_1">
                <a class="a_2"><img src="images/gyl.png"></a>
                <span class="span_2">广玉兰</span>
            </div>
        	<div class="img_3">
                <a class="a_3"><img src="images/gd.png"></a>
            </div>
        </div>
    </div>
    <div class="main">
    	<div class="mainbox">
        	<div class="mbox fl">
            	<h2 class="h2">
                	关于我们
                	<span class="span_3">/About Us</span>
                    <a href="index_gywm_1.html" class="a_4">+more</a>
                </h2>
                <div class="minfo">
                	<p>安徽荣鸿农业开发股份有限公司在安徽省全椒县石沛镇投资了大型现代化农业示范产业园区——安徽荣鸿农业科技示范园，作为园区管理机构，安徽荣鸿农业开发股份有限公司（注册资......<a href="index_gywm_1.html" class="a_5">【查看更多】</a></p>
                </div>
            </div>
        	<div class="mbox1 fl">
            	<h2 class="h2" style="color:#F00;">
                	招标信息
                	<span class="span_3">/Tender</span>
                    <a class="a_4">+more</a>
                </h2>
                <div class="minfo">
                	<ul class="ul_1">
                    	<li class="li_3"><a>安徽荣鸿农业科技示范园园区苗木养护管...</a><span class="fl_rt">7-19</span></li>
                    	<li class="li_3"><a>安徽荣鸿农业开发股份有限公司第二期苗...</a><span class="fl_rt">11-19</span></li>
                    </ul>
                </div>
            </div>
        	<div class="mbox2 fl">
            	<h2 class="h2">
                	新闻中心
                	<span class="span_3">/News</span>
                    <a href="index_xwzx.html" class="a_14">+more</a>
                </h2>
                <div class="mpic">
                	<img src="images/xw.jpg">
                </div>
                <ul class="minfo1">
                	<li class="li_4"><span class="span_4">11.13</span><a>滁州市张祥安市长莅临荣鸿农业示范园视察</a></li>
                	<li class="li_4"><span class="span_4">5.8</span><a>农业部发布50大政策措施推动农村改革</a></li>
                	<li class="li_4"><span class="span_4">3.27</span><a>我校首个人文社科领域专家工作站建立</a></li>
                	<li class="li_4"><span class="span_4">3.27</span><a>南农大与安徽荣鸿农业签订校企合作协议</a></li>
                </ul>
            </div>
        </div>
        <div class="kb"></div>
        <div class="partner">
            <h2>友情链接</h2>
            <div class="scrolllist">
                    <ul class="ul_2">
                        <li class="li_5"><a href="http://www.lknet.ac.cn/" target="_black"><img src="images/t1.jpg"></a></li>
                        <li class="li_5"><a href="http://www.agri.cn/" target="_black"><img src="images/t2.jpg"></a></li>
                        <li class="li_5"><a href="http://www.wexiao.cn/" target="_black"><img src="images/t3.jpg"></a></li>
                    </ul>
            </div>
            <div class="i_tell">
                服务热线 | 
                <span>18055169883</span>
            </div>
        </div>
        <div class="kb_1"></div>
    </div>
    <div class="footer">
    	<div class="footer_top">
        	<div class="foot_top_left">
            	<a class="a_6">供应信息</a>
            	<a>精品展示</a>
            	<a>关于我们</a>
            	<a>联系方式</a>
            	<a>网站地图</a>
            </div>
            <div class="foot_top_right"><a>关注我们</a></div>
        </div>
        <div class="foot">
			Copyright 2013 安徽荣鸿农业开发股份有限公司  皖ICP备14006290号  技术支持：
            <a>微笑互联</a><br>
            <a>荣鸿.com</a>
            <a>荣鸿农业.com</a><br>
            <a class="a_7"><img src="images/kexin1.png"></a>
        </div>
    </div>
    <div class="toolbar">
    	<a class="a_8"></a>
    	<a class="a_9"></a>
    	<a class="a_10"><img src="images/wxm_03.gif" class="img_4"></a>
    </div>
</body>
</html>
