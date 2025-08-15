<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Progressive Self‑Development</title>
<style>
  :root{
    --bg:#f6f7fb;--card:#ffffff;--ink:#0f1220;--muted:#6b7280;
    --accent:#2563eb;--accent-2:#10b981;--danger:#ef4444;--border:#e5e7eb;
    --ring: 0 10px 30px rgba(15,18,32,.06);
  }
  *{box-sizing:border-box}
  html,body{height:100%}
  body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif}
  .container{max-width:980px;margin:0 auto;padding:16px}
  header{display:flex;gap:12px;align-items:center;justify-content:space-between;margin-bottom:12px}
  h1{font-size:20px;margin:0}
  .btn{border:0;border-radius:12px;padding:10px 14px;font-size:14px;cursor:pointer;background:var(--accent);color:#fff;transition:.15s;box-shadow:0 1px 1px rgba(0,0,0,.04)}
  .btn:hover{filter:brightness(.96)}
  .btn.secondary{background:#e5e7eb;color:#111}
  .btn.ghost{background:transparent;border:1px solid var(--border);color:var(--ink)}
  .btn.success{background:var(--accent-2);color:#fff}
  .btn.danger{background:var(--danger);color:#fff}
  .btn.ghost-danger{background:transparent;border:1px solid var(--danger);color:var(--danger)}
  .grid{display:grid;gap:12px}
  .card{background:var(--card);border:1px solid var(--border);border-radius:16px;padding:14px;box-shadow:var(--ring)}
  label{font-size:12px;color:var(--muted);display:block;margin-bottom:6px}
  input[type="text"],input[type="number"],textarea{width:100%;padding:10px;border:1px solid var(--border);border-radius:12px;background:#fff}
  textarea{min-height:72px;resize:vertical}
  .topic{display:flex;gap:12px;align-items:center}
  .topic-name{flex:0 0 240px;font-weight:600}
  .bar{position:relative;height:16px;background:#f1f5f9;border-radius:10px;overflow:hidden;border:1px solid var(--border)}
  .bar>span{position:absolute;left:0;top:0;height:100%;background:linear-gradient(90deg,#60a5fa,#2563eb)}
  .bar.overflow>span{background:repeating-linear-gradient(45deg,#60a5fa,#60a5fa 10px,#2563eb 10px,#2563eb 20px)}
  .tick{position:absolute;top:-3px;bottom:-3px;width:1px;background:#e5e7f0}
  .small{font-size:12px;color:var(--muted)}
  .row{display:flex;gap:10px;flex-wrap:wrap}
  .spacer{height:8px}
  table{width:100%;border-collapse:collapse;table-layout:fixed}
  th,td{border-bottom:1px solid var(--border);padding:10px 8px;text-align:left;font-size:13px;vertical-align:top}
  th{color:var(--muted);font-weight:600}
  .pill{display:inline-block;padding:2px 8px;border-radius:999px;border:1px solid var(--border);font-size:12px;color:#374151;background:#f9fafb}
  .seg-indicator{display:flex;gap:4px}
  .seg{flex:1;height:8px;border-radius:6px;background:#e5e7eb}
  .seg.filled{background:#93c5fd}
  .hr{height:1px;background:var(--border);margin:10px 0}
  .right{margin-left:auto}
  .wrap{display:flex;gap:12px;flex-wrap:wrap}
  .circle-wrapper{display:flex;justify-content:center;align-items:center;margin-bottom:10px;position:relative}
  svg{transform:rotate(-90deg)}
  .circle-text{position:absolute;font-size:18px;font-weight:700}
  #radarCard canvas,#topicRadarCard canvas{display:block;width:100%;max-width:700px;margin:auto;background:#fff;border:1px solid var(--border);border-radius:12px;box-shadow:var(--ring)}

  /* ฟอร์มเพิ่มเควส */
  .quest-form{display:flex;gap:8px;align-items:end;background:#f9fafb;border:1px dashed var(--border);padding:10px;border-radius:12px;margin-top:10px}
  .quest-form .btn{padding:8px 12px}

  /* รายการค้างบันทึก */
  #pendingList{background:#f9fafb;border:1px solid var(--border);border-radius:12px;padding:10px;margin-top:10px}
  #pendingList .item{display:flex;gap:8px;margin:4px 0;align-items:center}
  #pendingList .delta{min-width:72px;font-weight:700}

  /* ประวัติอ่านง่าย: คอลัมน์หมายเหตุห่อบรรทัด */
  .note-cell{white-space:pre-wrap;word-break:break-word}

  /* ===== Modal ใส่หมายเหตุ + ประวัติเควส ===== */
  .modal{position:fixed;inset:0;background:rgba(15,18,32,.45);display:none;align-items:center;justify-content:center;padding:14px;z-index:50}
  .dialog{width:min(820px,calc(100% - 24px));background:#fff;border:1px solid var(--border);border-radius:16px;box-shadow:0 20px 60px rgba(0,0,0,.18);overflow:hidden}
  .dialog header{display:flex;gap:12px;align-items:center;justify-content:space-between;padding:12px 14px;border-bottom:1px solid var(--border)}
  .dialog .content{display:grid;grid-template-columns:1.2fr .8fr;gap:12px;padding:14px}
  .hist{border:1px solid var(--border);border-radius:12px;padding:10px;background:#fafafa;max-height:260px;overflow:auto}
  .hist h4{margin:0 0 6px 0;font-size:13px;color:#6b7280}
  .hist .entry{border-bottom:1px dashed #e5e7eb;padding:6px 0}
  .hist .entry:last-child{border-bottom:0}
  .dialog footer{display:flex;gap:10px;justify-content:flex-end;padding:12px 14px;border-top:1px solid var(--border);background:#fafafa}
</style>
</head>
<body>
<div class="container">
  <header>
    <h1>Progressive Self‑Development</h1>
    <div class="wrap">
      <button class="btn" id="addTopicBtn">เพิ่มหัวข้อหลัก</button>
      <button class="btn secondary" id="exportAllBtn">ส่งออกข้อมูลทั้งหมด</button>
      <span class="pill" id="statusPill">v2 • Local</span>
    </div>
  </header>

  <div class="circle-wrapper">
    <svg width="100" height="100">
      <circle cx="50" cy="50" r="45" stroke="#e5e7eb" stroke-width="10" fill="none"/>
      <circle id="progressCircle" cx="50" cy="50" r="45" stroke="#2563eb" stroke-width="10" fill="none" stroke-linecap="round" stroke-dasharray="282.743" stroke-dashoffset="282.743"/>
    </svg>
    <div class="circle-text" id="circleText">0%</div>
  </div>

  <div class="card" id="radarCard" style="overflow:hidden">
    <div class="small" style="margin-bottom:6px">สรุปภาพรวมหน้าแรก: รูปหลายเหลี่ยมจะเปลี่ยนตามจำนวนหัวข้อหลัก (ค่าคือ % เฉลี่ยจากหัวข้อย่อยของแต่ละหัวข้อหลัก)</div>
    <canvas id="radarCanvas" height="140"></canvas>
  </div>

  <section id="homeView" class="grid">
    <div class="card"><div class="small">หน้าแรก • แตะหัวข้อหลักเพื่อเข้าไปเพิ่ม/จัดการหัวข้อย่อย • บาร์ของหัวข้อหลัก = ค่าเฉลี่ยเปอร์เซ็นต์ของหัวข้อย่อยทั้งหมด</div></div>
    <div id="topicsList" class="grid"></div>
  </section>

  <section id="mainView" class="grid" style="display:none">
    <div class="card">
      <div class="row" style="align-items:center">
        <button class="btn ghost" id="backHomeBtn">← กลับหน้าแรก</button>
        <h2 id="mainTitle" style="margin:0"></h2>
        <span class="right small" id="mainSummary"></span>
        <button class="btn danger" id="deleteMainBtn">ลบหัวข้อหลักนี้</button>
      </div>
    </div>
    <div class="card" id="topicRadarCard" style="overflow:hidden">
      <div class="small" style="margin-bottom:6px">เรดาร์หัวข้อย่อยของหัวข้อหลักนี้</div>
      <canvas id="topicRadarCanvas" height="200"></canvas>
    </div>
    <div class="card">
      <div class="row" style="align-items:center">
        <div style="font-weight:700">หัวข้อย่อย</div>
        <button class="btn secondary right" id="addSubBtn">เพิ่มหัวข้อย่อย</button>
      </div>
      <div id="subsList" class="grid" style="margin-top:8px"></div>
    </div>
  </section>

  <section id="subView" class="grid" style="display:none">
    <div class="card">
      <div class="row" style="align-items:center">
        <button class="btn ghost" id="backMainBtn">← กลับหัวข้อหลัก</button>
        <h2 id="subTitle" style="margin:0"></h2>
        <span class="right small" id="subLive"></span>
      </div>
      <div class="spacer"></div>
      <div class="grid">
        <div class="card">
          <div class="row">
            <div style="flex:1"><label>Max points</label><input type="number" id="subMaxPoints" min="1" step="1"></div>
            <div style="flex:1"><label>จำนวนช่อง (segments)</label><input type="number" id="subSegments" min="0" step="1"></div>
            <div style="flex:1"><label>1 stat = กี่ points</label><input type="number" id="subPointsPerStat" min="1" step="1"></div>
          </div>
          <div class="spacer"></div>
          <div>
            <label>ตัวอย่างหลอด (อิงค่าปัจจุบัน + การเปลี่ยนแปลงที่ยังไม่บันทึก)</label>
            <div class="bar" id="subPreviewBar"><span style="width:0%"></span><div class="ticks" id="subPreviewTicks"></div></div>
            <div class="small" id="subPreviewMeta"></div>
            <div class="seg-indicator" id="subSegIndicator"></div>
          </div>
        </div>

        <div class="card">
          <div class="row" style="align-items:center">
            <h3 style="margin:0">Quests</h3>
            <button class="btn secondary right" id="addQuestBtn">เพิ่ม Quest</button>
          </div>

          <!-- ฟอร์มเพิ่มเควส -->
          <div id="questForm" class="quest-form" style="display:none">
            <div style="flex:2">
              <label>ชื่อเควส</label>
              <input type="text" id="questName" placeholder="เช่น ทำสมาธิ 10 นาที">
            </div>
            <div style="flex:1">
              <label>คะแนนต่อครั้ง (+/- ได้)</label>
              <input type="number" id="questPoints" step="1" value="5">
            </div>
            <div class="row" style="gap:6px">
              <button class="btn success" id="questSaveBtn">เพิ่ม</button>
              <button class="btn ghost" id="questCancelBtn">ยกเลิก</button>
            </div>
          </div>

          <div id="questsList" class="grid" style="margin-top:8px"></div>

          <div id="pendingList" style="display:none"></div>

          <div class="hr"></div>
          <div class="row">
            <button class="btn success" id="applyStageBtn">Save (บันทึกการเปลี่ยนแปลง)</button>
            <button class="btn ghost" id="discardStageBtn">ยกเลิกการเปลี่ยนแปลง</button>
          </div>
        </div>

        <div class="card">
          <div class="row" style="align-items:center">
            <h3 style="margin:0">ประวัติ</h3>
            <button class="btn secondary right" id="exportCsvBtn">ส่งออก CSV</button>
          </div>
          <table id="historyTable">
            <colgroup>
              <col style="width:170px"><col style="width:auto"><col style="width:110px">
            </colgroup>
            <thead><tr><th>วัน/เวลา</th><th>รายละเอียด</th><th>Δ points</th></tr></thead>
            <tbody></tbody>
          </table>
        </div>

        <div class="card"><button class="btn danger" id="deleteSubBtn">ลบหัวข้อย่อยนี้</button></div>
      </div>
    </div>
  </section>
</div>

<!-- ===== Modal: เพิ่มหมายเหตุ + ประวัติ ===== -->
<div id="noteModal" class="modal" aria-hidden="true">
  <div class="dialog" role="dialog" aria-modal="true">
    <header>
      <div>
        <div class="small" id="nmPath">หัวข้อหลัก › ย่อย › เควส</div>
        <div style="font-weight:700" id="nmTitle"></div>
      </div>
      <button class="btn ghost" id="nmClose">ปิด</button>
    </header>
    <div class="content">
      <div>
        <label id="nmLabel">ใส่หมายเหตุ (ไม่บังคับ)</label>
        <textarea id="nmInput" placeholder="เช่น ทำตามแผนได้ครบ 3 ขั้น"></textarea>
      </div>
      <div class="hist">
        <h4>ประวัติเควสนี้</h4>
        <div id="nmHist"></div>
      </div>
    </div>
    <footer>
      <span class="small" id="nmDelta"></span>
      <button class="btn ghost" id="nmCancel">ยกเลิก</button>
      <button class="btn success" id="nmSave">บันทึกเข้า “ค้างบันทึก”</button>
    </footer>
  </div>
</div>

<script>
/* ===== Storage & Model ===== */
const DB_KEY='psd_v2_nested';
function nowISO(){return new Date().toISOString();}
function uid(){return 'id'+Math.random().toString(36).slice(2,10);}
function loadDB(){try{const raw=localStorage.getItem(DB_KEY);return raw?JSON.parse(raw):{version:2,topics:[]}}catch(e){return {version:2,topics:[]}}}
function saveDB(db){localStorage.setItem(DB_KEY, JSON.stringify(db));}
let db=loadDB();

function ensureMain(t){ if(!t.subs) t.subs=[]; return t; }
function ensureSub(s){
  if(!s.settings) s.settings={};
  s.settings.maxPoints=Math.max(1,Number(s.settings.maxPoints||100));
  s.settings.segments=Math.max(0,Number(s.settings.segments||0));
  s.settings.pointsPerStat=Math.max(1,Number(s.settings.pointsPerStat||10));
  if(!s.transactions) s.transactions=[];
  if(!s.quests) s.quests=[];
  return s;
}
function computeSub(sub){
  const total=(sub.transactions||[]).reduce((a,b)=>a+Number(b.delta||0),0);
  const mp=Number(sub.settings.maxPoints), pps=Number(sub.settings.pointsPerStat);
  const stats=Math.floor(total/pps);
  const percent=mp?(total/mp)*100:0;
  return {total,stats,percent};
}
function computeMainPercent(main){
  const subs=(main.subs||[]).map(ensureSub);
  if(!subs.length) return 0;
  let sum=0; subs.forEach(s=>sum+=computeSub(s).percent);
  return sum/subs.length;
}
function formatNumber(n){return (Math.round(n*100)/100).toString();}
function download(filename,text){
  const a=document.createElement('a');
  a.href=URL.createObjectURL(new Blob([text],{type:'text/plain'}));
  a.download=filename; document.body.appendChild(a); a.click(); a.remove();
  setTimeout(()=>URL.revokeObjectURL(a.href),1000);
}

/* ===== Circle ===== */
function updateCircle(){
  const c=document.getElementById('progressCircle'), t=document.getElementById('circleText');
  if(!db.topics.length){ c.style.strokeDashoffset=282.743; t.textContent='0%'; return; }
  const avg=db.topics.reduce((s,x)=>s+computeMainPercent(x),0)/db.topics.length;
  const vis=Math.max(0,Math.min(100,avg));
  c.style.strokeDashoffset=282.743-(282.743*(vis/100)); t.textContent=Math.round(avg)+'%';
}

/* ===== Radar ===== */
function drawRadarOn(canvasId, labels, percents, subtitle){
  const cvs=document.getElementById(canvasId); if(!cvs) return;
  const ctx=cvs.getContext('2d');
  const cssW=(cvs.offsetWidth||cvs.clientWidth||700);
  const cssH=labels.length?300:140;
  const DPR=Math.max(1,window.devicePixelRatio||1);
  cvs.width=cssW*DPR; cvs.height=cssH*DPR; cvs.style.height=cssH+'px';
  ctx.setTransform(DPR,0,0,DPR,0,0);
  ctx.clearRect(0,0,cssW,cssH);

  if(!labels.length){
    ctx.fillStyle='#6b7280'; ctx.font='16px system-ui,-apple-system,Arial';
    ctx.textAlign='center'; ctx.fillText('ยังไม่มีหัวข้อหลัก — กด “เพิ่มหัวข้อหลัก” ด้านบน', cssW/2, cssH/2);
    return;
  }

  const N=labels.length;
  const vals=percents.map(v=>Math.max(0,Math.min(100,v)));
  const cx=cssW/2, cy=cssH/2+6, maxR=Math.min(cssW,cssH)*0.36, steps=5;

  ctx.lineWidth=1;
  for(let s=1;s<=steps;s++){
    const r=(s/steps)*maxR; ctx.beginPath();
    for(let i=0;i<N;i++){
      const a=(i/N)*Math.PI*2 - Math.PI/2;
      const x=cx+r*Math.cos(a), y=cy+r*Math.sin(a);
      i?ctx.lineTo(x,y):ctx.moveTo(x,y);
    }
    ctx.closePath(); ctx.strokeStyle='#e5e7eb'; ctx.stroke();
  }
  ctx.font='12px system-ui,-apple-system,Arial'; ctx.fillStyle='#0f1220';
  ctx.textAlign='center'; ctx.textBaseline='middle';
  for(let i=0;i<N;i++){
    const a2=(i/N)*Math.PI*2 - Math.PI/2;
    const x2=cx+maxR*Math.cos(a2), y2=cy+maxR*Math.sin(a2);
    ctx.beginPath(); ctx.moveTo(cx,cy); ctx.lineTo(x2,y2); ctx.strokeStyle='#e5e7eb'; ctx.stroke();
    const lx=cx+(maxR+16)*Math.cos(a2), ly=cy+(maxR+16)*Math.sin(a2);
    ctx.fillText(labels[i], lx, ly);
  }
  const pts=vals.map((v,i)=>{ const a=(i/N)*Math.PI*2 - Math.PI/2, r=(v/100)*maxR; return {x:cx+r*Math.cos(a), y:cy+r*Math.sin(a)}; });
  ctx.beginPath(); pts.forEach((p,i)=>i?ctx.lineTo(p.x,p.y):ctx.moveTo(p.x,p.y)); ctx.closePath();
  ctx.fillStyle='rgba(37,99,235,.18)'; ctx.strokeStyle='#2563eb'; ctx.lineWidth=2; ctx.fill(); ctx.stroke();
  ctx.fillStyle='#2563eb'; pts.forEach(p=>{ ctx.beginPath(); ctx.arc(p.x,p.y,3,0,Math.PI*2); ctx.fill(); });
  if(subtitle){ ctx.fillStyle='#6b7280'; ctx.font='12px system-ui,-apple-system,Arial'; ctx.textAlign='left'; ctx.fillText(subtitle,12,16); }
}

/* ===== Views ===== */
const homeView=document.getElementById('homeView');
const mainView=document.getElementById('mainView');
const subView=document.getElementById('subView');
const topicsList=document.getElementById('topicsList');

const backHomeBtn=document.getElementById('backHomeBtn');
const mainTitle=document.getElementById('mainTitle');
const mainSummary=document.getElementById('mainSummary');
const subsList=document.getElementById('subsList');
const addSubBtn=document.getElementById('addSubBtn');
const deleteMainBtn=document.getElementById('deleteMainBtn');

const backMainBtn=document.getElementById('backMainBtn');
const subTitle=document.getElementById('subTitle');
const subLive=document.getElementById('subLive');
const subMaxPoints=document.getElementById('subMaxPoints');
const subSegments=document.getElementById('subSegments');
const subPointsPerStat=document.getElementById('subPointsPerStat');
const subPreviewBar=document.getElementById('subPreviewBar');
const subPreviewTicks=document.getElementById('subPreviewTicks');
const subPreviewMeta=document.getElementById('subPreviewMeta');
const subSegIndicator=document.getElementById('subSegIndicator');
const questsList=document.getElementById('questsList');
const pendingList=document.getElementById('pendingList');
const historyTableBody=document.querySelector('#historyTable tbody');
const exportCsvBtn=document.getElementById('exportCsvBtn');
const applyStageBtn=document.getElementById('applyStageBtn');
const discardStageBtn=document.getElementById('discardStageBtn');
const deleteSubBtn=document.getElementById('deleteSubBtn');

/* ฟอร์มเพิ่มเควส */
const addQuestBtn=document.getElementById('addQuestBtn');
const questForm=document.getElementById('questForm');
const questName=document.getElementById('questName');
const questPoints=document.getElementById('questPoints');
const questSaveBtn=document.getElementById('questSaveBtn');
const questCancelBtn=document.getElementById('questCancelBtn');

/* Modal note */
const noteModal=document.getElementById('noteModal');
const nmPath=document.getElementById('nmPath');
const nmTitle=document.getElementById('nmTitle');
const nmLabel=document.getElementById('nmLabel');
const nmInput=document.getElementById('nmInput');
const nmHist=document.getElementById('nmHist');
const nmDelta=document.getElementById('nmDelta');
const nmClose=document.getElementById('nmClose');
const nmCancel=document.getElementById('nmCancel');
const nmSave=document.getElementById('nmSave');

let currentMainId=null, currentSubId=null;
/* stage เก็บทีละเหตุการณ์ พร้อม questId */
let stage={settings:null,events:[]}; // {note, delta, questId, questTitle}
function stageTotalDelta(){ return stage.events.reduce((s,e)=>s+e.delta,0); }

/* ---------- Home ---------- */
function renderHome(){
  homeView.style.display='grid'; mainView.style.display='none'; subView.style.display='none';
  topicsList.innerHTML='';
  if(!db.topics.length){
    const card=document.createElement('div'); card.className='card';
    card.innerHTML='<div class="small">ยังไม่มีหัวข้อหลัก กด “เพิ่มหัวข้อหลัก” ด้านบน</div>';
    topicsList.appendChild(card);
  }else{
    db.topics.forEach(t=>{
      ensureMain(t);
      const percent=computeMainPercent(t);
      const card=document.createElement('div'); card.className='card topic';
      card.innerHTML=
        '<div class="topic-name">'+t.name+'</div>'+
        '<div class="bar '+(percent>100?'overflow':'')+'" style="flex:1"><span style="width:'+Math.min(percent,200)+'%"></span></div>'+
        '<div class="small" style="width:160px;text-align:right">ค่าเฉลี่ย: '+formatNumber(percent)+'% • '+t.subs.length+' ย่อย</div>'+
        '<button class="btn ghost-danger del-main" title="ลบหัวข้อหลัก">ลบ</button>';
      card.addEventListener('click',()=>openMain(t.id));
      card.querySelector('.del-main').addEventListener('click',e=>{
        e.stopPropagation();
        if(!confirm('ลบ "'+t.name+'" พร้อมหัวข้อย่อยและประวัติทั้งหมด?')) return;
        db.topics=db.topics.filter(x=>x.id!==t.id);
        saveDB(db); renderHome();
      });
      topicsList.appendChild(card);
    });
  }
  drawRadarOn('radarCanvas', db.topics.map(t=>t.name), db.topics.map(t=>computeMainPercent(t)), 'สเกล: 0–100% (ค่าเฉลี่ยย่อยแต่ละหัวข้อหลัก)');
  updateCircle();
}

/* ---------- Main ---------- */
function openMain(id){
  currentMainId=id; currentSubId=null;
  const main=db.topics.find(t=>t.id===id); ensureMain(main);
  homeView.style.display='none'; mainView.style.display='grid'; subView.style.display='none';
  mainTitle.textContent=main.name;
  mainSummary.textContent='ค่าเฉลี่ยย่อยทั้งหมด: '+formatNumber(computeMainPercent(main))+'% • '+main.subs.length+' ย่อย';
  subsList.innerHTML='';
  if(!main.subs.length){
    const empty=document.createElement('div'); empty.className='small'; empty.textContent='ยังไม่มีหัวข้อย่อย';
    subsList.appendChild(empty);
  }else{
    main.subs.forEach(sub=>{
      ensureSub(sub);
      const {percent}=computeSub(sub);
      const el=document.createElement('div'); el.className='card topic';
      el.innerHTML=
        '<div class="topic-name">'+sub.name+'</div>'+
        '<div class="bar '+(percent>100?'overflow':'')+'" style="flex:1"><span style="width:'+Math.min(percent,200)+'%"></span></div>'+
        '<div class="small" style="width:120px;text-align:right">'+formatNumber(percent)+'%</div>';
      el.addEventListener('click',()=>openSub(sub.id));
      subsList.appendChild(el);
    });
  }
  drawRadarOn('topicRadarCanvas', main.subs.map(s=>s.name), main.subs.map(s=>computeSub(s).percent), 'สเกล: 0–100% ของแต่ละย่อย');
}
backHomeBtn.addEventListener('click',()=>{ currentMainId=null; renderHome(); });
addSubBtn.addEventListener('click', ()=>{
  const main=db.topics.find(t=>t.id===currentMainId); if(!main) return;
  const name=prompt('ชื่อหัวข้อย่อย (เช่น ER, EF)'); if(!name) return;
  main.subs.push(ensureSub({id:uid(),name:name.trim(),settings:{maxPoints:100,segments:5,pointsPerStat:10},transactions:[],quests:[
    {id:uid(),title:'งานสำเร็จเล็ก',points:5},{id:uid(),title:'งานสำเร็จใหญ่',points:10}
  ]}));
  saveDB(db); openMain(currentMainId);
});
deleteMainBtn.addEventListener('click',()=>{
  if(!currentMainId) return;
  const i=db.topics.findIndex(t=>t.id===currentMainId); if(i<0) return;
  const name=db.topics[i].name||'หัวข้อหลักนี้';
  if(!confirm('ลบ "'+name+'" พร้อมหัวข้อย่อยและประวัติทั้งหมด?')) return;
  db.topics.splice(i,1); saveDB(db); currentMainId=null; renderHome();
});

/* ---------- Sub ---------- */
function openSub(subId){
  currentSubId=subId;
  const main=db.topics.find(t=>t.id===currentMainId);
  const sub=main.subs.find(s=>s.id===subId); ensureSub(sub);
  homeView.style.display='none'; mainView.style.display='none'; subView.style.display='grid';
  subTitle.textContent=main.name+' › '+sub.name;
  subMaxPoints.value=sub.settings.maxPoints;
  subSegments.value=sub.settings.segments;
  subPointsPerStat.value=sub.settings.pointsPerStat;
  stage={settings:null,events:[]};
  [subMaxPoints,subSegments,subPointsPerStat].forEach(inp=>{
    inp.oninput=()=>{ stage.settings={maxPoints:+subMaxPoints.value,segments:+subSegments.value,pointsPerStat:+subPointsPerStat.value}; renderSubPreview(); };
  });
  questForm.style.display='none'; questName.value=''; questPoints.value='5';
  renderSubPreview(); renderQuests(); renderHistory(); renderPending();
  subLive.textContent='ค่า ณ ปัจจุบัน: '+formatNumber(computeSub(sub).percent)+'%';
}
backMainBtn.addEventListener('click',()=>openMain(currentMainId));

function renderSubPreview(){
  const main=db.topics.find(t=>t.id===currentMainId);
  const sub=main.subs.find(s=>s.id===currentSubId); ensureSub(sub);
  const s=stage.settings||sub.settings;
  const base=computeSub(sub);
  const totalWithStage=base.total+stageTotalDelta();
  const percent=s.maxPoints?(totalWithStage/s.maxPoints)*100:0;
  subPreviewBar.className='bar'+(percent>100?' overflow':'');
  subPreviewBar.querySelector('span').style.width=Math.min(percent,200)+'%';
  subPreviewTicks.innerHTML='';
  for(let i=1;i<Number(s.segments||0);i++){
    const tk=document.createElement('div'); tk.className='tick'; tk.style.left=(i*100/Number(s.segments))+'%';
    subPreviewTicks.appendChild(tk);
  }
  subSegIndicator.innerHTML='';
  const stats=Math.floor(totalWithStage/Number(s.pointsPerStat||10));
  for(let i=0;i<Number(s.segments||0);i++){
    const seg=document.createElement('div'); seg.className='seg'+(i<stats?' filled':''); subSegIndicator.appendChild(seg);
  }
  subPreviewMeta.textContent='หลังบันทึก: '+formatNumber(totalWithStage)+' pts ('+formatNumber(percent)+'%) • รายการค้าง '+stage.events.length+' รายการ • รวม '+(stageTotalDelta()>=0?'+':'')+formatNumber(stageTotalDelta())+' pts';
}

/* รายการค้างบันทึก */
function renderPending(){
  if(!stage.events.length){ pendingList.style.display='none'; pendingList.innerHTML=''; return; }
  pendingList.style.display='block';
  let html='<div class="small" style="margin-bottom:6px">รายการค้างบันทึก</div>';
  stage.events.forEach((ev,idx)=>{
    html+= `<div class="item"><div class="delta">${ev.delta>0?'+':''}${ev.delta} pts</div><div style="flex:1">${ev.note}</div><button class="btn ghost" data-i="${idx}">ยกเลิก</button></div>`;
  });
  pendingList.innerHTML=html;
  pendingList.querySelectorAll('button').forEach(b=>{
    b.onclick=()=>{ const i=+b.getAttribute('data-i'); stage.events.splice(i,1); renderPending(); renderSubPreview(); };
  });
}

/* ---- Modal helper: เปิด modal พร้อมประวัติของเควส ---- */
let modalQuest=null, modalDelta=0, modalAction='plus';
function openNoteModal(action, quest){
  modalQuest=quest; modalAction=action; modalDelta = (action==='plus'? +quest.points : -quest.points);
  const main=db.topics.find(t=>t.id===currentMainId);
  const sub=main.subs.find(s=>s.id===currentSubId);
  nmPath.textContent = `${main.name} › ${sub.name}`;
  nmTitle.textContent = `${quest.title}`;
  nmLabel.textContent = action==='plus' ? 'ใส่หมายเหตุ (ไม่บังคับ) — เพิ่มคะแนน' : 'ใส่หมายเหตุ (ไม่บังคับ) — ลดคะแนน';
  nmDelta.textContent = `ผลกระทบครั้งนี้: ${modalDelta>0?'+':''}${modalDelta} pts`;
  nmInput.value='';
  // ----- ประวัติเควสนี้ -----
  const hist = (sub.transactions||[])
    .filter(r => r.questId ? r.questId===quest.id : (r.note||'').includes(quest.title))
    .slice(-30) // เอาใหม่สุด 30 รายการพออ่านสบาย
    .reverse();
  if(!hist.length){
    nmHist.innerHTML = '<div class="small">ยังไม่มีประวัติของเควสนี้</div>';
  }else{
    nmHist.innerHTML = hist.map(r=>{
      const d=new Date(r.time);
      return `<div class="entry"><div class="small">${d.toLocaleString()} • ${r.delta>0?'+':''}${r.delta} pts</div><div>${(r.note||'')}</div></div>`;
    }).join('');
  }
  noteModal.style.display='flex';
  nmInput.focus();
}
function closeNoteModal(){ noteModal.style.display='none'; }

/* ปุ่ม modal */
[nmClose,nmCancel].forEach(b=>b.addEventListener('click',closeNoteModal));
nmSave.addEventListener('click',()=>{
  if(!modalQuest) return;
  const txt = nmInput.value.trim();
  const full = (modalAction==='plus'
                 ? `✔ ${modalQuest.title} (+${modalQuest.points})`
                 : `✖ ${modalQuest.title} (-${modalQuest.points})`)
               + (txt? ' — '+txt : '');
  stage.events.push({note:full, delta:modalDelta, questId:modalQuest.id, questTitle:modalQuest.title});
  closeNoteModal();
  renderSubPreview(); renderPending();
});
/* ปิด modal เมื่อคลิกนอกกล่อง */
noteModal.addEventListener('click',e=>{ if(e.target===noteModal) closeNoteModal(); });

/* ----- Quests list + Add ----- */
function renderQuests(){
  const main=db.topics.find(t=>t.id===currentMainId);
  const sub=main.subs.find(s=>s.id===currentSubId); ensureSub(sub);
  questsList.innerHTML='';
  if(!sub.quests.length){
    const empty=document.createElement('div'); empty.className='small'; empty.textContent='ยังไม่มีเควส'; questsList.appendChild(empty);
  }
  sub.quests.forEach(q=>{
    const row=document.createElement('div'); row.className='row'; row.style.alignItems='center';
    row.innerHTML=
      '<div style="flex:1"><div style="font-weight:600">'+q.title+
      '</div><div class="small">'+(q.points>0?'+':'')+q.points+' pts ต่อครั้ง</div></div>'+
      '<div class="wrap">'+
      '<button class="btn success">เขียว +</button>'+
      '<button class="btn danger">แดง −</button>'+
      '<button class="btn secondary">แก้ไข</button>'+
      '<button class="btn ghost">ลบ</button></div>';
    const [bPlus,bMinus,bEdit,bDel]=row.querySelectorAll('button');
    bPlus.onclick = ()=> openNoteModal('plus', q);
    bMinus.onclick= ()=> openNoteModal('minus', q);
    bEdit.onclick  = ()=>{
      const title=prompt('แก้ชื่อเควส',q.title); if(title===null) return;
      let pts=prompt('แก้จำนวนคะแนน (+/- ได้)',q.points); if(pts===null) return;
      pts=Number(pts); if(!isFinite(pts)) return alert('กรุณาใส่ตัวเลข');
      q.title=(title||'').trim()||q.title; q.points=pts; saveDB(db); renderQuests();
    };
    bDel.onclick   = ()=>{ if(!confirm('ลบเควสนี้?')) return; sub.quests=sub.quests.filter(x=>x.id!==q.id); saveDB(db); renderQuests(); };
    questsList.appendChild(row);
  });
}

/* ปุ่ม “เพิ่ม Quest” */
addQuestBtn.addEventListener('click',()=>{
  questForm.style.display = questForm.style.display==='none' ? 'flex' : 'none';
  if(questForm.style.display==='flex') questName.focus();
});
questCancelBtn.addEventListener('click',()=>{ questName.value=''; questPoints.value='5'; questForm.style.display='none'; });
questSaveBtn.addEventListener('click',()=>{
  const name=(questName.value||'').trim();
  let pts=Number(questPoints.value);
  if(!name) return alert('กรุณาใส่ชื่อเควส');
  if(!isFinite(pts)) return alert('กรุณาใส่ตัวเลขคะแนน');
  const main=db.topics.find(t=>t.id===currentMainId);
  const sub=main.subs.find(s=>s.id===currentSubId); ensureSub(sub);
  sub.quests.push({id:uid(), title:name, points:pts});
  saveDB(db);
  questName.value=''; questPoints.value='5'; questForm.style.display='none';
  renderQuests();
});

/* บันทึก / ยกเลิก */
applyStageBtn.addEventListener('click',()=>{
  const main=db.topics.find(t=>t.id===currentMainId);
  const sub=main.subs.find(s=>s.id===currentSubId); ensureSub(sub);
  if(stage.settings) sub.settings={...sub.settings,...stage.settings};
  if(stage.events.length){
    stage.events.forEach(ev=>{
      sub.transactions.push({time:nowISO(),note:ev.note,delta:ev.delta,questId:ev.questId,questTitle:ev.questTitle});
    });
  }
  saveDB(db);
  stage={settings:null,events:[]};
  renderSubPreview(); renderHistory(); renderPending(); openMain(currentMainId);
  alert('บันทึกแล้ว');
});
discardStageBtn.addEventListener('click',()=>{ stage={settings:null,events:[]}; renderSubPreview(); renderPending(); });
deleteSubBtn.addEventListener('click',()=>{
  if(!confirm('ลบหัวข้อย่อยนี้และข้อมูลทั้งหมด?')) return;
  const main=db.topics.find(t=>t.id===currentMainId);
  main.subs=main.subs.filter(s=>s.id!==currentSubId); saveDB(db); openMain(currentMainId);
});

/* ประวัติ */
function renderHistory(){
  const main=db.topics.find(t=>t.id===currentMainId);
  const sub=main.subs.find(s=>s.id===currentSubId); ensureSub(sub);
  historyTableBody.innerHTML='';
  (sub.transactions||[]).slice().reverse().forEach(r=>{
    const tr=document.createElement('tr');
    const d=new Date(r.time);
    tr.innerHTML='<td>'+d.toLocaleString()+'</td><td class="note-cell">'+(r.note||'')+'</td><td>'+(r.delta>0?'+':'')+r.delta+'</td>';
    historyTableBody.appendChild(tr);
  });
}
exportCsvBtn.addEventListener('click',()=>{
  const main=db.topics.find(t=>t.id===currentMainId);
  const sub=main.subs.find(s=>s.id===currentSubId);
  const rows=[['time','note','delta','questId','questTitle']].concat((sub.transactions||[]).map(r=>[r.time,r.note||'',r.delta,r.questId||'',r.questTitle||'']));
  const csv=rows.map(r=>r.map(v=>'"'+String(v).replace(/"/g,'""')+'"').join(',')).join('\n');
  download(main.name.replace(/\s+/g,'_')+'__'+sub.name.replace(/\s+/g,'_')+'_history.csv', csv);
});

/* ===== Add / Export ===== */
document.getElementById('addTopicBtn').addEventListener('click',()=>{
  const name=prompt('ชื่อหัวข้อหลัก (เช่น EQ)'); if(!name) return;
  db.topics.push(ensureMain({id:uid(),name:name.trim(),subs:[]}));
  saveDB(db); renderHome();
});
document.getElementById('exportAllBtn').addEventListener('click',()=>{
  download('progress_backup_nested.json', JSON.stringify(db,null,2));
});

/* ===== Init ===== */
function start(){
  db.topics.forEach(ensureMain);
  renderHome();
  window.addEventListener('resize', ()=>{
    drawRadarOn('radarCanvas', db.topics.map(t=>t.name), db.topics.map(t=>computeMainPercent(t)), 'สเกล: 0–100% (ค่าเฉลี่ยย่อยแต่ละหัวข้อหลัก)');
    if(currentMainId){
      const m=db.topics.find(t=>t.id===currentMainId)||{subs:[]};
      drawRadarOn('topicRadarCanvas', m.subs.map(s=>s.name), m.subs.map(s=>computeSub(s).percent), 'สเกล: 0–100% ของแต่ละย่อย');
    }
  });
}
window.addEventListener('DOMContentLoaded', start);
</script>
</body>
</html>
