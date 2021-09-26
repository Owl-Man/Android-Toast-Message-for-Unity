# Android Toast Message for Unity

Drag the **ToastSystem.cs** script to your scripts folder in Unity project. Now you can call the **Send** method, which is located in the **ToastSystem** static class, and specify your text in the parameter.

Example:

    using UnityEngine;
    
    public class Test : MonoBehaviour 
    {
        private void Start()
        {
            ToastSystem.Send("toast message");
        }
    }
