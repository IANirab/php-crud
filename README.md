# php-crud
this is a helper for php crud operation.

<hr>

# How to Use

<img src="https://imgbbb.com/images/2019/04/14/Screenshot-56.png" alt="folder sceenshot" />

create a new file `index.php` 

then , open `index.php` & `config.php` in your text editor .

In `config.php` , You need to setup Database connection as first.

then `index.php`,

put these at the top ,

``` include 'database/index.php';```

# For Insert :

`DB::insert($table, $data);`

`$table` = its your table name,

`$data` = A array ,where key will be the column of your table.

# For select :

`DB::select($table);`

### Example :

```bash
$results = DB::select($table);

while ($rows = $results->fetch_assoc()) {

	echo $rows['name'];
}
```


# For Update : 

`DB::update($table, $data, $id);`

# For Delete : 

`DB::delete($table, $id);`

---

### For more Links

- [GitHub](https://github.com/IANirab/)
- [Facebook](https://web.facebook.com/istiaq.nirab.1)

**Enjoy!**
