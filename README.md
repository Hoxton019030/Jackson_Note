# Jackson Note

示範用的Json資料放在`demo.json`裡面



# 如何使用Jackson 

1. 創建objectMapper

```java
@Test
void JacksonTutorial(){
    ObjectMapper objectMapper = new ObjectMapper();

}
```

ObjectMapper用來幫助我們將Json與Java的Object互相轉換

```mermaid
graph LR;;
Json <---> Java_Object
Java_Object <---> Json

```



2. 創建JsonNode物件

```java
@Test
void JacksonTutorial() throws JsonProcessingException {
    String demo = actuator.getActuatorThreadInformation();
    ObjectMapper objectMapper = new ObjectMapper();
    JsonNode jsonNode = objectMapper.readTree(demo);
}
```
