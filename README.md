Using System;
Using UnityEngine;

Public Class TextClass : MonoBehaviour
{
    Public KeyCode m_Key
    
    Public Void Awake()
    {
      m_Key = KeyCode.J;
    }
    
    
    
    Public Void Update()
    {
       if(Input.anykeydown)
       {
        Debug.Log("Hello World");
       }
    }
}
