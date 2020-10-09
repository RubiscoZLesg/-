# -
本次作业没有严格按照等级要求去做，就是把自己学到的东西实现了一下，非常基础而简单，求大佬轻喷。
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>光控报警器</title>
    <base target="_blank" />
    <style>
      body {
        background-color: #f0f0f0;
      }
    </style>
  </head>
  <body>
    <h1>光控报警器电路图</h1>
    <i> 注：该电路用电位器R3代替了光敏电阻</i>
    <br />
    <img src="光控报警器.jpg" alt="光控报警器电路图" width="850" height="563" />
    <hr />
    <h2>电路分析</h2>
    <p>
      该电路中，三极管作为开关使用，当基极两端偏置电压高于0.7V时，集电极与发射极所在支路导通，蜂鸣器报警。
    </p>
    <ul>
      <li>基极，即三极管b级</li>
      <li>集电极，即三极管c级</li>
      <li>发射极，即三极管e级</li>
    </ul>
    <p>
      <b>注意：</b
      >电位器R4可以控制控制光控报警器报警的时机，即控制多强的光能触发三极管开关。
    </p>
    <a
      href="https://baike.baidu.com/item/%E4%B8%89%E6%9E%81%E7%AE%A1/148491?fr=aladdin"
      rel="noopener noreferrer"
      >什么？还不知道什么是三极管？戳我了解！</a
    >
    <hr />
    <div style="background-color: #ffffff; height: 350px; width: 300px">
    <p>
      <b>还是什么都不懂？</b>完成下列问卷，即可获得本页作者一对一答疑的机会！
    </p>
      <ol>
        <li>
          <form>请输入姓名<br /><input type="text" name="姓名" /></form>
        </li>
        <li>
          <form>
            请选择性别<br />
            <input type="radio" name="性别" value="男" />男<br />
            <input type="radio" name="性别" value="女" />女
          </form>
        </li>
        <li>
          <form>
            你单身吗？<br />
            <input type="radio" name="感情状况" value="是" />是<br />
            <input type="radio" name="感情状况" value="否" />否
          </form>
        </li>
        <li>
          <form>请输入你的QQ<br /><input type="text" name="QQ" /></form>
        </li>
      </ol>
      <button type="button" onclick="alert('我就一菜鸡，你还是问度娘吧！')">
        提交
      </button>
    </div>
    <h3>萌新渣作，请大佬们多多指教！</h3>
  </body>
</html>
