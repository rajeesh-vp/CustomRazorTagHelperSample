Asp.Net Core razor custom Tag Helper code sample as described in https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/authoring?view=aspnetcore-3.1
© Microsoft 2020

Run https://localhost:port/mypage to see the implementation

What it does:
	```
	<email mail-to="rajeeshvp"></email> 
		will be converted into
	<a href="mailto:rajeeshvp@gmail.com">rajeeshvp@gmail.com</a>
	```
	Check commit 4755ad8 for changes
