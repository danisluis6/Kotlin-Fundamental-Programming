# Kotlin-Fundamental-Programming [![Build Status](https://travis-ci.org/nomensa/jquery.hide-show.svg)](https://travis-ci.org/nomensa/jquery.hide-show.svg?branch=master)

   ```Learn and accelerate programming quickly.```

<p><i>Write better Android apps <b>faster</b> with Kotlin. Kotlin is a modern statically typed programming language that will boost your productivity and <b>increase</b> your developer happiness.</i></p>
  
## Understand `main`

```java
public static void main(String[] args) {
    System.out.print("Welcome to Kotlin");
}
```

```kt
fun main(args:Array<String>) {
    print("Welcome to Kotlin")
}
```

## Understand declare variable static public in class

```java
public static String tag = .class.getSimpleName()
public static final String ACCESS_WIFI_STATE = 0
```

```kt
companion object {
    @JvmStatic var tag:String = MainActivity.javaClass.simpleName
    const val WIFI_CODE:Int = 0
}
```
