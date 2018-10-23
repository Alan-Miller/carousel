# Custom carousel

This is a carousel I made in React as a study. It uses React state, inline styling logic, and an interval to define how and when photos should rotate. 

The Back and Forward buttons change photo manually and restart the interval. `componentWillUnmount` is used to clear the interval when the component unmounts.

The carousel expects at least 3 photos to behave correctly.