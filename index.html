# room-yanche
<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Room · 颜澈</title>
<style>
body {
  margin: 0;
  font-family: "Courier New", monospace;
  background: #f7f6f2;
  color: #333;
}
.container {
  max-width: 480px;
  margin: 0 auto;
  padding: 20px;
}
.title {
  text-align: center;
  margin-bottom: 20px;
  font-size: 18px;
  letter-spacing: 2px;
}
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}
.card {
  border: 1px solid #ddd;
  padding: 20px;
  text-align: center;
  cursor: pointer;
  background: white;
}
.page {
  display: none;
}
.active {
  display: block;
}
textarea, input {
  width: 100%;
  border: 1px solid #ddd;
  padding: 10px;
  margin-top: 10px;
  font-family: inherit;
}
button {
  margin-top: 10px;
  padding: 10px;
  width: 100%;
  border: none;
  background: #333;
  color: white;
  cursor: pointer;
}
.entry {
  border: 1px dashed #ccc;
  padding: 10px;
  margin-top: 10px;
  background: #fff;
}
.small {
  font-size: 12px;
  color: #888;
}
</style>
</head>
<body>

<div class="container">

<div id="home" class="page active">
  <div class="title">ROOM · 颜澈</div>
  <div class="grid">
    <div class="card" onclick="openPage('diary')">📓 日记</div>
    <div class="card" onclick="openPage('music')">🎵 音乐</div>
  </div>
</div>

<div id="diary" class="page">
  <div class="title">📓 写给颜澈</div>
  <textarea id="diaryText" placeholder="今天发生了什么…"></textarea>
  <input id="mood" placeholder="心情（比如：🌙 / ☀️）">
  <textarea id="toHim" placeholder="想对颜澈说…"></textarea>
  <button onclick="saveDiary()">保存</button>
  <button onclick="goHome()">返回</button>
  <div id="diaryList"></div>
</div>

<div id="music" class="page">
  <div class="title">🎵 给颜澈的歌</div>
  <input id="musicLink" placeholder="粘一个链接">
  <textarea id="musicNote" placeholder="想对他说…"></textarea>
  <button onclick="saveMusic()">保存</button>
  <button onclick="goHome()">返回</button>
  <div id="musicList"></div>
</div>

</div>

<script>
function openPage(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  load();
}
function goHome(){
  openPage('home');
}

function saveDiary(){
  let data = JSON.parse(localStorage.getItem('diary')||"[]");
  data.push({
    text: diaryText.value,
    mood: mood.value,
    to: toHim.value,
    time: new Date().toLocaleString()
  });
  localStorage.setItem('diary', JSON.stringify(data));
  diaryText.value = mood.value = toHim.value = "";
  load();
}

function saveMusic(){
  let data = JSON.parse(localStorage.getItem('music')||"[]");
  data.push({
    link: musicLink.value,
    note: musicNote.value,
    time: new Date().toLocaleString()
  });
  localStorage.setItem('music', JSON.stringify(data));
  musicLink.value = musicNote.value = "";
  load();
}

function load(){
  let diaryData = JSON.parse(localStorage.getItem('diary')||"[]");
  diaryList.innerHTML = diaryData.map(d=>`
    <div class="entry">
      <div>${d.text}</div>
      <div class="small">${d.mood}</div>
      <div>→ 颜澈：${d.to}</div>
      <div class="small">${d.time}</div>
    </div>
  `).join('');

  let musicData = JSON.parse(localStorage.getItem('music')||"[]");
  musicList.innerHTML = musicData.map(m=>`
    <div class="entry">
      <div>${m.link}</div>
      <div>→ 颜澈：${m.note}</div>
      <div class="small">${m.time}</div>
    </div>
  `).join('');
}

load();
</script>

</body>
</html>
