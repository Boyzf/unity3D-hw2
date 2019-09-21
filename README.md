# unity3D-hw2

## 列出游戏中提及的事物（Object）
- 牧师
- 魔鬼
- 船
- 河岸
- 河流
## 玩家动作表（规则表），注意，动作越少越好。
<table>
    <thead>
        <tr>
            <th>动作</th>
            <th>条件</th>
            <th>结果</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>点击“restart”</td>
            <td> </td>
            <td>初始化游戏</td>
        </tr>
        <tr>
            <td>点击牧师/恶魔</td>
            <td>牧师/恶魔在岸上</td>
            <td>牧师/恶魔上船</td>
        </tr>
       <tr>
            <td>点击牧师/恶魔</td>
            <td>牧师/恶魔在船上</td>
            <td>牧师/恶魔上岸</td>
        </tr>
        <tr>
            <td>点击船</td>
            <td>船是静止的且船上有人</td>
            <td>船移动到对岸</td>
        </tr>
      <tr>
            <td>游戏胜利</td>
            <td>所有人物都移动到对岸</td>
            <td>显示胜利“you win”</td>
        </tr>
      <tr>
            <td>游戏失败</td>
            <td>存在一边的岸及船上的牧师总数少于恶魔</td>
            <td>显示失败“you lose”</td>
        </tr>
    </tbody>
</table>


## 根据要求将游戏中对象做成预制
![](QQ截图20190920134754.png)

## 整个游戏仅主摄像机 和 一个empty对象，其他对象皆由代码动态生成。
![](QQ截图20190920135120.png)

## 程序结构为MVC程序结构，分为model， view以及 controller。
![](QQ截图20190920134545.png)

## 结果界面大致如下
![](QQ截图20190920132133.png)

## 视屏链接
  [视频演示](https://v.youku.com/v_show/id_XNDM2ODY1NzEyOA==.html?spm=a2h3j.8428770.3416059.1)

视频链接：https://v.youku.com/v_show/id_XNDM3MDI4NjUwMA==.html?spm=a2hzp.8244740.0.0
