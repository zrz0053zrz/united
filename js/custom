
	$(document).ready(function(){
		//导航变色
		if($(document).scrollTop()==0){
				navTop();
			} else {
				navScroll();
			}
		$(window).scroll(function(){
			if($(document).scrollTop()==0){
				navTop();
			} else {
				navScroll();
			}
		})

		//校友会信息导航切换
		$("div.hide-div").hide();
		$("li.sub").each(function(index){
			$(this).bind("click",function(){
				clear();
				$(this).attr("class","sub active-sub");
				$("div.sub-content[index=" + index + "]").show();
			})
		})
	})
	//scrollTop==0时
	function navTop(){
		$(".navbar").css("background-color","rgba(59,143,197,0.8)");
		$(".navbar-default .navbar-nav > .active > a").css("color","#fff");
		$(".navbar-default .navbar-nav > li > a").css("color","#fff");
		$(".navbar-brand img").css("color","#fff");
		$(".btn-default-nav").css("color","#ccc");
		$(".btn-default-nav").css("border-color","#aaa");
	}
	//其余情况导航
	function navScroll(){
		$(".navbar").css("background-color","rgba(255,255,255,0.8)");
		$(".navbar-default .navbar-nav > .active > a").css("color","#13415e");
		$(".navbar-default .navbar-nav > li > a").css("color","#13415e");
		$(".navbar-brand img").css("color","#13415e");
		$(".btn-default-nav").css("color","#326e93");
		$(".btn-default-nav").css("border-color","#4d87ac");
	}


	//校友会信息导航切换
	function clear(){
		$("li.sub").each(function(index){
			$(this).attr("class","sub");
			$("div.sub-content[index=" + index + "]").hide();
		})
	}
