jQuery(document).ready(function($){
	var h = $(window).height();
	if(h > 1100){
		h = h - 50;
		$('.main1, .main2, .main3, .main4').css('min-height', h+'px');
	}
	step1();
	setTimeout(function(){
		$('#main-download').animate({opacity:"1"}, 500);
		$('.pp_logo').animate({opacity:"1"}, 500);
		setTimeout(function(){
			$('#tip-list').animate({opacity:"1"}, 500);
		}, 1000);
		$('#step_nav').find('li').eq(0).fadeIn(300);
		$('#step_nav').find('li').eq(1).fadeIn(800);
		$('#step_nav').find('li').eq(2).fadeIn(1300);
		$('#step_nav').find('li').eq(3).fadeIn(1800);
		setTimeout(function(){
			$('#click_tip').animate({opacity:"1"}, 1000);
			setTimeout(function(){
				$('#click_tip').animate({opacity:"0"}, 1000);
			}, 4500);
		}, 1000);
	}, 1000);
	var index_now = 0;
	$('#arrow-down').mouseover(function(){
		$('.more_version').show();
        $('.more_version').animate({right:"148px"}, 1000);
    });
    $('.more_version').mouseleave(function(){
        $('.more_version').css({right:"128px"});
     	$('.more_version').hide();
    });
	$('#navbar-toggle').click(function(){
		$('#px-nav-list').toggle();
	});
	$('#step_nav').find('li').click(function(){
		window.index = $(this).index();
		if(window.index != 0){
			$('#click_tip').animate({opacity:"0"}, 500);
		}
		if(window.index == 0){
			if(index_now != 0){
				$("body,html").css({scrollTop:0});
				index_now = window.index;
				$('.main-base').hide();
				step1();
			}
		}else if(window.index == 1){
			if(index_now != 1){
				$("body,html").css({scrollTop:0});
				index_now = window.index;
				$('.main-base').hide();
				step2();
			}
		}else if(window.index == 2){
			if(index_now != 2){
				$("body,html").css({scrollTop:0});
				index_now = window.index;
				$('.main-base').hide();
				step3();
			}
		}else if(window.index == 3){
			if(index_now != 3){
				$("body,html").css({scrollTop:0});
				index_now = window.index;
				$('.main-base').hide();
				step4();
			}
		}
		$('#step_nav').find('li').removeClass('active');
		$(this).addClass('active');
	});
});

function step2_2(index){
	window.index = index;
	$("body,html").css({scrollTop:0});
	$('.main-base').hide();
	step2();
}

function step1(){
	$('.main1').show();
	$('#menu').show();
	$('#menu').animate({width:"850px"}, 800);
	setTimeout(function(){
		$('.weibo, .twitter').fadeIn();
	}, 800);
	setTimeout(function(){
		$('#menu').find('a').animate({opacity:"1"});
	}, 500);
	setTimeout(function(){
		$('#p1_4').animate({opacity:"0.8"}, 300);
		setTimeout(function(){
			$('#p1_5').animate({opacity:"0.8"}, 800);
			setTimeout(function(){
				$('#p1_6').animate({opacity:"0.8"}, 300);
			}, 300);
			setTimeout(function(){
				$('#p1_9').animate({opacity:"1"}, 1000);
				setTimeout(function(){
					$('#p1_8').animate({opacity:"1"}, 2500);
				}, 800);
			}, 1200);
		}, 500);
	}, 900);
	$('#p1_7').animate({opacity:"1"}, 500);
}

function step2(){
	$('.main2').show();
	$('#p2_1').animate({top:"-190px"}, 500);
	setTimeout(function(){
		$('#p2_6').animate({opacity:"1"}, 500);
		setTimeout(function(){
			$('#p2_7').fadeIn(500);
		}, 500);
	}, 500);
}

function step3(){
	$('.main3').show();
	$('#p3_5').animate({left:"0px"}, 1000);
	setTimeout(function(){
		$('#main3-desc').animate({opacity:"1"}, 1000);
		$('#p3_4').animate({opacity:"1"}, 1000);
		$('#p3_3').animate({opacity:"1"}, 1000);
	}, 500);
}

function step4(){
	$('.main4').show();
	$('#p4_4').animate({opacity:"0.6"}, 1000);
	setTimeout(function(){
		$('#main4-desc').animate({opacity:"1"},1000);
		setTimeout(function(){
			$('#p4_3').animate({opacity:"1"},2000);
		}, 800);
	}, 800);
}