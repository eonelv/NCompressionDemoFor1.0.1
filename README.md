# NCompressionDemoFor1.0.1
this demo is to teach you how to use NCompression in your project

# what feather this plugin support
This is a code plugin that can compress or decompress file by steaming. it will use less memory when compress or decompress

# how to use
This plugin give you two ways. if you are a blueprint worker, you can use the way show in the picture.
![QQ_1721727177907](https://github.com/user-attachments/assets/5ed8e0dc-8681-4c9d-aca9-0ceb54b1e329)
the first parameter is souce file to read
the second parameter is destination file to write
the third one is working buffer size, you can pass it with 0
the next one is work dir. if Use Saved Dir is selected, the will work in FPaths::ProjectSavedDir(), otherwise use FPaths::ProjectPersistentDownloadDir()

if your project is C++ project, you should call the function directly, FNCompression::DecompressFileZLIB(SrcFile, DstFile, BufferSize, bUseSavedDir);

