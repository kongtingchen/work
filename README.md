# work
## 一、String, StringBuffer and StringBuilder

**1. 可变性** 

- String 不可变
- StringBuffer 和 StringBuilder 可变

**2. 线程安全** 

- String 不可变，因此是线程安全的
- StringBuilder 不是线程安全的
- StringBuffer 是线程安全的，内部使用 synchronized 进行同步

**3. 执行速度** 

- String < StringBuffer < StringBuilder

## 二、Object类的几个方法

- equals() 
- toString()
- wait()
- notify()
- notifyAll()
- hashCode()
- clone()
- getClass()
- finalize()

## 三、反射
**1、什么是反射**
- 在运行时，能通过Reflection APIs，对于任意一个类，能获取该类的属性和方法（包括private），对于任意一个对象，能调用它的任意方法和属性。

**2、为什么要反射**
- 对于类，在运行时，能获取该类的Class对象，该类的属性、方法和构造器，能新建类的实例
- 对于对象，在运行时，能检测该对象所属的类，能调用该类的任意属性、方法和构造器
- 动态代理

**3、获得class多线的方法**
- 类.class;   例如：Father.class;  Integer.TYPE;
- 对象.getClass()； 例如：f.getClass();
- Class.forName(类全名)；例如： Class.forName("com.mysql.jdbc.Driver")
- 类加载器ClassLoader，对象.getClass().getClassLoader.loadClass(类全名)

## 四、
