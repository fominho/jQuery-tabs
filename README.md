# jQuery-tabs

<div class="wrapper">
		                		<div class="tabs">
		                			<span class="tab">Москва</span> /
		                			<span class="tab">Караганда</span>
		                		</div>
		                		<div class="tab_content">
		                			<div class="tab_item">Содержимое 1</div>
		                			<div class="tab_item">Содержимое 2</div>
		                		</div>
		                	</div>
		                	
		                	
		                	
		                	
	$(".wrapper .tab").click(function()  {  
		$(".wrapper .tab").removeClass("active").eq($(this).index()).addClass("active");
		$(".tab_item").hide().eq($(this).index()).fadeIn()

	}).eq(0).addClass("active");
