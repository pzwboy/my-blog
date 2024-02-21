---
layout: page
title: Google 镜像 密码认证页面
---
<script type="text/javascript">   
	function password() {   
		var testV = 1;   
		var pass1 = prompt('为了避免滥用或用于非法用途，请输入密码：','');   
		while (testV < 3) {   
			if (!pass1)    
			history.go(-1);   
			if (pass1 == "1607-2209") {//设置密码
				alert('密码正确，关闭此弹窗以跳转。');   
				window.location.href="https://google.pzwboy.eu.org/";//添加你要跳转的页面
				break;   
			}    
	testV+=1;   
	var pass1 =    
	prompt('密码错误，请重新输入：','');   
	}   
	if (pass1!="password" & testV ==3)    
	history.go(-1);   
	return " ";   
	}    
document.write(password());   
</script>
 