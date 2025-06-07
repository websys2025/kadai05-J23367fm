## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* ・https://zipcloud.ibsnet.co.jp/api/search
* ・郵便番号を指定して、該当する住所情報をJSON形式で返すAPI。
* リクエストとレスポンスのフォーマット
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
*・API: Open-Meteo Weather API
*・URL: https://open-meteo.com
*
* エンドポイントと機能
* ・エンドポイント: https://api.open-meteo.com/v1/forecast
*・機能: 緯度や、経度を指定することで、次のような気象データを取得できる無料の天気API。
*
* リクエストとレスポンスのフォーマット
* ・リクエスト: const url = 'https://api.open-meteo.com/v1/forecast?latitude=35.60&longitude=140.12&current_weather=true';
*              const response = await fetch(url);
### Q3-3. 感想
* 今回の課題で苦労したこと
* ・初めてのWeb APIの読み取り操作で、データの取り出し方や書き方に戸惑いました。
* 演習を通して理解できたこと
* ・緯度・経度指定でどこの地域の天気でも取得できるので、自由度も高いと感じた。
* Web APIの利便性や課題など
* ・リアルタイムの情報を簡単に取得できてとても便利だと感じました。
