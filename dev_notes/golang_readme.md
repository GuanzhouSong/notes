...menustart

 - [文章](#c75625dccf148721245b46b1e3e6c79f)
 - [国内获取 golang.org/x 包失败的方法](#0a924bf17d1b7242d5600e9b537b969f)

...menuend


...menustart


...menuend

<h2 id="c75625dccf148721245b46b1e3e6c79f"></h2>

### 文章

 1. [语言](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%20%E5%A4%87%E5%BF%981-%E8%AF%AD%E8%A8%80.md)   
 2. [表达式](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%20%E5%A4%87%E5%BF%982-%E8%A1%A8%E8%BE%BE%E5%BC%8F.md) 
 3. [函数 ](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%20%E5%A4%87%E5%BF%983-%E5%87%BD%E6%95%B0.md) 
 4. [数据 ](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%20%E5%A4%87%E5%BF%984-%E6%95%B0%E6%8D%AE.md)
 5. [方法和接口](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%20%E5%A4%87%E5%BF%985-%E6%96%B9%E6%B3%95%E5%92%8C%E6%8E%A5%E5%8F%A3.md)  
 7. [并发](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%20%E5%A4%87%E5%BF%987-%E5%B9%B6%E5%8F%91.md)  
 8. [包](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%20%E5%A4%87%E5%BF%988-%E5%8C%85.md)    
 9. [反射](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%E5%A4%87%E5%BF%989-%E5%8F%8D%E5%B0%84.md)  
 10. [工具](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%E5%A4%87%E5%BF%98A-%E5%B7%A5%E5%85%B7.md) ||  [go命令详解](https://www.ctolib.com/docs-go-command-tutorial-c-0-0.html)
 11. [测试](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG%E5%A4%87%E5%BF%98B-%E6%B5%8B%E8%AF%95.md)
 12. [go格式化输出 ](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG-fmt%E6%A0%BC%E5%BC%8F%E5%8C%96%E8%BE%93%E5%87%BA.md)
 13. [go源码剖析笔记](https://github.com/mebusy/notes/blob/master/dev_notes/GOLANG_src_profile.md)
 14. [learn Go in Y minutes](https://github.com/mebusy/notes/blob/master/dev_notes/learnGoInYMinutes.md)
 15. [A Tour of GO](https://github.com/mebusy/notes/blob/master/dev_notes/ATourOfGo.md)
 16. [cheat sheet](https://github.com/mebusy/notes/blob/master/dev_notes/golang_cheatsheet.md)
 17. [GoInPractice70Tech](https://github.com/mebusy/notes/blob/master/dev_notes/GoInPractice70Tech.md), [6 template](https://github.com/mebusy/notes/blob/master/dev_notes/GoIn70_6.md), [7 web form](https://github.com/mebusy/notes/blob/master/dev_notes/GoIn70_7.md), [8 with web service](https://github.com/mebusy/notes/blob/master/dev_notes/GoIn70_8.md), [9 cloud, 10 micro service](https://github.com/mebusy/notes/blob/master/dev_notes/GoIn70_9.md), [11 reflection & code generation](https://github.com/mebusy/notes/blob/master/dev_notes/GoIn70_11.md)
 18. [go tips](https://github.com/mebusy/notes/blob/master/dev_notes/go_tips.md)
 19. [godoc](https://github.com/mebusy/notes/blob/master/dev_notes/godoc.md)

---------

<h2 id="0a924bf17d1b7242d5600e9b537b969f"></h2>

### 国内获取 golang.org/x 包失败的方法

 - 其实 golang 在 github 上建立了一个[镜像库](https://github.com/golang)，如 https://github.com/golang/net 即是 https://golang.org/x/net 的镜像库
 - 获取 golang.org/x/net 包，其实只需要以下步骤

```
mkdir -p $GOPATH/src/golang.org/x
cd $GOPATH/src/golang.org/x
git clone https://github.com/golang/net.git
```
 
```
mkdir -p $GOPATH/src/golang.org/x
cd $GOPATH/src/golang.org/x
git clone https://github.com/golang/tools.git
```

