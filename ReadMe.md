<head>
<meta content="en-us" http-equiv="Content-Language" />
<meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
<link href="../main.css" rel="stylesheet" type="text/css" />
<link href="../code.css" rel="stylesheet" type="text/css" />
<script src="../rainbow.min.js"></script>
</head>

<body>

## Image Helper ##
### <u> Properties </u> ###

>1. ImagePath
>2. ImagePrePath
>3. ImageStretch

### <u> How to use </u> ###

>1. To install Image Helper, run the following command in the Package Manager Console : https://www.nuget.org/packages/ImageHelper/

		Install-package ImageHelper

>2. Add to the top of xaml file : 

		xmlns:safeimage="clr-namespace:ImageLib;assembly=ImageHelper"
		
>3. Use as image control : 

		<safeimage:ImageHelper Width="350" Height="600" ImageStretch="UniformToFill" ImagePrePath="your image url/local" ImagePath="image url"/>

		
</body>

</html>
