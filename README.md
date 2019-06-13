# pdf_lib
通过cdn方式，方便展示pdf的库，依赖PDFJS
## 使用方式  
1 android main目录下新建assets，并将文件拷贝到此目录  
2 data = file:///android_asset/show_pdf.html? + url（url为pdf链接地址）  
3 通过webview展示 mWebview.loadUrl(data);
