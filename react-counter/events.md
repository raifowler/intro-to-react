**Questions**

> In your own words, explain the React core concept of encapsulation. Discuss why this React principle is important in application development.

A: Encapsulation is the concept of keeping your components independent of one another and reusable. It's the concept of breaking your code up into single responsibility sections(components) and creating ways for those sections to communicate with one another without allowing each other to control one anothers state. Each component should control it's own state and include props that can be passed to other components for the purpose of callbacks to the original component so it can update it's own state. 