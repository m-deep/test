classDiagram
  class Dog {
    <<Class>>
    - Name: String
    - Age: int
    - Breeder: String

    + Bark(): void
    + Run(): void
  }
