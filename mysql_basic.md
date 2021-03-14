## 最近使用mysql比较多，很多基础的都需要google，有必要记录一哈


1. 查询列名，为insert 做准备
```zsh
mysql> select column_name from Information_schema.columns where table_name = 'load_profile';

+-----------------+
| COLUMN_NAME     |
+-----------------+
| id              |
| name            |
| protocol        |
| profile_type    |
| process_count   |
...
| create_time     |
| update_time     |
| uid             |
+-----------------+
22 rows in set (0.00 sec)
```
