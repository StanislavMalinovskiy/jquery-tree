Current version: http://jquery-tree.googlecode.com/files/jquery-tree.tar.gz

Demo (will probably move to another hosting): http://max-at-work.narod.ru/jquery.tree.test.html

Demo without js: http://max-at-work.narod.ru/jquery.tree.test.nojs.html

Usage:
```
<head>
	<link rel="stylesheet" type="text/css" href="css/jQuery.Tree.css" />
</head>

<body>
	<ul id="tree">
		<li>
			<label>
				<!-- Label is essential --><input type="checkbox" />Element with checkbox
			</label>
		</li>
		<li>
			<label>
				<input type="checkbox" />Group
			</label>
			<ul>
				<li>
					<label>
						<input type="checkbox" />Sub-element
					</label>
				</li>
			</ul>
		</li>
	</ul>
	<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.3.2/jquery.min.js">
	</script>
	<script type="text/javascript" src="jQuery.Tree.js">
	</script>
	<script type="text/javascript">
		$(document).ready(function(){
			$("#tree").Tree();
		});
	</script>
</body>
```

Available "as is", works in FF3.5, IE8, Chrome 4 (others not tested).