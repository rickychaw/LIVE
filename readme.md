# 直播源 订阅列表

<style>
body { font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif; }
.header-box {
  background-color:#4f46e5;
  color:white;
  text-align:center;
  padding:2rem 1rem;
  border-radius:10px;
}
.playlist {
  background-color:white;
  padding:1rem 1.5rem;
  margin:1rem 0;
  border-radius:8px;
  box-shadow:0 2px 8px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}
.playlist:hover { transform: translateY(-2px); }
.link-block {
  display:flex;
  align-items:center;
  justify-content:space-between;
  background:#f5f5f5;
  padding:0.5rem 1rem;
  border-radius:5px;
  font-family:monospace;
  word-break:break-all;
  cursor:pointer;
}
.link-block:hover { background:#e0e0e0; }
.description { font-size:0.9rem; color:#555; margin-top:0.2rem; }
footer { text-align:center; padding:1rem; font-size:0.9rem; color:#888; }
</style>

<div class="header-box">
  <h1>直播源 订阅列表</h1>
  <p>点击链接即可复制完整 URL，在播放器中使用</p>
</div>

---

<div class="playlist">
  <div class="link-block" onclick="copyToClipboard('https://sub.ishare.us.kg/yylunbo.m3u')">
    https://sub.ishare.us.kg/yylunbo.m3u
  </div>
  <span class="description">YY轮播源，每天更新</span>
</div>

<div class="playlist">
  <div class="link-block" onclick="copyToClipboard('https://sub.ishare.us.kg/huyayqk.m3u')">
    https://sub.ishare.us.kg/huyayqk.m3u
  </div>
  <span class="description">HUYA直播频道列表</span>
</div>

<div class="playlist">
  <div class="link-block" onclick="copyToClipboard('https://sub.ishare.us.kg/douyuyqk.m3u')">
    https://sub.ishare.us.kg/douyuyqk.m3u
  </div>
  <span class="description">斗鱼直播精选</span>
</div>

<div class="playlist">
  <div class="link-block" onclick="copyToClipboard('https://sub.ishare.us.kg/bililive.m3u')">
    https://sub.ishare.us.kg/bililive.m3u
  </div>
  <span class="description">Bilibili 直播频道</span>
</div>

<footer>
  © 2025 IPTV 发布页面 | Powered by GitHub Pages
</footer>

<script>
function copyToClipboard(text) {
  navigator.clipboard.writeText(text).then(() => {
    alert('已复制链接：\n' + text);
  }, () => {
    alert('复制失败，请手动复制：\n' + text);
  });
}
</script>
