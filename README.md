

# Jetpack Compose List Demo
 

## Summary
- **Summary:**  Android App showing list with the help Jetpack Compose UI 
- **Created Date:** 28 June 2023
- **Last modified:** 28 June 2023 

## Feature
- Top Title for the List
- Row with Image and Description.
- Its Scrollable 



### Technology Used
- Kotlin
- Jetpack Compose
- LazyColumn by Compose
- Card by Compose
- Surface by Compose Material

### Backend Details

- **Webservice** : offline


#### Example Model


```
{
        "id": 3291839,
        "name": "Title of Plant",
        "description": "Some lorem ipsum description",
        "imageRes": 0
    }

```

```
data class Plant(
    val id: Int,
    val name: String,
    val description: String,
    val imageRes : Int
)
```

- **Library Imports**
  
```


    implementation 'androidx.activity:activity-compose:1.5.1'
    implementation platform('androidx.compose:compose-bom:2022.10.00')
    implementation 'androidx.compose.ui:ui'
    implementation 'androidx.compose.ui:ui-graphics'
    implementation 'androidx.compose.ui:ui-tooling-preview'
    implementation 'androidx.compose.material3:material3'

```


#### Project Structure



<img src="https://github.com/ganeshroman/User_List/blob/c0c8f88fa66d3e0b603f12a5c8577414ba55d06d/Screenshot%202023-06-28%20at%204.18.52%20PM.png" width="250" height="450">


#### Screenshots


<img src="https://github.com/ganeshroman/User_List/blob/6fc1f11e89713147eec613d967bd5bf35490fa8d/Screenshot_20230722_134811.png" width="250" height="450">










