# README
ruby version: 2.3.1p112 (2016-04-26 revision 54768) [x86_64-darwin17]
rails version: 5.1.6
Database: mysql

# membersテーブル

|Column|Type|Options|
|------|----|-------|
|user_id|integer|null: false, foreign_key: true|
|group_id|integer|null: false, foreign_key: true|

### Association
- belongs_to :group
- belongs_to :user
