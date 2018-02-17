# Attributes of the  Directive :- 
animationeffect - slide the element or apply background <br/>
params <br/>

## animationeffect
```````
animationeffect : backgroundTransition | Slide                  

```````
backgroundTransition is related to the background animations.<br/>
Slider for sliding


## params include:
speed - duration in which the animation to be completed <br/>
percentageOfArea - part of the area in th element to be covered in each iteration <br/>
direction - the direction in which the animation to be applied <br/>
backgroundColor - to set the backgroundcolor of the element <br/>



## direction

```
direction : topBottom | leftRight | rightLeft | bottomTop | 
            leftSlideDown   | leftSlideUp  | 
            RightSlideDown  | RightSlideUp | 
            BottomSlideDown | BottomSlideUp |
            SlideDown       | SlideUp
```

topBottom,leftRight,rightLeft,bottomTop are related to 'backgroundTransition'<br/>
SlideDown, SlideUp are related to slide the element from top<br/>
leftSlideDown,leftSlideUp are related to slide the element from left<br/>
RightSlideDown,RightSlideUp are related to slide the element from right<br/>
BottomSlideDown, BottomSlideUp are related to the slide the element from bottom<br/>

Speed of Each Iteration : speed/percentageOfArea
