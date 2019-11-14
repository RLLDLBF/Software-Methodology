# Software-Methodology
This is the repo for Software Methodology of 2019.

# Requirement
1. 大家的第四次作业安排在表格 se_homework_作业安排.xlsx
链接：https://docs.qq.com/sheet/DZUdVUEZqUXJGaXpm 
2. 大家需要在线编辑表格到all_api_map_benchmark.xlsx
链接：https://docs.qq.com/sheet/DZXRPWWNLc0lNTlZM?tab=BB08J3&c=A1A0A0
3. 提交代码到github：https://github.com/zjzh/sehomework.git （命名规则见readme）
4. 具体作业要求在ppt 软件方法学作4说明.ppt

# What to do?
## My job
学号 | 姓名 | sheet名，行号 | sheet名，行号 | sheet名，行号 | sheet名，行号 | sheet名，行号
:-: | :-: | :-: | :-: | :-:| :-: | :-: 
MF1933099 | 卫昱阳 | LinkedList,2 | Arrays,242 | ArrayList,2 | ArrayList,118 | Integer,102

## backup

### LinkedList,2
#### java
```
java.util.LinkedList$ public E pollFirst ()
```
#### swift
```
ArraySlice$mutating func popFirst() -> Element?
ArraySlice$@discardableResult mutating func removeFirst() -> Element
Array$@discardableResult mutating func removeFirst() -> Element
ContiguousArray@discardableResult mutating func removeFirst() -> Element
```

### Arrays,242
#### java
```
java.util.Arrays$public static void sort (int[] a)
```
#### swift
```
NSMutableArray$func sort(_ compare: (Any, Any, UnsafeMutableRawPointer?) -> Int, context: UnsafeMutableRawPointer?)
NSMutableArray$func sort(using sortDescriptors: [NSSortDescriptor])
NSMutableArray$func sort(options opts: NSSortOptions = [], usingComparator cmptr: (Any, Any) -> ComparisonResult)
Array$mutating func sort()
```
### ArrayList,2
#### java
```
java.util.ArrayList$ public Iterator<E> iterator ()
```
#### swift
```
ContiguousArray$func makeIterator() -> IndexingIterator<ContiguousArray<Element>>
Array$func makeIterator() -> IndexingIterator<Array<Element>>
```
### ArrayList,118
#### java
```
java.util.ArrayList$ public E remove (int index)
```
#### swift
```
ContiguousArray$@discardableResult mutating func remove(at index: Int) -> Element
Array$@discardableResult mutating func remove(at index: Int) -> Element
```
### Integer,102
#### java
```
java.lang.Integer$ public float floatValue ()
```
#### swift
```
NSNumber$var floatValue: Float { get }
```

