<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>คำนวณโค้ดส่วนลด Shopee Live</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: #f5f5f5; min-height: 100vh; }
  .wrap { max-width: 480px; margin: 0 auto; padding: 1rem; }
  .header { background: #EE4D2D; border-radius: 14px; padding: 1.1rem 1.25rem; margin-bottom: 1rem; }
  .header h1 { color: #fff; font-size: 18px; font-weight: 600; }
  .header p { color: rgba(255,255,255,0.85); font-size: 13px; margin-top: 3px; }
  .section-title { font-size: 12px; font-weight: 600; color: #888; margin: 1rem 0 0.5rem; text-transform: uppercase; letter-spacing: 0.05em; }
  .price-row { display: flex; align-items: center; gap: 10px; margin-bottom: 1rem; }
  .price-row input { flex: 1; font-size: 20px; padding: 10px 14px; border-radius: 10px; border: 2px solid #EE4D2D; outline: none; background: #fff; color: #333; }
  .price-row span { font-size: 20px; font-weight: 600; color: #555; }
  .coupon-card { background: #fff; border: 1px solid #e8e8e8; border-radius: 14px; padding: 0.9rem 1rem; margin-bottom: 0.6rem; display: flex; align-items: center; gap: 12px; }
  .best-card { border: 2px solid #EE4D2D; }
  .coupon-icon { width: 42px; height: 42px; background: #EE4D2D; border-radius: 10px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .coupon-icon svg { width: 20px; height: 20px; fill: #fff; }
  .coupon-info { flex: 1; min-width: 0; }
  .coupon-name { font-size: 14px; font-weight: 600; color: #333; }
  .coupon-desc { font-size: 12px; color: #888; margin-top: 2px; }
  .best-badge { background: #EE4D2D; color: #fff; font-size: 10px; padding: 2px 7px; border-radius: 20px; margin-left: 6px; vertical-align: middle; font-weight: 600; }
  .coupon-result { text-align: right; flex-shrink: 0; }
  .coupon-save { font-size: 16px; font-weight: 700; color: #EE4D2D; }
  .coupon-final { font-size: 12px; color: #888; margin-top: 2px; }
  .na { color: #bbb; font-size: 13px; }
  .empty { text-align: center; color: #aaa; font-size: 14px; padding: 2rem 0; }
  .edit-toggle { display: flex; align-items: center; gap: 8px; cursor: pointer; color: #EE4D2D; font-size: 14px; font-weight: 600; background: none; border: none; padding: 0.5rem 0; margin-top: 0.5rem; }
  .edit-area { display: none; margin-top: 0.75rem; background: #fff; border-radius: 14px; padding: 1rem; border: 1px solid #e8e8e8; }
  .edit-area.open { display: block; }
  .edit-header { display: grid; grid-template-columns: 1fr 72px 72px 72px 32px; gap: 6px; margin-bottom: 6px; }
  .edit-header span { font-size: 11px; color: #aaa; font-weight: 600; }
  .coupon-row { display: grid; grid-template-columns: 1fr 72px 72px 72px 32px; gap: 6px; align-items: center; margin-bottom: 6px; }
  .coupon-row input { font-size: 13px; padding: 7px 8px; border-radius: 8px; border: 1px solid #ddd; color: #333; background: #fafafa; width: 100%; }
  .coupon-row input:focus { outline: none; border-color: #EE4D2D; background: #fff; }
  .del-btn { background: none; border: none; cursor: pointer; color: #ccc; font-size: 16px; line-height: 1; padding: 4px; }
  .del-btn:hover { color: #EE4D2D; }
  .add-btn { background: none; border: 1.5px dashed #EE4D2D; color: #EE4D2D; border-radius: 10px; padding: 8px 12px; font-size: 13px; font-weight: 600; cursor: pointer; margin-top: 8px; width: 100%; }
  .add-btn:hover { background: #fff5f3; }
  .no-result { text-align: center; padding: 1.5rem 0; color: #aaa; font-size: 14px; }
</style>
</head>
<body>
<div class="wrap">
  <div class="header">
    <h1>คำนวณโค้ดส่วนลด</h1>
    <p>Shopee Live — สำหรับพนักงาน</p>
  </div>

  <div class="section-title">ราคาสินค้า</div>
  <div class="price-row">
    <span>฿</span>
    <input type="number" id="priceInput" placeholder="กรอกราคา เช่น 500" min="0" oninput="calc()" />
  </div>

  <div class="section-title">ผลลัพธ์โค้ดส่วนลด</div>
  <div id="results"><div class="no-result">กรอกราคาสินค้าด้านบน</div></div>

  <button class="edit-toggle" onclick="toggleEdit()">
    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M11 4H4a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7"/><path d="M18.5 2.5a2.121 2.121 0 0 1 3 3L12 15l-4 1 1-4 9.5-9.5z"/></svg>
    <span id="editLabel">แก้ไขโค้ด</span>
  </button>

  <div class="edit-area" id="editArea">
    <div class="edit-header">
      <span>ชื่อโค้ด</span>
      <span>ลด %</span>
      <span>สูงสุด ฿</span>
      <span>ขั้นต่ำ ฿</span>
      <span></span>
    </div>
    <div id="couponRows"></div>
    <button class="add-btn" onclick="addCoupon()">+ เพิ่มโค้ด</button>
  </div>
</div>

<script>
const DEFAULT = [
  { name: "โค้ด A", pct: 40, max: 100, min: 100 },
  { name: "โค้ด B", pct: 35, max: 120, min: 100 },
  { name: "โค้ด C", pct: 30, max: 300, min: 100 },
  { name: "โค้ด D", pct: 25, max: 140, min: 100 },
];
let saved = localStorage.getItem('coupons');
let coupons = saved ? JSON.parse(saved) : DEFAULT;

function calc() {
  const price = parseFloat(document.getElementById('priceInput').value) || 0;
  const el = document.getElementById('results');
  if (coupons.length === 0) { el.innerHTML = '<div class="empty">ยังไม่มีโค้ด กรุณาเพิ่มโค้ดด้านล่าง</div>'; return; }
  if (price === 0) { el.innerHTML = '<div class="no-result">กรอกราคาสินค้าด้านบน</div>'; return; }

  let results = coupons.map(c => {
    if (price < c.min) return { ...c, saving: null, final: null };
    const saving = Math.min(price * c.pct / 100, c.max);
    return { ...c, saving: Math.round(saving), final: Math.round(price - saving) };
  });

  let bestIdx = -1, bestSaving = 0;
  results.forEach((r, i) => { if (r.saving !== null && r.saving > bestSaving) { bestSaving = r.saving; bestIdx = i; } });

  el.innerHTML = results.map((r, i) => `
    <div class="coupon-card ${i === bestIdx ? 'best-card' : ''}">
      <div class="coupon-icon">
        <svg viewBox="0 0 24 24"><path d="M20.59 13.41l-7.17 7.17a2 2 0 0 1-2.83 0L2 12V2h10l8.59 8.59a2 2 0 0 1 0 2.82z"/><line x1="7" y1="7" x2="7.01" y2="7" stroke="#fff" stroke-width="2" stroke-linecap="round"/></svg>
      </div>
      <div class="coupon-info">
        <div class="coupon-name">${r.name}${i === bestIdx ? '<span class="best-badge">ดีสุด</span>' : ''}</div>
        <div class="coupon-desc">ลด ${r.pct}% สูงสุด ฿${r.max} | ขั้นต่ำ ฿${r.min}</div>
      </div>
      <div class="coupon-result">
        ${r.saving !== null
          ? `<div class="coupon-save">-฿${r.saving}</div><div class="coupon-final">จ่าย ฿${r.final}</div>`
          : `<div class="na">ต่ำกว่าขั้นต่ำ</div>`}
      </div>
    </div>
  `).join('');
}

function renderRows() {
  document.getElementById('couponRows').innerHTML = coupons.map((c, i) => `
    <div class="coupon-row">
      <input value="${c.name}" placeholder="ชื่อโค้ด" oninput="update(${i},'name',this.value)" />
      <input type="number" value="${c.pct}" min="0" max="100" oninput="update(${i},'pct',+this.value)" />
      <input type="number" value="${c.max}" min="0" oninput="update(${i},'max',+this.value)" />
      <input type="number" value="${c.min}" min="0" oninput="update(${i},'min',+this.value)" />
      <button class="del-btn" onclick="removeCoupon(${i})">✕</button>
    </div>
  `).join('');
}

function save() { localStorage.setItem('coupons', JSON.stringify(coupons)); }
function update(i, key, val) { coupons[i][key] = val; save(); calc(); }
function addCoupon() { coupons.push({ name: "โค้ดใหม่", pct: 20, max: 100, min: 100 }); save(); renderRows(); calc(); }
function removeCoupon(i) { coupons.splice(i, 1); save(); renderRows(); calc(); }

let editOpen = false;
function toggleEdit() {
  editOpen = !editOpen;
  document.getElementById('editArea').classList.toggle('open', editOpen);
  document.getElementById('editLabel').textContent = editOpen ? 'ซ่อนการแก้ไข' : 'แก้ไขโค้ด';
  if (editOpen) renderRows();
}
</script>
</body>
</html>
