#履歴テーブル(history)

|和名|属性名|型|PK|NN|FK|
|:---|:---|:---|:---:|:---:|:---:|
|購入したユーザー番号|history_user_number|int|〇|||
|購入回数|history_count|int|〇|||
|ジャンルID|history_genre_id|int||〇|〇|
|商品ID|history_merchandise_id|int||〇|〇|
|購入数|history_quantity|int||〇||
|購入日|history_day|datetime||〇||
