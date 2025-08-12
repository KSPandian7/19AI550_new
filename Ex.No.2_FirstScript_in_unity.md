# Ex.No: 2  Welcome Script in Unity
### DATE:                                                                            
### REGISTER NUMBER : 212222240052
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```cs
using UnityEngine;

public class sample : MonoBehaviour
{
    void Start()
    {
        print("Welcome to Unity");
    }
    void Update()
    {
        //print("AI for Games");
    }
}

```
### Output:
<img width="1919" height="968" alt="image" src="https://github.com/user-attachments/assets/1f8c6827-484c-4f48-81b9-576542b6d7ea" />



### Result:
Thus the welcome script was printed on Console Window  sucessfully.

