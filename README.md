<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>我的游戏库</title>
<style>
body{margin:0;padding:0;background:#f4f5f7;font-family:微软雅黑}
.top{background:#2488ff;color:#fff;text-align:center;padding:30px 0;font-size:26px;font-weight:bold}
.box{display:flex}
.left{width:120px;background:#fff;padding-top:20px}
.left div{padding:12px 10px;font-size:15px;color:#333}
.left div.active{background:#e8f4ff;color:#2488ff;font-weight:bold}
.right{flex:1;padding:15px}
.item{background:#fff;border-radius:8px;padding:12px;margin-bottom:15px;display:flex;align-items:center}
.ico{width:60px;height:60px;border-radius:8px;background:#ddd;margin-right:12px}
.info{flex:1}
.name{font-size:16px;font-weight:bold}
.time{font-size:13px;color:#666;margin-top:5px}
.btn{color:#2488ff;border:1px solid #2488ff;border-radius:20px;padding:6px 15px;text-decoration:none;font-size:14px}
.foot{text-align:center;padding:20px;font-size:12px;color:#999}
</style>
</head>
<body>
<div class="top">我的游戏库</div>
<div class="box">
  <div class="left">
    <div class="active">我的推荐</div>
    <div>苹果游戏</div>
    <div>短剧专区</div>
    <div>九门游戏</div>
  </div>
  <div class="right">
    <div class="item">
      <div class="ico"></div>
      <div class="info">
        <div class="name">福马聚（主讯）</div>
        <div class="time">2026-05-03</div>
      </div>
      <a href="https://你的推广链接1.com" class="btn">查看</a>
    </div>
    <div class="item">
      <div class="ico"></div>
      <div class="info">
        <div class="name">成语大宝藏</div>
        <div class="time">2026-05-03</div>
      </div>
      <a href="https://你的推广链接2.com" class="btn">查看</a>
    </div>
  </div>
</div>
<div class="foot">我的游戏库 · 永久免费</div>
</body>
</html>
