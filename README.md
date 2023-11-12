<!-- Guided Practice  Testing Methods

? Scenario: 
You were hired by a global hotel chain to redesign the functionality of the button panel on their elevators. The goal is to replace the outdated panel in over 1,200 different locations. Before you begin coding, you should 

*make a list of all the ways these panels should be tested to make sure they are working correctly and respond to unexpected input in a way that makes sense. 

?Task: 
*Remember to consider happy and unhappy paths! 
*Create Unit(as many as possible),
*Create One: Integration, Functional, Acceptance test. (make sure to label these test)


? Unit test 

* Happy Test: 

    -When floor buttons are pressed they light up white, and the white color goes away once the elevator reaches the requested floor 
    -When button is pressed, the elevator ascends / descends to the selected floor 
    -Multiple buttons can be pressed 
    -When a button is pressed, that elevator prioritizes floor selections that are also in alignment with the directio(up/down) of the initial button pressed. 
        i.e: 
        If I'm on floor 5 and press floor 2, and another passenger presses 3, while another presses 7; the elevator will proceed to go to floor 3 then 2, then it would finally ascend to floor 7. 
        
    -The elevator does not allow for passengers to select certain buttons to access floors such as the basement, unless a physical key is inserted. 
    -The elevator doors take 4 seconds to close , unless motion scanners pick up the presences of a person or object. 
    -If the elevator scanners pick up the motion of a person or object, they immediately re-open the doors to allow entry. 
    -When the alarm button is pressed, a loud discrete ringing noise occurs. 
    - When the emergency button is pulled, the elevator comes to a slow stop and stays still until the button is pressed. 
    -
    





-->
