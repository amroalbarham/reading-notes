

***Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:***
   - **Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.**
   - **Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)**
   - **Cookies are limited to about 4 KB of data — enough to slow down your application , but not enough to be terribly useful.**





### Transforms
  **2D Transforms :**
  ***Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.***
    
   -  **2D Rotate:The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.**
   - **2D Scale:Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger**
   - **2D Translate: The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.**
   - **2D Skew: The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis.**

### Transitions   
  + ***Transitions : The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties.***
  + ***Transition Duration : The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). ***
  + ***Transition Timing : The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration.***
  + ***Transition Delay : On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property. The delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing.***
  


 