<link rel="stylesheet" href="https://unpkg.com/@picocss/pico@latest/css/pico.min.css">

<div style="background:#ffffff; border-bottom:1px solid #dcdcdc;">
  <div style="
    max-width:1280px;
    margin:0 auto;
    padding:1.25rem 1.5rem;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:2rem;
    flex-wrap:wrap;
  ">
    <a href="index" style="display:flex; align-items:center;">
      <img src="images/logo-brand-youngs.png"
           alt="永旭材料貿易有限公司"
           style="height:80px; max-width:none; object-fit:contain;">
    </a>

    <nav style="
      display:flex;
      gap:1.5rem;
      font-size:0.95rem;
      align-items:center;
      white-space:nowrap;
    ">
      <a href="index">公司簡介</a>
      <a href="brands">代理品牌</a>
      <a href="products">產品列表</a>
      <a href="faq">FAQ</a>
      <a href="contact" style="font-weight:600;">聯絡我們</a>
    </nav>
  </div>
</div>

<form
  action="https://formsubmit.co/ray@youngs.com.tw"
  method="POST"
  style="display:grid; gap:0.6rem; font-size:0.9rem;"
>
  <!-- FormSubmit 設定（看不到，不影響畫面） -->
  <input type="hidden" name="_subject" value="官網聯絡表單詢問">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_template" value="table">

  <label>
    公司名稱
    <input type="text" name="company">
  </label>

  <label>
    聯絡人
    <input type="text" name="contact_name">
  </label>

  <label>
    聯絡電話
    <input type="tel" name="phone">
  </label>

  <label>
    電子郵件
    <input type="email" name="email" required>
  </label>

  <label>
    詢問內容
    <textarea name="message" rows="3"></textarea>
  </label>

  <button type="submit" style="
    margin-top:0.8rem;
    background:rgba(47,58,65,0.5);
    border:none;
    padding:0.6rem 1.2rem;
    width:140px;
    color:#fff;
    border-radius:4px;
  ">
    送出表單
  </button>
</form>



<footer style="margin-top:4rem; padding:1.5rem 1rem; border-top:1px solid #e5e5e5; font-size:0.85rem; color:#555;">
  <div style="max-width:1200px; margin:0 auto; text-align:center;">
    <div>永旭材料貿易有限公司 ©</div>
    <div>YOUNGS MATERIAL CO., LTD.</div>
    <div>電話：06-2580502 ｜ 地址：臺南市北區大和路330巷21號1樓</div>
  </div>
</footer>
