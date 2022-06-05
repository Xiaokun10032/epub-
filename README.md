我即使是死了，钉在棺材里了，也要在墓里,用这腐朽的声带喊出：
「三部敬，紫电老贼，天城启」
以上几人我***！


HTML打包，和做网页没什么太大区别
###
本质是一个.zip压缩文件,算法只认LZ77/LZ78，.7z.tar.gz都不行，Linux下可以直接选择epub格式压缩（改个后缀有什么麻烦的
文件树
###############################################
|mimetype                                     #
|                                             #
|META-INF                                     #
  |container.xml                              #
  |calibre_bookmarks.txt(非必要文件，放在最后)   #
  |                                           #
|OEBPS                                        #
  |Fonts                                      #
    |example.ttf                              #
  |Images                                     #
    |example.jpg                              #
  |Styles                                     #
    |example.css                              #
  |Text                                       #
    |example.xhtml                            #
  |content.opf                                #
  |toc.ncx                                    #
###############################################
***mimetype是一个固有文件，内容为     application/epub+zip
***META-INF里是元信息，包含container.xml,<rootfile/>指向了.opf文件的路径
***OEBPS包含了书籍主体内容·字体··插图··文字··样式表·
  content.opf 可读性较高，不做赘述
  toc.ncx  目录文件，depth、totalPageCount和maxPageNumber三个是固有值,<navpoint/>即是目录
****************************************************************************************
离个大谱，为什么REARMED空格换行都给我吃了
