# Práctica 1: Introducción a Unity

## Introducción

El objetivo de esta práctica es el de familiarizarnos con el entorno de desarrollo del motor Unity. Para ello los pasos realizados han sido los siguientes:

* Se han incluidos objetos 3D básicos (Un cubo y un cilindro)
* Se ha incluido en el proyecto el paquete Starter Assets.
* Se ha incluido un objeto libre de la Asset Store que no sea de los Starter Assets. Concretamente un coche del paquete Low Poly Car Vehicle Pack.
* Cada objeto tiene una etiqueta que lo identifique.
* Se han utilizado prefabs de Starter Asset Third Person
* Se ha agregado un script que escriba en la consola los objetos que se han utilizado.

## Script utilizado
El script utilizado ha sido el siguiente:

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class ShowName : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        Debug.Log("Soy un objeto llamado " + gameObject.name);  
    }
}
```

## Gif de la escena
A continuación se adjunta un gif con la escena realizada