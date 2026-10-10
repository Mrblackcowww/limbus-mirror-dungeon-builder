<!doctype html>
<html lang="ko">
<head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1">
<title>거던 빌더 | Mirror Dungeon Build Simulator</title>
<style>
:root{--bg:#111217;--panel:#1a1c24;--panel2:#222530;--line:#363a49;--text:#f0f1f5;--muted:#a4a8b8;--gold:#d8b66a;--accent:#aa8bff;--danger:#e87979;--good:#8dd6a6}
*{box-sizing:border-box}body{margin:0;background:radial-gradient(ellipse at top,#20212b 0,#111217 55%);color:var(--text);font:15px/1.5 system-ui,-apple-system,"Noto Sans KR",sans-serif}
header{padding:25px max(18px,calc((100% - 1400px)/2));border-bottom:1px solid var(--line);background:#111217d9;position:sticky;top:0;z-index:5;backdrop-filter:blur(12px)}
.brand{display:flex;align-items:center;gap:12px}.sigil{width:42px;height:42px;display:grid;place-items:center;border:1px solid var(--gold);color:var(--gold);font-size:22px;transform:rotate(45deg)}.sigil span{transform:rotate(-45deg)}h1{font-size:22px;margin:0;letter-spacing:.02em}.subtitle{color:var(--muted);font-size:12px}
main{max-width:1400px;margin:0 auto;padding:22px 18px 60px}.notice{padding:12px 15px;background:#342b1c;border:1px solid #695635;color:#f2d9a4;border-radius:10px;margin-bottom:18px;font-size:13px}
.toolbar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:18px}.btn,button,select,input{font:inherit}.btn,button{cursor:pointer;border:1px solid var(--line);background:var(--panel2);color:var(--text);padding:9px 13px;border-radius:8px}.btn.primary{background:var(--gold);border-color:var(--gold);color:#17140e;font-weight:700}.btn:hover,button:hover{border-color:var(--gold)}.layout{display:grid;grid-template-columns:minmax(0,1.2fr) minmax(340px,.8fr);gap:18px}.panel{background:linear-gradient(155deg,#1c1e27,#171820);border:1px solid var(--line);border-radius:13px;padding:17px;min-width:0}.panel h2{font-size:16px;margin:0 0 12px;display:flex;align-items:center;justify-content:space-between}.panel h3{font-size:14px;margin:16px 0 8px;color:#e4d3a5}.muted{color:var(--muted)}.small{font-size:12px}.filters{display:flex;gap:7px;flex-wrap:wrap;margin-bottom:12px}.pill{border:1px solid var(--line);border-radius:999px;padding:5px 10px;background:#191b23;color:var(--muted);cursor:pointer;font-size:12px}.pill.active{color:#17140e;background:var(--gold);border-color:var(--gold)}.cards{display:grid;grid-template-columns:repeat(auto-fill,minmax(185px,1fr));gap:9px}.idcard,.giftcard{border:1px solid var(--line);background:#20222c;border-radius:10px;padding:11px;display:flex;flex-direction:column;gap:7px}.idcard.selected{border-color:var(--gold);box-shadow:inset 0 0 0 1px #d8b66a55}.cardtop{display:flex;align-items:start;justify-content:space-between;gap:8px}.cardname{font-weight:650}.tag{font-size:11px;border-radius:5px;padding:2px 6px;background:#303342;color:#d8dbea;white-space:nowrap}.keywordline{display:flex;gap:5px;flex-wrap:wrap}.kwtag{font-size:11px;border-radius:5px;padding:2px 6px;border:1px solid color-mix(in srgb,var(--kw) 55%,transparent);color:var(--kw);background:color-mix(in srgb,var(--kw) 10%,transparent)}.cardactions{display:flex;gap:6px;margin-top:auto}.cardactions button{padding:6px 8px;font-size:12px;flex:1}.selectedlist{display:flex;flex-direction:column;gap:7px}.partyrow{display:flex;align-items:center;gap:9px;padding:9px;border:1px solid var(--line);background:#20222b;border-radius:8px}.partyrow .grow{flex:1;min-width:0}.partyrow .grow strong{display:block;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.mini-btn{padding:4px 8px!important}.metricgrid{display:grid;grid-template-columns:repeat(2,1fr);gap:8px}.metric{background:#20222b;border:1px solid var(--line);border-radius:9px;padding:10px}.metric strong{display:block;font-size:22px}.barrow{display:grid;grid-template-columns:58px 1fr 28px;align-items:center;gap:8px;margin:9px 0;font-size:12px}.bar{height:8px;background:#30323d;border-radius:20px;overflow:hidden}.bar>span{height:100%;display:block;border-radius:20px}.giftrow{display:grid;grid-template-columns:1fr auto;gap:8px;align-items:center;padding:9px 0;border-bottom:1px solid #30323d}.giftrow:last-child{border-bottom:0}.giftrow strong{font-size:13px}.giftrow .sub{font-size:11px;color:var(--muted)}.select{width:100%;background:#20222b;color:var(--text);border:1px solid var(--line);border-radius:7px;padding:8px}.row{display:flex;gap:8px;align-items:center}.row>*{min-width:0}.row input{flex:1}.textinput{background:#20222b;border:1px solid var(--line);color:var(--text);border-radius:7px;padding:9px;min-width:0}.sectiongap{margin-top:17px}.empty{padding:20px;text-align:center;border:1px dashed var(--line);border-radius:9px;color:var(--muted)}.status{font-size:12px;color:var(--good);min-height:18px}.foot{margin-top:22px;color:var(--muted);font-size:12px}.two-col{display:grid;grid-template-columns:1fr 1fr;gap:10px}.hidden{display:none!important}
@media(max-width:900px){.layout{grid-template-columns:1fr}.rightcol{display:grid;grid-template-columns:1fr 1fr;gap:14px}.rightcol>.panel{margin:0}.rightcol .wide{grid-column:1/-1}}
@media(max-width:600px){header{position:static;padding:16px}.layout{grid-template-columns:1fr}.rightcol{display:flex;flex-direction:column}.cards{grid-template-columns:1fr 1fr}.panel{padding:12px}.cards .idcard{padding:9px}.cardname{font-size:13px}.toolbar .btn{flex:1}.two-col{grid-template-columns:1fr}}
</style>
</head>
<body>
<header><div class="brand"><div class="sigil"><span>Σ</span></div><div><h1>거던 빌더</h1><div class="subtitle">MIRROR DUNGEON · BUILD LAB / PROTOTYPE 0.1</div></div></div></header>
<main>
<div class="notice">프로토타입 안내: 현재 포함된 인격·에고 기프트는 기능 시연용 샘플 데이터입니다. 게임 내 실제 효과·합성 레시피가 검증된 완전한 데이터베이스가 아니므로, 추천 점수는 등록된 키워드 가중치에 따른 참고값입니다.</div>
<div class="toolbar">
<button class="btn primary" id="saveBtn">빌드 저장</button><button class="btn" id="loadBtn">저장 빌드 불러오기</button><button class="btn" id="exportBtn">JSON 내보내기</button><button class="btn" id="importBtn">JSON 가져오기</button><button class="btn" id="clearBtn">초기화</button>
<input id="importFile" type="file" accept=".json,application/json" class="hidden">
<span id="status" class="status" style="align-self:center"></span>
</div>
<div class="layout">
<section class="panel">
<h2>01 / 키워드 & 인격 선택 <span class="tag" id="partyCount">0명 편성</span></h2>
<div class="filters" id="keywordFilters"></div>
<div class="row" style="margin-bottom:12px"><input id="search" class="textinput" placeholder="인격명 또는 수감자 검색…"><select id="sort" class="select" style="max-width:150px"><option value="synergy">시너지 순</option><option value="name">이름 순</option></select></div>
<div class="cards" id="identityCards"></div>
<h3 class="sectiongap">편성 순서</h3><div id="partyList" class="selectedlist"></div>
<div class="sectiongap"><button class="btn" id="clearParty">편성 비우기</button></div>
</section>
<div class="rightcol">
<section class="panel">
<h2>02 / 빌드 진단</h2>
<div class="metricgrid"><div class="metric"><span class="muted small">편성 인원</span><strong id="metricMembers">0</strong></div><div class="metric"><span class="muted small">주력 키워드</span><strong id="metricMain">—</strong></div></div>
<h3>키워드 집중도</h3><div id="keywordBars"></div><p class="muted small">인격 데이터에 입력된 키워드 가중치를 합산합니다. 전투 성능의 실측 예측값은 아닙니다.</p>
</section>
<section class="panel">
<h2>03 / 추천 기프트</h2><div class="filters" id="giftFilters"></div><div id="giftRecommendations"></div>
</section>
<section class="panel wide">
<h2>04 / 보유 기프트 & 강화</h2>
<div class="row"><select id="giftSelect" class="select"></select><button id="addGift" class="btn">추가</button></div>
<div id="ownedGifts" class="sectiongap"></div>
<h3>강화·합성 경로</h3><div id="recipeView" class="muted small">기프트를 선택하면 강화 경로와 예시 레시피를 확인할 수 있습니다.</div>
</section>
<section class="panel wide">
<h2>05 / 저장된 빌드</h2><div id="savedBuilds"></div>
</section>
</div>
</div>
<div class="foot">데이터는 브라우저의 localStorage에 저장됩니다. 다른 기기/브라우저로 옮기려면 JSON 내보내기를 사용하세요. 샘플 데이터는 data/ 폴더에서 확장할 수 있습니다.</div>
</main>
<script>
const KEYWORDS = [
{id:"bleed",name:"출혈",color:"#e05b65"},{id:"rupture",name:"파열",color:"#78c58b"},
{id:"sinking",name:"침잠",color:"#6ea8e8"},{id:"burn",name:"화상",color:"#ed9c52"},
{id:"poise",name:"호흡",color:"#c0a0f5"},{id:"charge",name:"충전",color:"#e8cc61"},
{id:"tremor",name:"진동",color:"#dd8bc6"}
];
const IDENTITIES = [
{id:"bleed_rodion_princess",name:"피의 여왕 로쟈",sinner:"로쟈",keywords:{bleed:3},notes:"출혈 중심 예시 데이터"},
{id:"bleed_don_lamancha",name:"라 만차랜드의 돈키호테",sinner:"돈키호테",keywords:{bleed:3},notes:"출혈 중심 예시 데이터"},
{id:"bleed_outis_barber",name:"바브드 아웃스",sinner:"아웃티스",keywords:{bleed:3},notes:"출혈 중심 예시 데이터"},
{id:"bleed_gregor_bride",name:"신부 그레고르",sinner:"그레고르",keywords:{bleed:2},notes:"출혈 중심 예시 데이터"},
{id:"rupture_example",name:"파열 인격 예시",sinner:"싱클레어",keywords:{rupture:3},notes:"프로토타입용 예시 항목 — 실제 인격 데이터 확인 필요"},
{id:"tremor_example",name:"진동 인격 예시",sinner:"이스마엘",keywords:{tremor:3},notes:"프로토타입용 예시 항목 — 실제 인격 데이터 확인 필요"},
{id:"sinking_example",name:"침잠 인격 예시",sinner:"홍루",keywords:{sinking:3},notes:"프로토타입용 예시 항목 — 실제 인격 데이터 확인 필요"},
{id:"burn_example",name:"화상 인격 예시",sinner:"파우스트",keywords:{burn:3},notes:"프로토타입용 예시 항목 — 실제 인격 데이터 확인 필요"},
{id:"charge_example",name:"충전 인격 예시",sinner:"뫼르소",keywords:{charge:3},notes:"프로토타입용 예시 항목 — 실제 인격 데이터 확인 필요"},
{id:"poise_example",name:"호흡 인격 예시",sinner:"히스클리프",keywords:{poise:3},notes:"프로토타입용 예시 항목 — 실제 인격 데이터 확인 필요"}
];
const GIFTS = [
{id:"bleed_gift_1",name:"핏빛 가시",keyword:"bleed",tier:1,description:"출혈 빌드용 예시 기프트. 실제 효과값은 추후 입력.",upgradeTo:"bleed_gift_2",recipe:["bleed_gift_1","bleed_gift_1"],verified:false},
{id:"bleed_gift_2",name:"핏빛 가시 (강화)",keyword:"bleed",tier:2,description:"강화 기프트 예시.",upgradeTo:"bleed_gift_3",recipe:["bleed_gift_1","bleed_gift_1"],verified:false},
{id:"bleed_gift_3",name:"핏빛 가시 (최종 강화)",keyword:"bleed",tier:3,description:"최종 강화 기프트 예시.",upgradeTo:null,recipe:["bleed_gift_2","bleed_gift_2"],verified:false},
{id:"rupture_gift_1",name:"균열의 파편",keyword:"rupture",tier:1,description:"파열 빌드용 예시 기프트.",upgradeTo:"rupture_gift_2",recipe:["rupture_gift_1","rupture_gift_1"],verified:false},
{id:"rupture_gift_2",name:"균열의 파편 (강화)",keyword:"rupture",tier:2,description:"강화 기프트 예시.",upgradeTo:null,recipe:["rupture_gift_1","rupture_gift_1"],verified:false},
{id:"sinking_gift_1",name:"가라앉은 기억",keyword:"sinking",tier:1,description:"침잠 빌드용 예시 기프트.",upgradeTo:"sinking_gift_2",recipe:["sinking_gift_1","sinking_gift_1"],verified:false},
{id:"sinking_gift_2",name:"가라앉은 기억 (강화)",keyword:"sinking",tier:2,description:"침잠 빌드용 강화 예시 기프트.",upgradeTo:null,recipe:["sinking_gift_1","sinking_gift_1"],verified:false},
{id:"poise_gift_1",name:"선명한 궤적",keyword:"poise",tier:1,description:"호흡 빌드용 예시 기프트.",upgradeTo:"poise_gift_2",recipe:["poise_gift_1","poise_gift_1"],verified:false},
{id:"poise_gift_2",name:"선명한 궤적 (강화)",keyword:"poise",tier:2,description:"호흡 빌드용 강화 예시 기프트.",upgradeTo:null,recipe:["poise_gift_1","poise_gift_1"],verified:false},
{id:"burn_gift_1",name:"꺼지지 않는 불씨",keyword:"burn",tier:1,description:"화상 빌드용 예시 기프트.",upgradeTo:"burn_gift_2",recipe:["burn_gift_1","burn_gift_1"],verified:false},
{id:"burn_gift_2",name:"꺼지지 않는 불씨 (강화)",keyword:"burn",tier:2,description:"화상 빌드용 강화 예시 기프트.",upgradeTo:null,recipe:["burn_gift_1","burn_gift_1"],verified:false},
{id:"charge_gift_1",name:"축전 장치",keyword:"charge",tier:1,description:"충전 빌드용 예시 기프트.",upgradeTo:"charge_gift_2",recipe:["charge_gift_1","charge_gift_1"],verified:false},
{id:"charge_gift_2",name:"축전 장치 (강화)",keyword:"charge",tier:2,description:"충전 빌드용 강화 예시 기프트.",upgradeTo:null,recipe:["charge_gift_1","charge_gift_1"],verified:false},
{id:"tremor_gift_1",name:"진동 공명체",keyword:"tremor",tier:1,description:"진동 빌드용 예시 기프트.",upgradeTo:"tremor_gift_2",recipe:["tremor_gift_1","tremor_gift_1"],verified:false},
{id:"tremor_gift_2",name:"진동 공명체 (강화)",keyword:"tremor",tier:2,description:"진동 빌드용 강화 예시 기프트.",upgradeTo:null,recipe:["tremor_gift_1","tremor_gift_1"],verified:false}
];
let party=[], ownedGifts=[], activeKeyword="all", activeGiftKeyword="all", selectedGift="bleed_gift_1", filterSearch="";
const $=id=>document.getElementById(id);
const keyword=id=>KEYWORDS.find(k=>k.id===id);
const gift=id=>GIFTS.find(g=>g.id===id);
const identity=id=>IDENTITIES.find(i=>i.id===id);
const esc=s=>String(s??"").replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
function status(s){$("status").textContent=s;setTimeout(()=>{if($("status").textContent===s)$("status").textContent=""},2800)}
function counts(){let c={};party.map(identity).filter(Boolean).forEach(i=>Object.entries(i.keywords).forEach(([k,v])=>c[k]=(c[k]||0)+v));return c}
function renderFilters(){ $("keywordFilters").innerHTML=`<button class="pill ${activeKeyword==="all"?"active":""}" data-kw="all">전체 키워드</button>`+KEYWORDS.map(k=>`<button class="pill ${activeKeyword===k.id?"active":""}" data-kw="${k.id}">${k.name}</button>`).join("");$("giftFilters").innerHTML=`<button class="pill ${activeGiftKeyword==="all"?"active":""}" data-gkw="all">전체</button>`+KEYWORDS.map(k=>`<button class="pill ${activeGiftKeyword===k.id?"active":""}" data-gkw="${k.id}">${k.name}</button>`).join("")}
function renderIdentities(){let arr=IDENTITIES.filter(i=>(activeKeyword==="all"||i.keywords[activeKeyword])&&(`${i.name} ${i.sinner}`.toLowerCase().includes(filterSearch.toLowerCase())));if($("sort").value==="name")arr.sort((a,b)=>a.name.localeCompare(b.name,"ko"));else {let c=counts();arr.sort((a,b)=>Math.max(...Object.keys(b.keywords).map(k=>(c[k]||0)+b.keywords[k]))-Math.max(...Object.keys(a.keywords).map(k=>(c[k]||0)+a.keywords[k])))}$("identityCards").innerHTML=arr.map(i=>{let sel=party.includes(i.id);return `<article class="idcard ${sel?"selected":""}"><div class="cardtop"><div><div class="cardname">${esc(i.name)}</div><div class="muted small">${esc(i.sinner)}</div></div><span class="tag">${sel?"편성 중":"샘플"}</span></div><div class="keywordline">${Object.entries(i.keywords).map(([k,v])=>`<span class="kwtag" style="--kw:${keyword(k)?.color||"#aaa"}">${keyword(k)?.name||k} ${v}</span>`).join("")}</div><div class="muted small">${esc(i.notes||"")}</div><div class="cardactions"><button data-add="${i.id}">${sel?"편성 해제":"편성에 추가"}</button></div></article>`}).join("")||'<div class="empty">조건에 맞는 인격이 없습니다.</div>'}
function renderParty(){ $("partyCount").textContent=`${party.length}명 편성`;$("metricMembers").textContent=party.length;$("partyList").innerHTML=party.map((id,n)=>{let i=identity(id);if(!i)return "";return `<div class="partyrow"><span class="tag">${n+1}</span><div class="grow"><strong>${esc(i.name)}</strong><div class="keywordline">${Object.keys(i.keywords).map(k=>`<span class="kwtag" style="--kw:${keyword(k)?.color}">${keyword(k)?.name}</span>`).join("")}</div></div><button class="mini-btn" data-up="${n}" ${n===0?"disabled":""}>↑</button><button class="mini-btn" data-down="${n}" ${n===party.length-1?"disabled":""}>↓</button><button class="mini-btn" data-remove="${id}">×</button></div>`}).join("")||'<div class="empty">왼쪽에서 인격을 추가하세요. 인원 제한은 없습니다.</div>';renderDiagnosis();renderIdentities()}
function renderDiagnosis(){let c=counts(),sorted=KEYWORDS.map(k=>({...k,score:c[k.id]||0})).sort((a,b)=>b.score-a.score),max=Math.max(1,...sorted.map(k=>k.score));$("metricMain").textContent=sorted[0]?.score?sorted[0].name:"—";$("keywordBars").innerHTML=sorted.map(k=>`<div class="barrow"><span>${k.name}</span><div class="bar"><span style="width:${k.score/max*100}%;background:${k.color}"></span></div><span>${k.score}</span></div>`).join("")}
function recommend(){let c=counts();let list=GIFTS.filter(g=>(activeGiftKeyword==="all"||g.keyword===activeGiftKeyword));list.sort((a,b)=>((c[b.keyword]||0)*10+b.tier)-((c[a.keyword]||0)*10-a.tier));$("giftRecommendations").innerHTML=list.slice(0,7).map(g=>`<div class="giftrow"><div><strong>${esc(g.name)}</strong><div class="sub">${keyword(g.keyword)?.name} · ${"★".repeat(g.tier)}${g.verified?"":" · 샘플/미검증"}</div><div class="sub">${esc(g.description)}</div></div><button class="mini-btn" data-own="${g.id}">보유 추가</button></div>`).join("")||'<div class="empty">추천할 기프트가 없습니다.</div>'}
function renderGiftSelect(){$("giftSelect").innerHTML=GIFTS.map(g=>`<option value="${g.id}">${g.name} · ${keyword(g.keyword)?.name} · T${g.tier}</option>`).join("");$("giftSelect").value=selectedGift}
function renderOwned(){let tally={};ownedGifts.forEach(id=>tally[id]=(tally[id]||0)+1);$("ownedGifts").innerHTML=Object.entries(tally).map(([id,n])=>{let g=gift(id);if(!g)return "";return `<div class="giftrow"><div><strong>${esc(g.name)} × ${n}</strong><div class="sub">${keyword(g.keyword)?.name} · T${g.tier}</div></div><div class="row"><button class="mini-btn" data-less="${id}">−</button><button class="mini-btn" data-more="${id}">+</button><button class="mini-btn" data-recipe="${id}">경로</button></div></div>`}).join("")||'<div class="empty">보유 기프트를 추가해 보세요.</div>';renderRecipe()}
function renderRecipe(){let g=gift(selectedGift);if(!g){$("recipeView").textContent="기프트를 선택하세요.";return}let next=g.upgradeTo?gift(g.upgradeTo):null;let recipe=(g.recipe||[]).map(id=>gift(id)?.name||id);$("recipeView").innerHTML=`<div class="giftrow"><div><strong>${esc(g.name)} (T${g.tier})</strong><div class="sub">${esc(g.description)}</div></div><span class="tag">${g.verified?"검증됨":"예시 데이터"}</span></div><p>강화 다음 단계: <strong>${next?esc(next.name):"등록된 다음 단계 없음"}</strong></p><p>등록된 예시 합성 재료: ${recipe.map(esc).join(" + ")||"없음"}</p><p class="muted">주의: 표시된 합성식은 기능 확인을 위한 샘플입니다. 실제 게임 레시피와 일치한다고 보장하지 않습니다.</p>${next?`<button class="btn" data-own="${next.id}">강화형을 보유 목록에 추가</button>`:""}`}
function stateObj(){return {version:1,party:[...party],ownedGifts:[...ownedGifts],activeKeyword,activeGiftKeyword,selectedGift}}
function applyState(s){if(!s||!Array.isArray(s.party)||!Array.isArray(s.ownedGifts))throw Error("올바른 빌드 JSON이 아닙니다.");party=s.party.filter(id=>identity(id));ownedGifts=s.ownedGifts.filter(id=>gift(id));activeKeyword=s.activeKeyword||"all";activeGiftKeyword=s.activeGiftKeyword||"all";selectedGift=gift(s.selectedGift)?s.selectedGift:GIFTS[0].id;renderAll()}
function renderSaved(){let saved=JSON.parse(localStorage.getItem("md-builder-saves")||"[]");$("savedBuilds").innerHTML=saved.map((s,i)=>`<div class="giftrow"><div><strong>${esc(s.name)}</strong><div class="sub">${new Date(s.date).toLocaleString("ko-KR")} · ${s.state.party.length}명</div></div><div class="row"><button class="mini-btn" data-loadsave="${i}">불러오기</button><button class="mini-btn" data-delsave="${i}">삭제</button></div></div>`).join("")||'<div class="empty">저장된 빌드가 없습니다.</div>'}
function renderAll(){renderFilters();renderIdentities();renderParty();recommend();renderGiftSelect();renderOwned();renderSaved()}
document.addEventListener("click",e=>{let t=e.target.closest("button");if(!t)return;
if(t.dataset.kw!==undefined){activeKeyword=t.dataset.kw;renderAll()}
if(t.dataset.gkw!==undefined){activeGiftKeyword=t.dataset.gkw;renderAll()}
if(t.dataset.add){party.includes(t.dataset.add)?party=party.filter(x=>x!==t.dataset.add):party.push(t.dataset.add);renderAll()}
if(t.dataset.remove){party=party.filter(x=>x!==t.dataset.remove);renderAll()}
if(t.dataset.up!==undefined){let n=+t.dataset.up;if(n>0){[party[n-1],party[n]]=[party[n],party[n-1]];renderAll()}}
if(t.dataset.down!==undefined){let n=+t.dataset.down;if(n<party.length-1){[party[n+1],party[n]]=[party[n],party[n+1]];renderAll()}}
if(t.dataset.own){ownedGifts.push(t.dataset.own);selectedGift=t.dataset.own;renderAll()}
if(t.dataset.more){ownedGifts.push(t.dataset.more);renderOwned()}
if(t.dataset.less){let idx=ownedGifts.indexOf(t.dataset.less);if(idx>=0)ownedGifts.splice(idx,1);renderOwned()}
if(t.dataset.recipe){selectedGift=t.dataset.recipe;$("giftSelect").value=selectedGift;renderRecipe()}
if(t.dataset.loadsave!==undefined){let a=JSON.parse(localStorage.getItem("md-builder-saves")||"[]");applyState(a[+t.dataset.loadsave].state);status("빌드를 불러왔습니다.")}
if(t.dataset.delsave!==undefined){let a=JSON.parse(localStorage.getItem("md-builder-saves")||"[]");a.splice(+t.dataset.delsave,1);localStorage.setItem("md-builder-saves",JSON.stringify(a));renderSaved();status("저장 빌드를 삭제했습니다.")}
});
$("search").addEventListener("input",e=>{filterSearch=e.target.value;renderIdentities()});
$("sort").addEventListener("change",renderIdentities);
$("giftSelect").addEventListener("change",e=>{selectedGift=e.target.value;renderRecipe()});
$("addGift").addEventListener("click",()=>{ownedGifts.push($("giftSelect").value);selectedGift=$("giftSelect").value;renderOwned();status("보유 기프트에 추가했습니다.")});
$("clearParty").addEventListener("click",()=>{party=[];renderAll()});
$("saveBtn").addEventListener("click",()=>{let name=prompt("빌드 이름을 입력하세요","새 거던 빌드");if(!name)return;let a=JSON.parse(localStorage.getItem("md-builder-saves")||"[]");a.unshift({name,date:new Date().toISOString(),state:stateObj()});localStorage.setItem("md-builder-saves",JSON.stringify(a));renderSaved();status("빌드를 저장했습니다.")});
$("loadBtn").addEventListener("click",()=>{renderSaved();$("savedBuilds").scrollIntoView({behavior:"smooth",block:"center"})});
$("exportBtn").addEventListener("click",()=>{let blob=new Blob([JSON.stringify({...stateObj(),exportedAt:new Date().toISOString()},null,2)],{type:"application/json"});let a=document.createElement("a");a.href=URL.createObjectURL(blob);a.download="limbus-build.json";a.click();URL.revokeObjectURL(a.href);status("JSON 파일을 내보냈습니다.")});
$("importBtn").addEventListener("click",()=>$("importFile").click());
$("importFile").addEventListener("change",async e=>{let f=e.target.files[0];if(!f)return;try{applyState(JSON.parse(await f.text()));status("JSON 빌드를 가져왔습니다.")}catch(err){alert("가져오기에 실패했습니다: "+err.message)}e.target.value=""});
$("clearBtn").addEventListener("click",()=>{if(confirm("현재 편성과 보유 기프트를 초기화할까요? 저장된 빌드는 유지됩니다.")){party=[];ownedGifts=[];activeKeyword="all";activeGiftKeyword="all";selectedGift=GIFTS[0].id;renderAll()}});
renderAll();
</script>
</body></html>