[Pirate|eyeCount: Int|raid();pillage()|
  [beard]--[parrot]
  [beard]-:>[foul mouth]
]

.. uml::
   :alt: Software Design Diagram

   @startuml
   abstract class Dog
   class Labrador

   Dog <|-- Labrador
   @enduml