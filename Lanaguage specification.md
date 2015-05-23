Classes:
    /com/example/tutorial/package
    C ClassName : ExtendingClass, ImplementingClass, ImplementingClass, ...
      $P StaticProperty: String
      P NormalProperty: int
      
      F @ (String constructorArgument)
      F dispose (): void

Interfaces:
    I InterfaceName : ExtendingInferface, ExtendingInterface, ...
      F getName (): String
      F getColour (): Colour
      F setName (String name): void
      F setColour (Colour colour): void

Enums:
    E Colour
      - RED (0)
      - BLUE (1)
      - YELLOW (2)
      - GREEN (3)
      
      P num: int
      F @ (int num)
