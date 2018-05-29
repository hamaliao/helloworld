#查找当前目录所有源文件
aux_source_directory(. SRCS)

#生成执行文件
add_executable(helloworld ${SRCS})


