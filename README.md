<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
	</head>
	<body>
		<form name="form1">
			<label for=username>姓名</label>
			<input name=username id=username type=text required />
			<br/>
			<label for=age>年龄</label>
			<input name=age id=age type=number min=0 max=100/>
			<br/>
			<label for=birthday>出生日期</label>
			<input name=birthday id=birthday type=date />
			<br/>
			<label for=email>Email</label>
			<input name=email id=email type=email required />
			<br/>
			<label for=url>个人主页</label>
			<input name=url id=url type=url />
			<br/>
			<label for=memo>个人简介</label>
			<textarea name=memo id=memo required ></textarea>
			<br/>
			<input type=submit>
	</body>
</html>
