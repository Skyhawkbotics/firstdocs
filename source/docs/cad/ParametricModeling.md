# Parametric Modeling

Parametric modeling is a design method where dimensions like length, angle, and other parameters fully define each action. In Fusion, parametric modeling is built in through the timeline. Every action you do is stored on the timeline. In simple terms, you build your model step-by-step, and each step remembers how it was created, so you can change dimensions or features later and the entire model updates accordingly.

## How Parametric Modeling Works
In Fusion, parametric modeling works using a timeline, sketches, features, and constraints:

### Sketch + Constraints
* You start with a 2D sketch
* You draw shapes like circles, rectangles, etc
* You add dimensions (like "this should be 10 mm") to control the size
* You add constraints (e.g. "horizontal", "equal", "tangent") that control how the shapes interact 
!!! example
    Draw a rectangle with lines, constrain two sides to be equal, and set the width to 40 mm. Now it's always a square, and you can change its size by editing that 40 mm value
### Features
  * After sketching, you turn sketches into 3D shapes using tools like:
    * Extrude: Pull a 2D shape into 3D
    * Revolve: Spin a sketch around an axis to make round parts
    * Loft, Sweep, etc...
### Timeline History
  * Every operation (sketch, extrude, fillet, etc.) is recorded on the timeline
  * You can go back in time to edit earlier steps, and Fusion will automatically recalculate all later steps

  ![](../assets/fusion360/timeline.png)

## Pros and Cons of Parametric Modeling

### Pros
  1. Easy to Modify
      * You can edit dimensions or features and the entire model updates automatically
      * Great for iterating designs quickly
  2. Maintains Design Features
      * Relationships between features (e.g., always-centered holes) remain intact even when the design changes
      * Other modifications, such as fillets, also persist when changes are made
  3. Timeline + History Editing
      * Fusion's timeline lets you go back and change earlier steps without redoing the model
  4. Precision
      * It's easier to be accurate and apply real-world rules (like symmetry, equal lengths, tangents)
### Cons
 1. Steeper Learning Curve
     * Understanding constraints and timeline editing can be confusing at first
     * New users may struggle with debugging why something breaks when editing or why a sketch isn't fully defined
 2. Slower for Quick Edits
     * For quick, one-off models, fully constraining everything is slower than just guesstimating it
 3. Timeline Mess
     * In Fusion, long timelines with many features can be hard to edit
     * Dependencies between features can be break easily if not organized well
