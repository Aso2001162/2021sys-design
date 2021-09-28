entity "ユーザーテーブル" as user <user> <<M.MASTER_MARK_COLOR>> {
  + user_number [PK]
  --
  user_id
  user_pass
  user_name
  user_address
}

entity "商品テーブル" as merchandise <merchandise> <<M.MASTER_MARK_COLOR>> {
  + genre_id [PK]
  + merchandise_id [PK]
  --
  genre_name
  merchandise_name
  int
  merchandise_detail
  sales
}  
