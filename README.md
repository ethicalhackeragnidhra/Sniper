Sniper
======
>Sniper是一个功能强大、高性能的HTTP负载工具,采用Golang编写。利用多核并发优势，实现海量并发、

>超低内存占用、丰富图表展示。是测试、分析、优化服务端性能的绝佳助手！

###体验
提供以下可执行文件，可直接运行
* Mac OSX 64 bit
* Mac OSX 32 bit
* Linux 64 bit
* Linux 32 bit

###功能
以实用为原则，实现以下功能
- GET / POST
- keep-alive模式
- https
- 图表展示结果
- 测试多个目标
- 支持大文件负载

####对比同类工具
<table>
   <tr>
      <td>工具 </td>
      <td>编写语言 </td>
      <td>keep-alive </td>
      <td>https </td>
      <td>多点测试 </td>
      <td>结果展示 </td>
      <td>代理</td>
   </tr>
   <tr>
      <td>ab </td>
      <td>c </td>
      <td>NO </td>
      <td>YES </td>
      <td>NO </td>
      <td>html，标准输出</td>
      <td>YES </td>
   </tr>
   <tr>
      <td>siege </td>
      <td>c </td>
      <td>YES </td>
      <td>YES </td>
      <td>YES </td>
      <td>csv，标准输出</td>
      <td>YES </td>
   </tr>
   <tr>
      <td>http_load </td>
      <td>c </td>
      <td>NO </td>
      <td>YES </td>
      <td>YES </td>
      <td>标准输出</td>
      <td>YES </td>
   </tr>
   <tr>
      <td>webbench </td>
      <td>c </td>
      <td>NO </td>
      <td>YES </td>
      <td>NO </td>
      <td>标准输出</td>
      <td>YES </td>
   </tr>
   <tr>
      <td>sniper</td>
      <td>go</td>
      <td>YES </td>
      <td>YES </td>
      <td>YES </td>
      <td>js+html5，标准输出</td>
      <td>NO </td>
   </tr>
</table>


##性能
- 内存占用略高于Apache Benchmark（ab）
- 执行速度接近ab，高并发时超过ab
- 支持10k以上并发

##图表展示
- 统计分析每个请求
- 输出建立连接时间
- 输出服务端响应时间
- 输出总时间

##使用说明
1. 安装Golang
2. 安装Sniper
3. 参数说明

##关于
- 友好项目
- 作者
- Licence
