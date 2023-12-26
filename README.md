- 👋 微信公众号 ESN技术社区
- 👀 社区论坛讨论：86night.com
- 🌱 红队+Go+Python+其他时间C系列
- 💞️ I’m looking to collaborate on ...
- 📫 esnshequ@gmail.com

<!---
esnshequ/esnshequ is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<html>
<head>
<title>{$mybb->settings['bbname']}</title>
{$headerinclude}
</head>
<body>
{$header}
<div align="center" style="width: 50%; margin: auto;">
	<img src="images/logo.png">
	<h1>欢迎访问 {$mybb->settings['bbname']}</h1>
	<h2>永久域名：www.86night.com</h2>
	<h4>86Night—微信公众号Esn技术社区专属交流论坛,我们只是一群利用空余时间来增长自己的兴趣爱好的普通人</h4>
	<br>
	<a class="button" href="{$mybb->settings['bburl']}/member.php?action=login" onclick="$('#quick_login').modal({ fadeDuration: 250, keepelement: true, zIndex: (typeof modal_zindex !== 'undefined' ? modal_zindex : 9999) }); return false;" style="margin-right:10px">登入论坛</a>
	<a href="{$mybb->settings['bburl']}/member.php?action=register" class="button">注册论坛</a>
</div>
{$footer}
</body>
</html>
