# 📦 Task Manager – Estructuras de Datos

Este módulo contiene todas las estructuras de datos personalizadas utilizadas en el proyecto **Task Manager**.

## 🧠 Estructuras implementadas

* 🔄 `CustomQueue` – Cola simple tipo FIFO
* 🏁 `PriorityQueue` – Cola con prioridad (entera)
* 🔀 `CustomStack` – Pila tipo LIFO
* 📋 `UserTaskList` – Lista personalizada de tareas
* 🌲 `SubtaskTreeService` – Árbol de subtareas con nodos

## 🛠 Tecnologías

* Java 22
* Maven

## 📁 Estructura del paquete

```
umg.edu.gt.structures
├── queue
├── stack
├── tree
└── list
```

## 📦 Dependencia en otros módulos

Este módulo se utiliza como dependencia en el proyecto principal `task-manager-springboot`.

### 🔻 Ejemplo para usar en el `pom.xml` del proyecto principal:

```xml
<dependency>
    <groupId>umg.edu.gt</groupId>
    <artifactId>task-manager-structures</artifactId>
    <version>1.0.0</version>
</dependency>
```

## 👨‍💻 Autor

* Carlos Valiente 
