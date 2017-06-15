<meta charset="utf-8">

### Php常用的字符串处理函数、数组处理函数和文件操作函数  ###
<br>


### 字符串处理函数： ###

----------

    count()	计算数组中的单元数目或对象中的属性个数
    
    foreach()		遍历数组
     
    list()		遍历数组
    
    explode()		将字符串转成数组
    
    implode()		将数组转成一个新字符串
    
    is_array()	检查是否是数组
    
    print_r() 	输出数组
    
    sort()		数组排序
    
    array_keys() 	返回数组中所有的键名
    
    array_values() 		返回数组中所有的值
    
    key()				从关联数组中取得键名
    
    array()		 创建数组
    
    array_combine() 	通过合并两个数组来创建一个新数组
    
    range() 	创建并返回一个包含指定范围的元素的数组
    
    array_merge()	把两个或多个数组合并成一个数组
    
    array_slice()	在数组中根据条件取出一段值
    
    array_diff()	返回两个数组的差集数组
    
    array_intersect()	计算数组的交集
    
    array_search()	在数组中搜索给定的值
    
    array_splice()	移除数组的一部分且替代它
    
    array_key_exists()	判断某个数组中是否存在指定的key
    
    shuffle()		把数组中的元素按随机顺序重新排列
    
    array_flip()	交换数组中的键和值
    
    array_reverse()	将原数组中的元素顺序翻转，创建新的数组并返回
    
    array_unique()	移除数组中重复的值



 
#### 数组处理函数： ####

----------

    
    strpos() 	查找字符串位置
    
    str_replace(search,replace,$str):		
    从$str中查找search用replace来替换
    
    str_split($str,len): 把$str按len长度进行分割返回数组
    
    ltrim、rtrim  去除左侧和右侧空格\字符
    
    strtolower($str)  	字符串转换为小写
    
    strtoupper($str)  	字符串转换为大写
    
    ucfirst($str)	 将字符串的第一个字符转换为大写
    
    trim()	去除字符串首尾处的空白字符（或者其他字符）
    
    strlen()   	 字符串长度
    
    substr()   	 截取字符串
    
    substr_replace()对指定字符串中的部分字符串进行替换
    
    strstr()检索字符串函数
    
    explode()分割字符串函数
    
    implode()将数组合并成字符串
    
    str_repeat()重复一个字符串
    
    addslashes();转义字符串
    
    htmlspecialchars()HTML 实体转义



### 文件操作处理函数： ###

----------

    file_exists()	判断文件或文件夹是否存在 
    
    fopen()		打开文件 
    
    fclose()		关闭文件 
    
    is_writable()		判断是否可写入 
    
    fwrite()		写入数据 
    
    feof()		测试文件指针是否到了文件结束的位置
     
    fgets()		从文件指针中读取一行 
    
    fgetcsv()		解析CVS格式字段 
    
    readfile ()		读取整个文件内容 
    
    file_get_contents()		将整个文件作为一个字符串读入 
    
    fgetc()		读取一个字符 
    
    fread()		读取任意长度 
    
    filesize()		获取一个文件的大小
     
    unlink()		删除一个文件 
    
    rmdir()			删除一个目录 
    
    mkdir()			创建一个目录 
    
    basename()		返回径中的文件名 
    
    dirname()		返回路径中的目录部分 
    
    pathinfo()		返回文件路径的信息：  包括以下数组单元 
    
    	1. dirname(显示所有的路径)
    	2. basename(显示文件名和后缀名) 
    	3. extension(显示后缀名)
     
    copy() 	 复制文件
    
    file_put_contents()		将一个字符串写入文件 
    
    filetype()		取得文件类型 
    
    is_dir()		判断是否是一个目录 
    
    flock()		进行文件锁定 
    
    is_uploaded_file()		判断文件是否能过HTPP POST 上传
    
    move_uploaded_file()		将上传的文件移动到新位置 


### php操作mysql处理函数： ###

----------


    mysql_connect()		建立数据库连接
    
    mysql_close()		关闭数据库连接
    
    mysql_select_db()	选择数据库
    
    mysql_query()		执行MySQL语句
    
    mysql_result()		获取和显示数据
    
    mysql_fetch_row()		获取和显示数据
    
    mysql_fetch_array()		获取和显示数据
    
    mysql_fetch_assoc()		获取和显示数据
    
    mysql_num_rows()		返回结果集中的行数
    
    mysql_affected_rows() Insert,update,delete	影响的记录的个数
    
    mysql_db_name()			获取数据库名
    
    mysql_fetch_field()		获取字段信息