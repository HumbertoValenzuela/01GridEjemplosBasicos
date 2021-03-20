# 01GridEjemplosBasicos
display: grid;  grid-template-columns. grid-column-start. grid-column: 2 / 4. grid-row: 1 / span 2.
```javascript
.servicios4 {
    margin-top: 1rem;
    border: 3px solid black;
    display: grid;  
    grid-template-columns: 50% 25% 25%;  
     /*agregando 4 filas  */
    grid-template-rows: 25% 25% 25% 25%;   
    height: 8rem;
}
.servicio4 {  
    color: white;
    text-align: center;
}
.servicio-1-3 {   
    background-color: darkviolet;
    /* span es el numero de lineas que quiero saltar. no contar el inicio */
    grid-column: 1 / span 1;
    grid-row: 1 / span 4;
    
}
.servicio-2-3 {
    background-color: limegreen;
    grid-column: 2 / span 2;
    grid-row: 1 / span 2;      
}
.servicio-3-3 { 
    background-color: teal;
    grid-column: 2 / span 2; 
    grid-row: 3 / span 2;
       
}
```
