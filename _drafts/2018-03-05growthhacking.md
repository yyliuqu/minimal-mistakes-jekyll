title	author
Hello World!
backstreettoy
{{ page.title }}

{{ page.author }}

{{ site.filePath.image }}

通过在_posts文件夹中增加文件来建立文章

如果要使用草稿功能，在_drafts文件夹中增加文章，默认情况下草稿不会发布到网站上，如果需要发布，在参数中增加 --drafts，例如jekyll serve --incremental --drafts

如果要插入图片，将文件拷贝到 assets/img 文件夹中，然后通过下列的方式引用图片

<img src="{{site.filePath.image}}/filename " />
