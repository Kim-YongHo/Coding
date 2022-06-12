## 코드업 01~20

### 01 **[기초-출력] 출력하기01**

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello");
    }
}
```

### 02 **[기초-출력] 출력하기02**

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

### 03 **[기초-출력] 출력하기03**

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello");
        System.out.println("World");
    }
}
```

### 04 **[기초-출력] 출력하기04**

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("\'Hello\'"); // 역슬랙시를 'or" 출력 가능
    }
}
```

### 05 **[기초-출력] 출력하기05**

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("\"Hello World\""); // 역슬랙시를 'or" 출력 가능
    }
}
```

### 06 **[기초-출력] 출력하기06**

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("\"!@#$%^&*()\""); // 역슬랙시를 'or" 출력 가능
    }
}
```

### 07 **[기초-출력] 출력하기07**

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("C:\\Download\\hello.cpp"); //역슬랙시를 2번 사용 / 하나 출력 가능
    }
}
```

### 08  **[기초-출력] 출력하기08**

```java
public class Main {
    public static void main(String[] args) {
        //유니코드 : 국제적인 문자 코드 규약
        System.out.printf("\u250C\u252C\u2510\n");
        System.out.printf("\u251C\u253C\u2524\n");
        System.out.printf("\u2514\u2534\u2518\n");
    }
}
```

### 09

```java

```

### 10 **[기초-입출력] 정수 1개 입력받아 그대로 출력하기** 

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int x = sc.nextInt();

        System.out.println(x);

    }
}
```

