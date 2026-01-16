<link rel="stylesheet" href="https://unpkg.com/@picocss/pico@latest/css/pico.min.css">

<div style="background:#ffffff; border-bottom:1px solid #dcdcdc;">
  <div style="
    max-width:1280px;
    margin:0 auto;
    padding:1.25rem 1.5rem; /* 保留原本 padding，上下與導覽列平行 */
    display:flex;
    align-items:center; /* logo 與導覽列垂直置中 */
    justify-content:space-between;
    gap:2rem;
    flex-wrap:wrap;
  ">




<form
  action="https://formsubmit.co/ray@youngs.com.tw"
  method="POST"
  style="display:grid; gap:0.6rem; font-size:0.9rem;"
>

  <!-- FormSubmit 必要設定 -->
  <input type="hidden" name="_subject" value="官網聯絡表單詢問">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_template" value="table">

  <label>
    公司名稱
    <input
      type="text"
      name="company"
      placeholder="請輸入公司名稱"
      style="height:1.6rem; font-size:0.9rem; padding:0.2rem;"
    >
  </label>

  <div style="display:grid; grid-template-columns:1fr 1fr; gap:0.6rem;">
    <label>
      聯絡人
      <input
        type="text"
        name="contact_name"
        placeholder="請輸入姓名"
        style="height:1.6rem; font-size:0.9rem; padding:0.2rem;"
      >
    </label>

    <label>
      性別
      <select
        name="gender"
        style="height:1.6rem; font-size:0.9rem; padding:0.2rem;"
      >
        <option value="">請選擇</option>
        <option>先生</option>
        <option>女士</option>
        <option>其他</option>
      </select>
    </label>
  </div>

  <label>
    聯絡電話
    <input
      type="tel"
      name="phone"
      placeholder=""
      style="height:1.6rem; font-size:0.9rem; padding:0.2rem;"
    >
  </label>

  <label>
    電子郵件
    <input
      type="email"
      name="email"
      required
      placeholder="example@email.com"
      style="height:1.6rem; font-size:0.9rem; padding:0.2rem;"
    >
  </label>

  <label>
    詢問內容
    <textarea
      name="message"
      rows="3"
      placeholder="請輸入您的需求或產品規格"
      style="font-size:0.9rem; padding:0.2rem;"
    ></textarea>
  </label>

  <button
    type="submit"
    style="
      margin-top:0.8rem;
      background:rgba(47,58,65,0.5);
      border:none;
      padding:0.6rem 1.2rem;
      font-size:0.9rem;
      width:140px;
      color:#fff;
      border-radius:4px;
      cursor:pointer;
    "
    onmouseover="this.style.background='rgba(47,58,65,0.8)'"
    onmouseout="this.style.background='rgba(47,58,65,0.5)'"
  >
    送出表單
  </button>

</form>





<footer style="
  margin-top:4rem;
  padding:1.5rem 1rem;
  border-top:1px solid #e5e5e5;
  font-size:0.85rem;
  color:#555;
">
  <div style="
    max-width:1200px;
    margin:0 auto;
    display:flex;
    flex-direction:column;
    gap:0.25rem;
    text-align:center;
  ">
    <div>永旭材料貿易有限公司 ©</div>
    <div>YOUNGS MATERIAL CO., LTD.</div>
    <div>電話：06-2580502 ｜ 地址：臺南市北區大和路330巷21號1樓</div>
  </div>
</footer>
