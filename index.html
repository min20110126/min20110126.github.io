<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shop</title>

<style>
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto;
  background: #f5f5f5;
}

header {
  background: #111;
  color: white;
  text-align: center;
  padding: 15px;
  font-size: 22px;
  font-weight: bold;
}

.ad {
  background: #fffbe6;
  color: #555;
  font-size: 12px;
  padding: 8px 12px;
  text-align: center;
}

.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 12px;
  padding: 12px;
}

@media (min-width: 768px) {
  .grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

.item {
  background: white;
  border-radius: 12px;
  padding: 10px;
  cursor: pointer;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.item img {
  width: 100%;
  border-radius: 10px;
}

.name {
  margin-top: 8px;
  font-size: 14px;
}

.price {
  color: #e60023;
  font-weight: bold;
  margin-top: 4px;
}

.pages {
  text-align: center;
  padding: 20px;
}

.pages button {
  margin: 0 4px;
  padding: 8px 12px;
  border: none;
  border-radius: 6px;
  background: #111;
  color: white;
}

/* 상세 페이지 */
.detail {
  position: fixed;
  inset: 0;
  background: white;
  z-index: 10;
  display: none;
  flex-direction: column;
}

.detail img {
  width: 100%;
}

.detail-content {
  padding: 16px;
}

.buy {
  position: fixed;
  bottom: 0;
  width: 100%;
  background: #e60023;
  color: white;
  border: none;
  padding: 16px;
  font-size: 18px;
}
</style>
</head>

<body>

<header>Shop</header>

<div class="ad">
  이 포스팅은 쿠팡 파트너스 활동의 일환으로,
  이에 따른 일정액의 수수료를 제공받습니다.
</div>

<div class="grid" id="grid"></div>

<div class="pages">
  <button onclick="loadPage(1)">1</button>
  <button onclick="loadPage(2)">2</button>
  <button onclick="loadPage(3)">3</button>
  <button onclick="loadPage(4)">4</button>
</div>

<!-- 상세 페이지 -->
<div class="detail" id="detail">
  <img id="detailImg">
  <div class="detail-content">
    <h3 id="detailName"></h3>
    <p id="detailPrice"></p>
    <p>로켓배송 · 무료배송</p>
  </div>
  <button class="buy" onclick="goBuy()">쿠팡에서 구매하기</button>
</div>

<script>
const products = [
  // 1~36 예시 상품
  ...Array.from({ length: 36 }, (_, i) => ({
    name: `인기 상품 ${i + 1}`,
    price: `${(i % 9 + 1) * 10000 + 9900}원`,
    img: `https://image.coupangcdn.com/image/vendor_inventory/example${(i % 5) + 1}.jpg`,
    link: "https://www.coupang.com" // 🔴 여기에 파트너스 링크
  }))
];

let currentProduct = null;

function loadPage(page) {
  const grid = document.getElementById("grid");
  grid.innerHTML = "";
  const start = (page - 1) * 9;

  products.slice(start, start + 9).forEach((p, i) => {
    grid.innerHTML += `
      <div class="item" onclick="openDetail(${start + i})">
        <img src="${p.img}">
        <div class="name">${p.name}</div>
        <div class="price">${p.price}</div>
      </div>
    `;
  });
}

function openDetail(i) {
  currentProduct = products[i];
  document.getElementById("detailImg").src = currentProduct.img;
  document.getElementById("detailName").innerText = currentProduct.name;
  document.getElementById("detailPrice").innerText = currentProduct.price;
  document.getElementById("detail").style.display = "flex";
}

function goBuy() {
  location.href = currentProduct.link;
}

loadPage(1);
</script>

</body>
</html>
