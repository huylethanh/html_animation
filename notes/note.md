### **Calculate basic trigonometric functions**

> `sine of angle = opposite / hypotenuse`
>
> `cosine of angle = adjacent / hypotenuse`
>
> `tangent of angle = opposite / adjacent` 
***
### **Convert radians to degrees and degrees to radians**


> `radians = degrees * Math.PI / 180.`
>
> `degrees = radians * 180 / Math.PI`

***
### **Rotate to the mouse (or any point)**

>*substitute mouse.x, mouse.y with the x, y point to rotate to*
>
>`dx = mouse.x – object.x; `
>
>`dy = mouse.y – object.y;` 
>
>`object.rotation = Math.atan2(dy, dx) * 180 / Math.PI; `
***
### **Convert angular velocity to x, y velocity**

>`vx = speed * Math.cos(angle);`
>
>`vy = speed * Math.sin(angle);`
***
### **Convert angular acceleration (any force acting on an object) to x,y cceleration**

>`ax = force * Math.cos(angle); `
>
>`ay = force * Math.sin(angle);`
***
### **Add acceleration to velocity**

>`vx += ax;`
> 
>`vy += ay; `
***
### **Add velocity to position**

>`object.x += vx; `
>
>`object.y += vy;`
***