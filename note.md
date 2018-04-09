## JAVA编译和运行
JAVA编译器不是将程序翻译成机器语言，而是将程序翻译成一种称为字节码的语言。字节码是Java虚拟机虚构的机器语言，但是Java虚拟机很容易将字节码翻译成计算机的机
器语言。
* `javac helloWorld.java` 编译java程序，将程序编译成字节码
* `java helloworld` 运行java程序，对编译的java程序运行java字节码解释器。 

## Scanner类的控制台输入
* 首先需要导入包 `import java.util.Scanner`
* 再创建一个Scanner类 `Scanner sc = new Scanner(System.in);`
* .nextInt()/.nextDouble()/.nextFloat()/nextBoolean()/.next()读入一个单词，直到空格分隔符/.nextLine()读入一行，直到换行符
