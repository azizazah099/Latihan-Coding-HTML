<!DOCTYPE html>
<html>
   
    <head>
        <title>Coding tabel</title>
    </head>
    <style>
        table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
        }
        </style>
    <body>
        <ol>
            <li>
                <p style="font-size: 20;"><h1>TABEL</h1> </p>
                <p> <h2> 対戦結果</h2>
               <p><h3>第73回JABA九州大会</h3></p> 
               <p>2021年5月9日(日) 9:00</p> 
               <p></p> 試合会場：オーヴィジョンスタジアム下関</p>
                <table style="width:45%" >
                    <tr style="text-align:center;">
                        <th>チーム名</th>
                        <th>1</th>
                        <th>2</th>
                        <th>3</th>
                        <th>4</th>
                        <th>5</th>
                        <th>6</th>
                        <th>7</th>
                        <th>8</th>
                        <th>9</th>
                        <th>計</th>
                      </tr>
                      <tr  style="text-align:center;">
            
                            <td>パナソニック</td>
                            <td>0</td>
                            <td>0</td>
                            <td>0</td>
                            <td>0</td>
                            <td>1</td>
                            <td>0</td>
                            <td>3</td>
                            <td>0</td>
                            <td>3</td>
                            <td>7</td>
                      </tr>
                      <tr style="text-align:center;">
                      <td>Honda熊本</td>
                      <td>0</td>
                      <td>1</td>
                      <td>0</td>
                      <td>0</td>
                      <td>0</td>
                      <td>0</td>
                      <td>0</td>
                      <td>0</td>
                      <td>0</td>
                      <td>1</td>
                      </tr>
                            
                      </tr>


                </table>

               <br>

                <table style="width:45%">
                   <tr style="text-align:center;">
                    <th rowspan="2">バッテリー</th>
                    <th colspan="5">Honda熊本</th>
                    <th colspan="5">パナソニック</th>
                   </tr>
                   <tr>
                    <td colspan="5">投手：島袋、福田、横川、内田、高山、中津
                        捕手：竹葉</td>
                    <td colspan="5">
                        投手：榎本 :
                        捕手：川上
                    </td>
                   </tr>
                </table>
            </li>

            <li>
                <p style="font-size: 20;"><h1>FORM</h1> </p>

                <form>
                    <label for="お名前">お名前 [必須]:</label>　
                    <input type="text" id="お名前" name="お名前">　<br>
                    <label for="メールアドレス">メールアドレス [必須]:</label>
                    <input type="text" id="lメールアドレス" name="メールアドレス"> <br>
                    <label for="電話"> 電話番号　[任意]</label>
                    <input type="text" id="電話" name="電話"> <br>
                    
                    <br>
                    <label for="ご用件">ご要件　[必須]:</label>
                    <select id="ご用件" name="ご用件">
                        <option value=" 選択してください">選択してください</option>
                        <option value="書籍についてのご質問(個人のお客様)">書籍についてのご質問(個人のお客様)</option>
                        <option value="書籍についてのご質問(取次・書店様)">書籍についてのご質問(取次・書店様) </option>
                        <option value="書籍についてのご質問(メディア関係者様) ">書籍についてのご質問(メディア関係者様) </option>
                        <option value="アルバイト・パートに関するお問い合わせ">アルバイト・パートに関するお問い合わせ</option>
                        <option value="仕事のご依頼・お問い合わせ">仕事のご依頼・お問い合わせ</option>
                        <option value="外部スタッフのご希望(フリーの方、制作会社様)">外部スタッフのご希望(フリーの方、制作会社様)</option>
                        <option value="その他のお問合せ">その他のお問合せ</option>
                    </select>
                    <br>
                    <br>
                    <label for=" 問合せ"> 問い合わせ内容 [必須]:　</label> <br>
                    <textarea name="問合せ"></textarea>
                    <br>
	                <button type="button">確認</button>
                </form>

            </li>


        </ol>
        
</html>
