## 코드업 11~20

### 11 **[기초-입출력] 문자 1개 입력받아 그대로 출력하기** 

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String str = sc.next();

        System.out.println(str);

    }
}
```

### 12 **[기초-입출력] 실수 1개 입력받아 그대로 출력하기**

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        float x = sc.nextFloat();

        System.out.println(x);

    }
}
```

### 13 **[기초-입출력] 정수 2개 입력받아 그대로 출력하기**

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int x = sc.nextInt();
        int y = sc.nextInt();

        System.out.println(x + " " + y); // +로 연결해서 출력

    }
}
```

### 14  **[기초-입출력] 문자 2개 입력받아 순서 바꿔 출력하기**

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int x = sc.nextInt();
        int y = sc.nextInt();
        int temp;

        temp = x;
        x = y;
        y = temp;

        System.out.println(x + " " + y); // +로 연결해서 출력
    }
}
```

### 15 **[기초-입출력] 실수 입력받아 둘째 자리까지 출력하기**

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        float x = sc.nextFloat();

        System.out.printf("%.2f", x); //출력 자릿수를 제한
    }
}
```

### 16

```java

```

### 17 **[기초-입출력] 정수 1개 입력받아 3번 출력하기**

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int x = sc.nextInt();
        
        System.out.printf("%d %d %d", x, x,x); //출력 자릿수를 제한
    }
}
```

### 18 **[기초-입출력] 시간 입력받아 그대로 출력하기**

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String str = sc.next();

        String[] temp = str.split(":"); //split를 활용해 : 로 시간과 분 구별 

        System.out.printf("%s:%s", temp[0], temp[1]); 
    }
}
```

### 19 **[기초-입출력] 연월일 입력받아 그대로 출력하기**

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String str = sc.next();

        String[] temp = str.split("\\."); //오류로 인해 \\. 입력

        int x = Integer.parseInt(temp[0]);
        int y = Integer.parseInt(temp[1]);
        int z = Integer.parseInt(temp[2]);

        System.out.printf("%04d.%02d.%02d", x,y,z); // 3월을 03 or 3로 입력에 대비
    }
}
```

### 20 **[기초-입출력] 주민번호 입력받아 형태 바꿔 출력하기**

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String str = sc.next();

        String[] temp = str.split("-");

        System.out.printf("%s%s", temp[0], temp[1]);
    }
}
```
