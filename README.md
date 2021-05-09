# PPP_develop
以GAMP为基础，进行PPP相关的一些学习研究
# 配置
以VS为基础进行debug和开发，本仓库已经建立好相应的debug工程，首次拉代码仍需在VS中配置以下属性配置
```
1:Configuration Properties --> c/c++ --> Preprocessor --> Preprocessor Definitions:
WIN32;_DEBUG;_CONSOLE;%(PreprocessorDefinitions);_CRT_SECURE_NO_WARNINGS;ENAGLO;ENACMP;ENAGAL;ENAQZS;NFREQ=3
2: Configuration Properties --> Linker --> Debugging --> Generate Debug Info: Y(/DEBUG)
3: Configuration Properties --> C/C++ --> General --> Debug Information Format: C7
```
