# Images service

## Функциональность сервиса

Программа должна запускать число потоков, равное количеству ядер процессора вашего компьютера.

- Используя библиотеку Imgscalr, уменьшать изображение без потери качества. 

```java
public static BufferedImage resize(BufferedImage src, int targetWidth, 
        int targetHeight, BufferedImageOp... ops);
```