

<html>
    <head>
        <meta charset="UTF-8">
        <title>MUKI space* / 網站前端課程</title>
      </head>
    <body>
        <header>MUKI space* / 網站前端課程</header>
        <div class="panel">
            <form>
                <fieldset>
                    <legend>基本資料</legend>
                    <p>(必填)姓名：<input type="text" placeholder="請輸入文字" required="required"></p>
                    <p>(必填)聯絡電話：<input type="tel" placeholder="請填入電話號碼" required="required"></p>
                    <p>電子信箱：<input type="email" placeholder="請輸入email"></p>
                    <p>生日：<input type="date"></p>
                </fieldset>
                <fieldset>
                    <legend>進階資料</legend>
                    <p>您是如何知道此課程：
                        <input type="radio" id="course-s1"><label for="course-s1">Facebook 廣告</label>
                        <input type="radio" id="course-s2"><label for="course-s2">Google 廣告</label>
                        <input type="radio" id="course-s3"><label for="course-s3">親友介紹</label>
                        <input type="radio" id="course-s4"><label for="course-s4">其他</label>
                    </p>
                    <p>有什麼想了解的嗎<br />
                        <textarea id="" cols="40" rows="8"></textarea>
                    </p>
                </fieldset>
                <div class="btn-position">
                    <button type="submit">送出</button>
                    <button type="reset">重寫</button>
                </div>
            </form>
        </div>
    </body>
</html>

