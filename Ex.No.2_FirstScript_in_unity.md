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
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    void Start()
    {
        //print("Welcome to Unity");
        Vector3 pos = transform.position;
        transform.position = new Vector3(0, 0.2f, 0);
    }

    // Update is called once per frame
    void Update()
    {
        print("AI for Games");
    }
}

```
### Output:
<img width="1919" height="1079" alt="Screenshot 2025-08-11 093848" src="https://github.com/user-attachments/assets/7eea0764-7d38-44a2-8645-55f20476f69c" />



### Result:
Thus the welcome script was printed on Console Window  sucessfully.

