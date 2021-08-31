## 了解TypeScript

1、了解TypeScript和JavaScript之间的关系

2、知道你在使用什么TypeScript选项

3、了解 代码生成与类型检查是独立的

4、适应结构化类型

5、限制 any 类型的使用

## TypeScript的类型系统

6、使用你的编辑器来询问和探索类型系统

充分使用编辑器的language service功能（类型提示，类型检查，类型推倒，自动补全，类型定义跳转)

7、将类型看作值的集合

8、知道如何判断符号是否在类型空间或值空间中

9、优先选择类型声明而不是类型断言

10、避免对象包装类型(字符串，数字，布尔，符号，BigInt)

11、认识超额属性检查的极限

12、使用类型操作和泛型以避免重复自己

13、了解类型和接口之间的区别

14、使用类型操作和泛型避免重复自己

15、为动态数据使用索引签名（Index signature）

16、优先使用 Arrays、Tuple、ArrayLike而非number index signatures

17、使用readonly来避免mutation造成的错误

18、使用Mapped Type来实现值和类型的同步

## 类型推断

19、避免滥用类型推导

20、不同的类型使用不同的变量

21、理解 Type Widening

22、理解Type Narrowing

23、一次性定义所有对象

24、在使用别名时（Aliases）保持一致

25、使用异步函数（async）代替Callback

26、理解在类型推断中如何使用上下文

27、使用函数构造和库来帮助类型流

## 类型设计

28、优先使用总是表示有效状态的类型

29、接受的要自由，生产的要严格

30、不要在文档中重复类型信息

31、将空值推到类型的外围

32、选择union of Interfaces而不是Interfaces of union

33、使用更细化的string类型，优先考虑使用string literal union

34、相比不准确的类型宁愿考虑使用不完备的类型 

35、从API和Specs生成类型，而不是数据

36、使用问题域语言的名称类型

37、使用brands来模拟nominal typing

## 处理 any

38、对any类型使用最窄的可能范围

39、使用更细化的 any

40、在类型良好的函数中隐藏不安全的类型断言

41、理解进化的any

42、对于未知类型的值，使用unknown代替any

43、选择类型安全的 Monkey patch （补丁）方法

44、使用type-coverage测试type的覆盖率

## 类型声明和@types

45、把TypeScript和@types放到devDependencies中

46、了解类型声明中涉及的三个版本

47、导出公共API中出现的所有类型

48、使用TSDoc作为API注释

49、为callback提供this的类型

50、优先选择条件类型而不是重载声明

51、尽量避免用户对@types的依赖，不要强制web用户依赖NodeJS的types

52、注意测试类型的陷阱

## 编写并运行你的代码

53、优先考虑使用Javascript的语言特性而非Typescript独有的语言特性

54、知道如何迭代对象

55、理解DOM层次结构

56、要依靠 private 来隐藏信息

57、使用sourcemap去debug Typescript 程序

## 迁移到 TypeScript

58、编写现代JavaScript

59、使用@ts-check和JSDoc来试验TypeScript

60、使用allowJs混合TypeScript和JavaScript

61、一个模块一个模块地转换依赖图

62、在启用noImplicitAny之前不要认为迁移已经完成
