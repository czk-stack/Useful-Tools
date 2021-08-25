# List转Object[]
```java
        List<Integer> list = new ArrayList<>();
        list.add(1);
        list.add(2);
        list.add(3);
        Object[] array = list.toArray();
        
        // System.out.println(array.length);
        // for(int i =0; i < 3; i++){
        //     System.out.println(array[i]);
        // }
```

# List 转 Integer[]
```java
        List<Integer> list = new ArrayList<>();
        list.add(1);
        list.add(2);
        list.add(3);
        Integer[] array = new Integer[list.size()];
        array = list.toArray(array);

        // System.out.println(array.length);
        // for(int i =0; i < 3; i++){
        //     System.out.println(array[i]);
        // }
```
