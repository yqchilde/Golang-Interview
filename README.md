> 目录
>
> * [1\. 下面这段代码输出的内容：](#1-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E7%9A%84%E5%86%85%E5%AE%B9)
> * [2\. 下面这段代码输出什么，说明原因。](#2-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88%E8%AF%B4%E6%98%8E%E5%8E%9F%E5%9B%A0)
> * [3\. 下面两段代码输出什么？](#3-%E4%B8%8B%E9%9D%A2%E4%B8%A4%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [4\. 下面这段代码有什么缺陷？](#4-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E6%9C%89%E4%BB%80%E4%B9%88%E7%BC%BA%E9%99%B7)
> * [5\. new() 与 make() 的区别](#5-new-%E4%B8%8E-make-%E7%9A%84%E5%8C%BA%E5%88%AB)
> * [6\. 下面这段代码能否通过编译，不能的话原因是什么；如果能，输出什么？](#6-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%83%BD%E5%90%A6%E9%80%9A%E8%BF%87%E7%BC%96%E8%AF%91%E4%B8%8D%E8%83%BD%E7%9A%84%E8%AF%9D%E5%8E%9F%E5%9B%A0%E6%98%AF%E4%BB%80%E4%B9%88%E5%A6%82%E6%9E%9C%E8%83%BD%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [7\. 下面这段代码能否通过编译，不能的话原因是什么；如果可以，输出什么？](#7%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%83%BD%E5%90%A6%E9%80%9A%E8%BF%87%E7%BC%96%E8%AF%91%E4%B8%8D%E8%83%BD%E7%9A%84%E8%AF%9D%E5%8E%9F%E5%9B%A0%E6%98%AF%E4%BB%80%E4%B9%88%E5%A6%82%E6%9E%9C%E5%8F%AF%E4%BB%A5%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [8\. 下面这段代码能否通过编译，如果可以，输出什么？](#8-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%83%BD%E5%90%A6%E9%80%9A%E8%BF%87%E7%BC%96%E8%AF%91%E5%A6%82%E6%9E%9C%E5%8F%AF%E4%BB%A5%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [9\. 下面这段代码能否通过编译？不能的话，原因是什么？如果通过，输出什么？](#9%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%83%BD%E5%90%A6%E9%80%9A%E8%BF%87%E7%BC%96%E8%AF%91%E4%B8%8D%E8%83%BD%E7%9A%84%E8%AF%9D%E5%8E%9F%E5%9B%A0%E6%98%AF%E4%BB%80%E4%B9%88%E5%A6%82%E6%9E%9C%E9%80%9A%E8%BF%87%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [10\. 通过指针变量p访问其成员变量name,有哪几种方式？](#10-%E9%80%9A%E8%BF%87%E6%8C%87%E9%92%88%E5%8F%98%E9%87%8Fp%E8%AE%BF%E9%97%AE%E5%85%B6%E6%88%90%E5%91%98%E5%8F%98%E9%87%8Fname%E6%9C%89%E5%93%AA%E5%87%A0%E7%A7%8D%E6%96%B9%E5%BC%8F)
> * [11\. 下面这段代码能否通过编译？如果通过，输出什么？](#11-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%83%BD%E5%90%A6%E9%80%9A%E8%BF%87%E7%BC%96%E8%AF%91%E5%A6%82%E6%9E%9C%E9%80%9A%E8%BF%87%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [12\. 以下代码输出什么？](#12-%E4%BB%A5%E4%B8%8B%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [13\. 关于字符串连接，下面语法正确的是？](#13-%E5%85%B3%E4%BA%8E%E5%AD%97%E7%AC%A6%E4%B8%B2%E8%BF%9E%E6%8E%A5%E4%B8%8B%E9%9D%A2%E8%AF%AD%E6%B3%95%E6%AD%A3%E7%A1%AE%E7%9A%84%E6%98%AF)
> * [14\. 下面这段代码能否编译通过？如果可以，输出什么？](#14-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%83%BD%E5%90%A6%E7%BC%96%E8%AF%91%E9%80%9A%E8%BF%87%E5%A6%82%E6%9E%9C%E5%8F%AF%E4%BB%A5%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [15\. 下面赋值正确的是（）](#15-%E4%B8%8B%E9%9D%A2%E8%B5%8B%E5%80%BC%E6%AD%A3%E7%A1%AE%E7%9A%84%E6%98%AF)
> * [16\. 关于init函数，下面说法正确的是（）](#16-%E5%85%B3%E4%BA%8Einit%E5%87%BD%E6%95%B0%E4%B8%8B%E9%9D%A2%E8%AF%B4%E6%B3%95%E6%AD%A3%E7%A1%AE%E7%9A%84%E6%98%AF)
> * [17\. 下面这段代码输出什么以及原因？](#17-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88%E4%BB%A5%E5%8F%8A%E5%8E%9F%E5%9B%A0)
> * [18\. 下面这段代码能否编译通过？如果可以，输出什么？](#18-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%83%BD%E5%90%A6%E7%BC%96%E8%AF%91%E9%80%9A%E8%BF%87%E5%A6%82%E6%9E%9C%E5%8F%AF%E4%BB%A5%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [19\. 关于channel，下面语法正确的是（）](#19-%E5%85%B3%E4%BA%8Echannel%E4%B8%8B%E9%9D%A2%E8%AF%AD%E6%B3%95%E6%AD%A3%E7%A1%AE%E7%9A%84%E6%98%AF)
> * [20\. 下面这段代码输出什么？](#20-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [21\. 下面这段代码输出什么？](#21-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [22\. 下面这段代码输出什么？](#22-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [23\. 下面这段代码输出什么？](#23-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [24\. 下面这段代码输出什么？](#24-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [25\. 关于 cap() 函数的适用类型，下面说法正确的是()](#25-%E5%85%B3%E4%BA%8E-cap-%E5%87%BD%E6%95%B0%E7%9A%84%E9%80%82%E7%94%A8%E7%B1%BB%E5%9E%8B%E4%B8%8B%E9%9D%A2%E8%AF%B4%E6%B3%95%E6%AD%A3%E7%A1%AE%E7%9A%84%E6%98%AF)
> * [26\. 下面这段代码输出什么？](#26-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [27\. 下面这段代码输出什么？](#27-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [28\. 下面属于关键字的是（）](#28-%E4%B8%8B%E9%9D%A2%E5%B1%9E%E4%BA%8E%E5%85%B3%E9%94%AE%E5%AD%97%E7%9A%84%E6%98%AF)
> * [29\. 下面这段代码输出什么？](#29-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [30\. 下面这段代码输出什么？](#30-%E4%B8%8B%E9%9D%A2%E8%BF%99%E6%AE%B5%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
> * [31\. 31-60题](https://github.com/yqchilde/Golang-Interview/blob/master/31-60.md)

## 1. 下面这段代码输出的内容：

```go
package main

import "fmt"

func main() {
    defer_call()
}

func defer_call()  {
    defer func() {fmt.Println("打印前")}()
    defer func() {fmt.Println("打印中")}()
    defer func() {fmt.Println("打印后")}()

    panic("触发异常")
}
```

**答：输出内容为：**

```shell
打印后
打印中
打印前
panic: 触发异常
```

**解析：**
`defer` 的执行顺序是先进后出。出现panic语句的时候，会先按照 `defer` 的后进先出顺序执行，最后才会执行panic。

## 2. 下面这段代码输出什么，说明原因。

```go
package main

import "fmt"

func main() {
    slice := []int{0, 1, 2, 3}
    m := make(map[int]*int)

    for key, val := range slice {
        m[key] = &val
    }

    for k, v := range m {
    fmt.Println(k, "->", *v)
    }
}
```

**答：输出内容为：**

```shell
// 注：key的顺序无法确定
0 -> 3
1 -> 3
2 -> 3
3 -> 3
```

**解析：**

`for range` 循环的时候会创建每个元素的副本，而不是每个元素的引用，所以 `m[key] = &val` 取的都是变量val的地址，所以最后 `map` 中的所有元素的值都是变量 `val` 的地址，因为最后 `val` 被赋值为3，所有输出的都是3。

## 3. 下面两段代码输出什么？

```go
// 1.
func main() {
    s := make([]int, 5)
    s = append(s, 1, 2, 3)
    fmt.Println(s)
}

// 2.
func main() {
    s := make([]int, 0)
    s = append(s, 1, 2, 3, 4)
    fmt.Println(s)
}
```

**答：输出内容为：**

```shell
// 1.
[0 0 0 0 0 1 2 3]

// 2.
[1 2 3 4]
```

**解析：**

使用 `append` 向 `slice` 中添加元素，第一题中slice容量为5，所以补5个0，第二题为0，所以不需要。

## 4. 下面这段代码有什么缺陷？

```go
func funcMui(x, y int) (sum int, error) {
    return x + y, nil
}
```

**答：第二个返回值没有命名**

**解析：**

在函数有多个返回值时，只要有一个返回值有命名，其他的也必须命名。如果有多个返回值必须加上括号();如果只有一个返回值且命名也需要加上括号()。这里的第一个返回值有命名sum，第二个没有命名，所以错误。

## 5. new() 与 make() 的区别

**解析：**

- `new(T)`  和 `make(T, args)`  是Go语言内建函数，用来分配内存，但适用的类型不用。
- `new(T)` 会为了 `T` 类型的新值分配已置零的内存空间，并返回地址（指针），即类型为 `*T` 的值。换句话说就是，返回一个指针，该指针指向新分配的、类型为 `T` 的零值。适用于值类型，如 `数组` 、 `结构体` 等。
- `make(T, args)` 返回初始化之后的T类型的值，也不是指针 `*T` ，是经过初始化之后的T的引用。 `make()` 只适用于 `slice` 、 `map` 和 `channel` 。

## 6. 下面这段代码能否通过编译，不能的话原因是什么；如果能，输出什么？

```go
func main() {
    list := new([]int)
    list = append(list, 1)
    fmt.Println(list)
}
```

**答：不能通过**

**解析：**

不能通过编译， `new([]int)` 之后的 `list` 是一个 `*int[]` 类型的指针，不能对指针执行 `append` 操作。可以使用 `make()` 初始化之后再用。同样的， `map` 和 `channel` 建议使用 `make()` 或字面量的方式初始化，不要用 `new` 。 

## 7. 下面这段代码能否通过编译，不能的话原因是什么；如果可以，输出什么？

```go
func main() {
    s1 := []int{1, 2, 3}
    s2 := []int{4, 5}
    s1 = append(s1, s2)
    fmt.Println(s1)
}
```

**答：不能通过**

**解析：**

`append()` 的第二个参数不能直接使用 `slice` ，需使用 `...` 操作符，将一个切片追加到另一个切片上： `append(s1, s2...)` 。或者直接跟上元素，形如： `append(s1, 1, 2, 3)`  。

## 8. 下面这段代码能否通过编译，如果可以，输出什么？

```go
var (
    size := 1024
    max_size = size * 2
)

func main() {
    fmt.Println(size, max_size)
}
```

**答：不能通过**

**解析：**

这道题的主要知识点是变量的简短模式，形如：x := 100 。但这种声明方式有限制：

1. 必须使用显示初始化；
1. 不能提供数据类型，编译器会自动推导；
1. 只能在函数内部使用简短模式；

## 9. 下面这段代码能否通过编译？不能的话，原因是什么？如果通过，输出什么？

```go
func main() {
    sn1 := struct {
        age  int
        name string
	}{age: 11, name: "qq"}
	sn2 := struct {
        age  int
        name string
	}{age: 11, name: "11"}

    if sn1 == sn2 {
        fmt.Println("sn1 == sn2")
    }

    sm1 := struct {
        age int
        m   map[string]string
    }{age: 11, m: map[string]string{"a": "1"}}
    sm2 := struct {
        age int
        m   map[string]string
    }{age: 11, m: map[string]string{"a": "1"}}

    if sm1 == sm2 {
        fmt.Println("sm1 == sm2")
    }
}
```

**答：不能通过,invalid operation: sm1 == sm2**

**解析：**

考点是结构体的比较，有几个需要注意的地方：

1. 结构体只能比较是否相等，但是不能比较大小；
1. 想同类型的结构体才能进行比较，结构体是否相同不但与属性类型有关，还与属性顺序相关；
1. 如果struct的所有成员都可以比较，则该struct就可以通过==或!=进行比较是否相同，比较时逐个项进行比较，如果每一项都相等，则两个结构体才相等，否则不相等；

**那有什么是可以比较的呢？**

- 常见的有bool、数值型、字符、指针、数组等

**不能比较的有**

- slice、map、函数

## 10. 通过指针变量p访问其成员变量name,有哪几种方式？

- A. p.name
- B. (&p).name
- C. (*p).name
- D. p->name

**答：A C**

**解析：**

`&` 取址运算符， `*` 指针解引用

## 11. 下面这段代码能否通过编译？如果通过，输出什么？

```go
package main

import "fmt"

type MyInt1 int
type MyInt2 = int

func main() {
    var i int = 0
    var i1 MyInt1 = i
    var i2 MyInt2 = i
    fmt.Println(i1, i2)
}
```

**答：不能通过**

**解析：**

这道题考的是 `类型别名` 与 `类型定义` 的区别
第5行代码是基于类型 `int` 创建了新类型 `MyInt1` ，第6行代码是创建了int的类型别名 `MyInt2` ，注意类型别名的定义是 `=` 。所以，第10行代码相当于是将int类型的变量赋值给MyInt1类型的变量，Go是强类型语言，编译当然不通过；而MyInt2只是int的别名，本质上还是int，可以赋值。
第10行代码的赋值可以使用强制类型转换 `var i1 MyInt1 = MyInt1(i)` 

## 12. 以下代码输出什么？

```go
func main() {
    a := []int{7, 8, 9}
    fmt.Printf("%+v\n", a)
    ap(a)
    fmt.Printf("%+v\n", a)
    app(a)
    fmt.Printf("%+v\n", a)
}

func ap(a []int) {
    a = append(a, 10)
}

func app(a []int) {
    a[0] = 1
}
```

**答：输出内容为：**

```shell
[7 8 9]
[7 8 9]
[1 8 9]
```

**解析：**

因为append导致底层数组重新分配内存了，append中的a这个alice的底层数组和外面不是一个，并没有改变外面的。

## 13. 关于字符串连接，下面语法正确的是？

- A. str := 'abc' + '123'
- B. str := "abc" + "123"
- C. str := '123' + "abc"
- D. fmt.Sprintf("abc%d", 123)

**答：B、D**

**解析：**

在Golang中字符串用双引号，字符用单引号
字符串连接除了以上两种连接方式，还有 `strings.Join()` 、 `buffer.WriteString()` 等

## 14. 下面这段代码能否编译通过？如果可以，输出什么？

```go
const (
    x = iota
    _
    y
    z = "zz"
    k
    p = iota
)

func main() {
    fmt.Println(x, y, z, k, p)
}
```

**答：编译通过，输出：**`**0 2 zz zz 5**` 

**解析：**

iota初始值为0，所以x为0，_表示不赋值，但是iota是从上往下加1的，所以y是2，z是“zz”,k和上面一个同值也是“zz”,p是iota,从上0开始数他是5

## 15. 下面赋值正确的是（）

- A. var x = nil
- B. var x interface{} = nil
- C. var x string = nil
- D. var x error = nil

**答：B、D**

**解析：**

A错在没有写类型，C错在字符串的空值是 `""` 而不是nil。
知识点：nil只能赋值给指针、chan、func、interface、map、或slice、类型的变量。

## 16. 关于init函数，下面说法正确的是（）

- A. 一个包中，可以包含多个init函数；
- B. 程序编译时，先执行依赖包的init函数，再执行main包内的init函数；
- C. main包中，不能有init函数；
- D. init函数可以被其他函数调用；

**答：A、B**

**解析：**

1. init()函数是用于程序执行前做包的初始化的函数，比如初始化包里的变量等；
1. 一个包可以出现多个init()函数，一个源文件也可以包含多个init()函数；
1. 同一个包中多个init()函数的执行顺序没有明确的定义，但是不同包的init函数是根据包导入的依赖关系决定的；
1. init函数在代码中不能被显示调用、不能被引用（赋值给函数变量），否则出现编译失败；
1. 一个包被引用多次，如A import B，C import B，A import C，B被引用多次，但B包只会初始化一次；
1. 引入包，不可出现死循环。即A import B，B import A，这种情况下编译失败；

![image.png](https://cdn.nlark.com/yuque/0/2019/png/517869/1574040068413-cfcc17c2-6f8b-4c1c-b09b-d6d297c9f745.png#align=left&display=inline&height=330&name=image.png&originHeight=419&originWidth=948&size=156149&status=done&width=746)


## 17. 下面这段代码输出什么以及原因？

```go
func hello() []string {
    return nil
}

func main() {
    h := hello
    if h == nil {
        fmt.Println("nil")
    } else {
        fmt.Println("not nil")
    }
}
```

- A. nil
- B. not nil
- C. compilation error

**答：B**

**解析：**

这道题里面，是将 `hello()` 赋值给变量h，而不是函数的返回值，所以输出 `not nil` 

## 18. 下面这段代码能否编译通过？如果可以，输出什么？

```go
func GetValue() int {
    return 1
}

func main() {
    i := GetValue()
    switch i.(type) {
    case int:
        fmt.Println("int")
    case string:
        fmt.Println("string")
    case interface{}:
        fmt.Println("interface")
    default:
        fmt.Println("unknown")
    }
}
```

**答：编译失败**

**解析：**

只有接口类型才能使用类型选择
类型选择的语法形如：i.(type)，其中i是接口，type是固定关键字，需要注意的是，只有接口类型才可以使用类型选择。

## 19. 关于channel，下面语法正确的是（）

- A. var ch chan int
- B. ch := make(chan int)
- C. <-ch
- D. ch<-

**答：A、B、C**

**解析：**

A、B都是申明channel；C读取channel；写channel是必须带上值，所以D错误。

## 20. 下面这段代码输出什么？

- A. 0
- B. 1
- C. Compilation error

```go
type person struct {
    name string
}

func main() {
    var m map[person]int
    p := person{"make"}
    fmt.Println(m[p])
}
```

**答：A**

**解析：**

打印一个map中不存在的值时，返回元素类型的零值。这个例子中，m的类型是map[person]int，因为m中 不存在p，所以打印int类型的零值，即0。

## 21. 下面这段代码输出什么？

- A. 18
- B. 5
- C. Compilation error

```go
func hello(num ...int) {
    num[0] = 18
}

func main() {
    i := []int{5, 6, 7}
    hello(i...)
    fmt.Println(i[0])
}
```

**答：18**

**解析：**

可变参数传递过去，改变了第一个值。

## 22. 下面这段代码输出什么？

```go
func main() {  
    a := 5
    b := 8.1
    fmt.Println(a + b)
}
```

- A. 13.1  
- B. 13
- C. compilation error  

**答：C**

**解析：**

`a` 的类型是`int` ，`b` 的类型是`float` ，两个不同类型的数值不能相加，编译报错。

## 23. 下面这段代码输出什么？

```go
package main

import (  
    "fmt"
)

func main() {  
    a := [5]int{1, 2, 3, 4, 5}
    t := a[3:4:4]
    fmt.Println(t[0])
}
```

- A. 3
- B. 4
- C. compilation error  

**答：B**

**解析：**

- 知识点：操作符 `[i, j]`。基于数组（切片）可以使用操作符 `[i, j]`创建新的切片，从索引 `i` ，到索引 `i` ，到索引 `j` 结束，截取已有数组（切片）的任意部分，返回新的切片，新切片的值包含原数组（切片）的 `i` 索引的值，但是不包含 `j` 索引的值。`i` 、`j` 都是可选的，`i` 如果省略，默认是0，`j` 如果省略，默认是原数组（切片）的长度。`i` 、`j` 都不能超过这个长度值。

- 假如底层数组的大小为 k，截取之后获得的切片的长度和容量的计算方法：**长度：j-i，容量：k-i**。

  截取操作符还可以有第三个参数，形如 [i,j,k]，第三个参数 k 用来限制新切片的容量，但不能超过原数组（切片）的底层数组大小。截取获得的切片的长度和容量分别是：**j-i、k-i**。

  所以例子中，切片 t 为 [4]，长度和容量都是 1。

## 24. 下面这段代码输出什么？

```go
func main() {
    a := [2]int{5, 6}
    b := [3]int{5, 6}
    if a == b {
        fmt.Println("equal")
    } else {
        fmt.Println("not equal")
    }
}
```

- A. compilation error  
- B. equal  
- C. not equal 

**答：A**

**解析：**

Go中的数组是值类型，可比较，另外一方面，数组的长度也是数组类型的组成部分，所以 `a` 和 `b` 是不同的类型，是不能比较的，所以编译错误。

## 25. 关于 cap() 函数的适用类型，下面说法正确的是()

- A. array
- B. slice
- C. map
- D. channel

**答：A、B、D**

**解析：**

cap()，cap() 函数不适用 map

## 26. 下面这段代码输出什么？

```go
func main() {  
    var i interface{}
    if i == nil {
        fmt.Println("nil")
        return
    }
    fmt.Println("not nil")
}
```

- A. nil
- B. not nil
- C. compilation error  

**答：A**

**解析：**

当且仅当接口的动态值和动态类型都为 nil 时，接口类型值才为 nil

## 27. 下面这段代码输出什么？

```go
func main() {  
    s := make(map[string]int)
    delete(s, "h")
    fmt.Println(s["h"])
}
```

- A. runtime panic
- B. 0
- C. compilation error 

**答：B**

**解析：**

删除 map 不存在的键值对时，不会报错，相当于没有任何作用；获取不存在的减值对时，返回值类型对应的零值，所以返回 0。

## 28. 下面属于关键字的是（）

- A. func
- B. struct
- C. class
- D. defer

**答：A、B、D**

## 29. 下面这段代码输出什么？

```go
func main() {  
    i := -5
    j := +5
    fmt.Printf("%+d %+d", i, j)
}
```

- A. -5 +5
- B. +5 +5
- C. 0  0

**答：A**

**解析：**

`%d`表示输出十进制数字，`+`表示输出数值的符号。这里不表示取反。

## 30. 下面这段代码输出什么？

```go
type People struct{}

func (p *People) ShowA() {
    fmt.Println("showA")
    p.ShowB()
}
func (p *People) ShowB() {
    fmt.Println("showB")
}

type Teacher struct {
    People
}

func (t *Teacher) ShowB() {
    fmt.Println("teacher showB")
}

func main() {
    t := Teacher{}
    t.ShowB()
}
```

**答：teacher showB**

**解析：**

知识点：结构体嵌套。

在嵌套结构体中，People 称为内部类型，Teacher 称为外部类型；通过嵌套，内部类型的属性、方法，可以为外部类型所有，就好像是外部类型自己的一样。此外，外部类型还可以定义自己的属性和方法，甚至可以定义与内部相同的方法，这样内部类型的方法就会被“屏蔽”。这个例子中的 ShowB() 就是同名方法。
