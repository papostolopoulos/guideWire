Requirements:
InVision account (FREE)
https://www.invisionapp.com

Description:
Create a simple HTML web page that contains a button that can be styled using two different themes: Business and Consumer. You will create an external style.css that will define the characteristics which match the supplied designs. The CSS needs to use custom properties that can be modified to change the overall styling globally. Send a .zip file with all the required files. Please note - we are looking for the example button to interactively work with the different states.

InVision designs:
https://guidewire.invisionapp.com/share/49Q0LPLJQCM
PW: gwcode2019

Example
:root {
  --main-bg-color: coral;
  --main-txt-color: blue; 
  --main-padding: 15px; 
}

#div1 {
  background-color: var(--main-bg-color);
  color: var(--main-txt-color);
  padding: var(--main-padding);
}

#div2 {
  background-color: var(--main-bg-color);
  color: var(--main-txt-color);
  padding: var(--main-padding);
}
