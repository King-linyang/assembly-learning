#    

[bx+si+idata]表示一个内存单元  
偏移地址为(bx)+(si)+idata,bx中的数值加上si中的数值再加上idata

- 指令：mov ax,[bx+si+idata]  
  将一个内存单元内容送入到ax  
  这个内存单元的长度为2字节(字单元)，存放一个字  
  偏移地址为bx中的数值加上si中的数值再加上idata，段地址再ds中

- 数学描述  
  (ax=(ds)*16+(bx)+(si)+idata)























