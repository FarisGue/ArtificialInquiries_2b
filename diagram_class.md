# Diagramme de classes

Ce diagramme représente les principales données utilisées dans l'application
**Human or AI? – Knowledge Task Mapper**.

```mermaid
classDiagram

class Task {
  +String id
  +String name
  +String importance
  +String frequency
  +String assistanceLevel
  +String explanation
}

class AIRole {
  +String id
  +String name
}

class HumanResponsibility {
  +String id
  +String name
}

class Reflection {
  +String id
  +String summary
}

class TaskManager {
  +List~Task~ tasks
  +addTask()
  +editTask()
  +deleteTask()
  +saveToLocalStorage()
  +loadFromLocalStorage()
  +calculateStatistics()
}

Task "1" --> "*" AIRole : uses
Task "1" --> "*" HumanResponsibility : keeps
Task "1" --> "1" Reflection : generates
TaskManager "1" --> "*" Task : manages
