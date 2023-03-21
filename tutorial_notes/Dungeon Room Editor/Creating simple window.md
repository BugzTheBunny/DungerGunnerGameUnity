# Section 5 - Video 8.

- [Refference to the API of the MenuItem](https://docs.unity3d.com/ScriptReference/MenuItem.html) - helps to create windows.

- Usage example:
`This will create an option to create an empty window.`
    ```
    using System.Collections;
    using System.Collections.Generic;
    using UnityEngine;
    using UnityEditor;
    public class RoomNodeGraphEditor : EditorWindow
    {
        [MenuItem("Toom Node Graph Editor", menuItem = "Window/Dungeon Editor/ Room Node Graph Editor")]

        private static void OpenWindow() {
            GetWindow<RoomNodeGraphEditor>("Room Node Grap Editor");
        }
    }
    ```
    