# 像素约会卡

这是一个原创实现、但流程非常接近你提供的像素恋爱卡网站的静态页面。

最终表单已经设置为发送到：

    a@gmail.com

提交方式使用 FormSubmit：

    https://formsubmit.co/a@gmail.com

## 第一次使用
FormSubmit 通常会向 a@gmail.com 发送一次激活/确认邮件。
需要先在该邮箱中确认一次，之后表单回复才会正常投递。

## GitHub Pages 部署
1. 新建 GitHub repository
2. 上传 index.html
3. Settings → Pages
4. 选择 main branch / root
5. 保存后分享 GitHub Pages 链接

## 注意
邮箱地址会出现在网页源代码中，这是纯静态 FormSubmit 方案的正常情况。
如果你不想让收件邮箱暴露在源代码里，需要改用自己的后端/API。
