# Java学习笔记

1. JDK中包含JRE和开发工具集（如Javac编译工具），JRE中包含JVM和其他标准类库
2. .java文件 --> javac --> .class文件 --> java.exe --> result
3. java注释分为单行、多行、文档注释，其中多行注释不能嵌套多行注释，但是多行注释可以嵌套当行注释
4. 命名规则， 包名全部小写，类名接口名方法名首字母大写，变量名第二个首字母大写，常量名全部大写用下划线相连
5. java变量未初始化不能使用
6. Java中也有隐式类型转换，但只能进行“提升”的转换，比如float -> doubel, int -> long，但是对于精度丢失的转换不支持，比如float -> int这种。此外char可以向int, float, double这种数据转换，boolean类型不支持转换.
7. short,byte,char之间运算时，都会转为int，甚至是byte+byte的情况
8. 浮点数默认是double类型的，因此初始化float时要用1.23f
9. 取余操作之间按正数取余进行，最后结果的符号与被余数的符号相同
10. ++ += 等操作不会该边数据本身的类型，如short st = 1, st++还是short型，st = st + 1, 此时编译无法通过

