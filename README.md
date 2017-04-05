# snh48-get-lucky-tickets
SNH48官方商城刷票捡漏脚本，完全模拟手动刷票，将手动刷票过程自动化
## 使用方法
1. Chrome浏览器安装 [Tampermonkey](https://chrome.google.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo) 扩展；Firefox浏览器安装 [Greasemonkey](https://addons.mozilla.org/zh-cn/firefox/addon/greasemonkey/) 扩展
2. 点击 [这里](https://github.com/TangHHH/snh48-get-lucky-tickets/raw/master/SNH48%20Lucky%20Ticket%201.1%20(ticket%20page).user.js) 安装脚本
3. 打开 [剧场门票](http://shop.48.cn/tickets) ，打开需要刷票捡漏的票务页面，选择捡漏票种、设定好刷票间隔，点击“开始捡漏”即可开始刷票，在票务图片的下方会有输出，如果成功会自动跳到门票详情页面，开始后点击“停止捡漏”可停止刷票或修改参数重新开始。
        
        
## 更新日志      
[2017.4.5] 1.1.5版本                  
什么时候官网取消刷票封IP了……现在取消最小刷票间隔限制             
[2017.2.21] 1.1.4版本            
官网现在成了只转票不出票了……所以现在脚本改成10秒转不出票重新提交购买       
[2017.2.13] 1.1.3版本       
忽略可能是由于服务器并发请求的内部错误引起的错误代码为162001的请求错误       
[2017.2.7] 1.1.2版本      
更新匹配地址       
[2016.12.15] 1.1版本          
更新内容：优化IO，现在可以不用修改脚本内容，也不用关闭脚本了，直接在页面上输入相应参数点击“开始捡漏”即可，开始后点击“停止捡漏”可停止刷票并修改参数     
[2016.12.14] 1.0版本 

## LICENSE
MIT
