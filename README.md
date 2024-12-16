This repository demonstrates a common misconception in Ruby concerning instance variable access.  The example shows a class with a getter method for an instance variable.  While the getter allows reading the variable's value, direct assignment through the getter does not modify the internal instance variable.  This behavior can be surprising to those coming from languages with different getter/setter conventions.