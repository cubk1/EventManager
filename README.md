# EventManager

Reflective Event System made for create minecraft client form scratch

## Create Instance
```java
EventManager eventManager = new EventManager();
```

## Register
```java
Test test = new Test();
eventManager.register(test); // register
eventManager.unregister(test); // unregister
```

## Call Event
```java
eventManager.call(new UpdateEvent());
```