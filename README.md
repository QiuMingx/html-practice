# HTML_practice
HTML 基础知识

# HTML的修饰标签：
```
    文字斜体：<i> </i>
    文字加粗：<b> </b>
    下划线：  <ins> </ins>
    删除线：  <del> </del>
    下标：    <sub> </sub>
    上标：    <sup> </sup>
```
# HTML的常用提示符号：
        <       &lt; 
        >       &gt;
        ™       &trade;
        ®       &reg;
        ©       &copy;

# HTML的列表标签：
    无序列表：
        <ul>
            <li>列表项</li>
            <li>列表项</li>
            <li>列表项</li>
            .....
        </ul>
        属性： 
            disc ：圆点
            square ：正方形
            circle ：空心圆
    有序列表：
        <ol>
            <li>列表项</li>
            <li>列表项</li>
            <li>列表项</li>
            .....
        </ol>
        属性： 
            l ：数字
            a ：小写字母
            A ：大写字母
            i : 罗马数字
            I : 大写罗马数字
列表的应用场景：   
            
# 图像标签
    语法：
        <img src = "" alt = "" ../>
    属性：
        src:    必填 显示图像的URL
        alt:    图像替代文本 (用户无法查看图像，alt属性可以代替图像显示在浏览器中的内容。)
        height: 图像的高
        width:  图像的宽

# 超链接标签
    语法：
        <a href = "" >内容</a>
    属性：
        href：链接地址。
        target: 链接的目标窗口 _self _blank _top _parent
        title: 链接提示文字
        name: 链接命名
    锚点：
        同页面的跳转：
            <a href="#锚点名">内容</a>
            <a href="" name = "锚点名"></a>
        不同页面的跳转：
            <a href="网页名称#锚点名">内容</a>
            <a href="" name = "锚点名"></a>
    电子邮件：
        <a href="mailto:邮件地址">内容</a>
    下载文件：
        <a href="下载文件地址">内容</a>

# 表格 table
    语法结构：
        <caption></caption>: 表格标题
        <th></th>: 表头
        <tr></tr>: 表示行
        <td></td>: 表示单元格
    
        <table>
            <caption>...</caption>
            <thead>
                <tr>
                    <td>表头</td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>主体</td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <td>脚注</td>
                </tr>
            </tfoot>
        </table>
    
    






