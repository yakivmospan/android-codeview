```java
Intent intent = new Intent(this, ActivityA.class);
intent.setFlags(Intent.FLAG_ACTIVITY_CLEAR_TOP);
startActivity(intent);
```