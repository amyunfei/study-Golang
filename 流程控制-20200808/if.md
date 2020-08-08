# if

## 普通写法

<pre name="code">
func main () {
  age := 20
  if age > 18 {
    ...
  } else if age < 18 {
    ...
  } else {
    ...
  }
}
</pre>


## 同一行进行赋值

<pre name="code">
func main () {
  
  if age := 20;age > 18 {
    ...
  } else if age < 18 {
    ...
  } else {
    ...
  }
}
</pre>
### 此处变量age作用于只在于if块中, 无法在函数中直接访问