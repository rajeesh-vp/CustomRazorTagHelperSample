Asp.Net Core razor custom Tag Helper code sample as described at https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/authoring?view=aspnetcore-3.1
© Microsoft 2020

Sample verified by rajeeshvp@gmail.com
Files Added/Changed
	1. MyPage.cshtml
	2. _ViewImports.cshtml
	3. EmailTagHelper.cs
Run https://localhost:port/mypage to see the implementation

What it does:
	<blockquote>
	<email mail-to="rajeeshvp"></email> 
		will be converted into
	<a href="mailto:rajeeshvp@gmail.com">rajeeshvp@gmail.com</a>
	</blockquote>
