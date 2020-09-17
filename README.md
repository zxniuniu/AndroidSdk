# AndroidSdk

// 分卷压缩文件，每卷46M，压缩AndroidSdk文件夹内容，压缩文件名称AndroidSdk-20200918.7z.001, .002 ...

7za.exe a -t7z -r -m0=LZMA2 -mx9 -v18m AndroidSdk-20200918.7z AndroidSdk

// 解压分卷文件，解压到当前AndroidSdk目录

7za.exe x -y -oAndroidSdk AndroidSdk-20200916.7z.001
