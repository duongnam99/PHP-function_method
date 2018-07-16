# PHP
- var_dump() ( hàm check )
## Một số hàm cần lưu ý khi xử lí chuỗi
- addslashes ( $str ) / stripslashes ($str)
- explode ( $delimiter , $string) / implode($delimiter, $piecesarray);
- strlen($string)
- str_word_count($str)
- str_repeat(  $str,  int $n  )
- str_replace( $chuoi_tim, $chuoi_thay_the, $chuoi_nguon )
- substr( $string,  $start, $length )
- strstr( $string, $ky_tu_cho_truoc )
- strpos($str, $chuoi_tim )
- strtoupper($string ) / strtolower($str);
- ucword($string) / ucfirst($string)
- trim($string, $ky_tu) ( xóa kí tự)
## Một số hàm xử lí mảng:
- count($array)
- array_values($array)
- array_pop($array) 
- array_push($array,$var,$var...)
- array_shift($array) / array_unshift($array, $var, $var...) ( xóa hoặc thêm nhiều phần tử vào đầu mảng)
- array_flip($array) ( chuyển key thành value)
- sort($array) ( sắp xếp mảng theo tăng dần, trả về false nếu không thành công)
- array_reverse($array)
- array_merger($array,$array...)
- array_search($keyword,$array) ( tìm kiếm, trả về key nếu có)
- array_slice($array,$begin,$lenght) ( lấy phần tử )
- array_key_exists($key,$array) ( trả về true nếu tồn tại)
- array_diff($array1,$array2,..) ( trả về mảng chứa các phần tử có trong 1 nhưng không có trong 2)
- array_intersect($array1,$array2,..) ( trả về mảng các phần tử giống nhau của mảng)

## Full
- [chuỗi](http://php.net/manual/en/ref.strings.php)
- [Mảng](http://php.net/manual/en/ref.array.php)
