# GamePhysicsTutorial

Project Repo for the Game Physics in... Series. The following are currently implemented within the repo:

| [_Game Physics in One Weekend_](https://www.amazon.com/gp/product/B08RXT38YN)  | [_Game Physics: The Next Week_](https://www.amazon.com/gp/product/B08RXSCKZ8) | [_Game Physics: The Rest of Your Life_](https://www.amazon.com/gp/product/B08RXQPXD1) |
| ------------- | ------------- | ------------- |
| <li>- [X] The Vector Classes </li>              |
| <li>- [X] The Matrix Classes </li>              | 
| <li>- [X] The Quat Classe </li>                 |   
| <li>- [X] Bodies </li>                          |
| <li>- [ ] Gravity </li>                         |         
| <li>- [ ] Gravity as an Impulse </li>           |
| <li>- [ ] Collision </li>                       |
| <li>- [ ] Contacts and Projection Method </li>  |                      
| <li>- [ ] Conservation of Momentum </li>        |                  
| <li>- [ ] Elasticity </li>                      |
| <li>- [ ] Angular velocity  </li>               |         
| <li>- [ ] General Impulses </li>                |
| <li>- [ ] Add Angular Collision Impulse </li>   |
| <li>- [ ] Friction </li>                        |
| <li>- [ ] Continuous Collision Detection </li>  |
| <li>- [ ] Time of Impact </li>                  |
| <li>- [ ] The Bounds Class </li>                |
| <li>- [ ] Broadphase and Narrowphase </li>      | 



Original Readme from [Game Physics In One Weekend book series](https://gamephysicsweekend.github.io/)

# VulkanRenderer

This is a very basic renderer that is meant to be used in conjuction with the [Game Physics In One Weekend book series](https://gamephysicsweekend.github.io/).

It is currently only targeted for Windows 10 and Visual Studio 2019.

When you get the project to build and run, you should see a small sphere on top of a large sphere.  This is the hello world of the book series.

![Hello World](https://github.com/gamephysicsweekend/VulkanRenderer/blob/main/data/images/helloworld.jpg?raw=true)

## Usage

Scene.cpp is where you should begin writing the code from the book series.  And sprinkled throughout the rest of the code will be comments:

```
// TODO: Add code here
```

This is where you would fill in the code snippets from the texts.

## Controls

The controls for the renderer are very basic.

```
Mouse look to rotate the camera around the origin.
Scroll to zoom.
"R" to reset the scene.
"T" to pause and unpause time.
"Y" to step the simulation by a single frame (only works when the simulation is paused).
```


## Vulkan Resources

Although this "renderer" uses Vulkan, it is not intended as a resource for learning it.  Instead, I recommend the following:

[https://vulkan-tutorial.com/](https://vulkan-tutorial.com/)

[https://www.fasterthan.life/blog/2017/7/11/i-am-graphics-and-so-can-you-part-1](https://www.fasterthan.life/blog/2017/7/11/i-am-graphics-and-so-can-you-part-1)

[https://github.com/SaschaWillems/Vulkan](https://github.com/SaschaWillems/Vulkan)

[https://www.lunarg.com/vulkan-sdk/](https://www.lunarg.com/vulkan-sdk/)
